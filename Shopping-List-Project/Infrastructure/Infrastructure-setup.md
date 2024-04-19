# Create non root user

```
TODO - write commands to create the user and give the correct privileges
```



# Create a user
```
sudo adduser shoppinglist`
sudo usermod -aG sudo shoppinglist
```

Add the following lines at the end of the /etc/sudoers file:
```
shoppinglist ALL=(ALL) NOPASSWD: ALL
```

# Install Docker

```
sudo apt update
sudo apt-get install docker.io
```

# Install Docker Compose

```
sudo curl -L https://github.com/docker/compose/releases/download/1.21.0/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose

sudo chmod +x /usr/local/bin/docker-compose

After you do the curl command , it'll put docker-compose into the

/usr/local/bin

which is not on the PATH. To fix it, create a symbolic link:

sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
And now if you do: docker-compose --version

You'll see that docker-compose is now on the PATH
```
# Transfer first dockercompose

Transfer project file /infra/docker-compose.yml into /home/shoppinglist/infra

# To start docker and daemon
```
sudo systemctl start docker
sudo systemctl status docker

sudo dockerd
```