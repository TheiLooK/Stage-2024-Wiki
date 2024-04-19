# Requirements
- IntelliJ Idea
Plugins: MapStruct Support, Maven Helper, SonarLint, Flutter
Dev options on mobile for debug: https://developer.android.com/studio/debug/dev-options?hl=fr#enable
- JDK 21 (https://jdk.java.net/21/)
- SpringBoot 
- Maven 3.8+ (add Maven path in IntelliJ settings)
- Docker Desktop
- Flutter SDK (https://docs.flutter.dev/get-started/install/windows/mobile)
 Once Flutter is installed, the Dart's SDK is located at /flutter/bin/cache/dart-sdk
Flutter doc: https://docs.flutter.dev/

To verify if Flutter is well installed, use 'flutter doctor' on your cmd.
To fix the Android's sdk issue you need to go in the Android's Studio sdk manager, SDK Tools and check 'Android SDK Command-line Tools' to install it.
To fix the Android's licenses, use 'flutter doctor --android-licenses' on your cmd.

# Retrieve project code
1. Create new project in IntelliJ from version control
 Url: https://eddaluxembourg@dev.azure.com/eddaluxembourg/2024-STAGE-ShoppingList/_git/2024-STAGE-ShoppingList

2. Connect with your Edda account. A personnal access token will be automatically generated for IntelliJ in Azure Devops User settings

# SpringBoot
The project structure has been setup using Spring Initialzr (https://start.spring.io/)

![image.png](/.attachments/image-c401fe0f-a506-4a2f-9c04-2c9c5ff2a1aa.png)
Note: IntelliJ also provides Spring Initializer project wizard.

# Setup API authentification in Flutter

- Create .env file at root (`shoppinglist/.env`) and put this inside: `API_KEY=[TOKEN HERE]`. You can find the token in azure: Pipelines -> Library -> ShoppingListAPIVariables -> API_KEY

- Do this command `flutter pub run build_runner build`

# Docker
First : you need install maven : 'mvn clean install'
Second : you need to build the docker : 'docker build -t target/shoppinglist-0.0.1-snapshot.war .'
Third : you need to start the first time in the cmd before any start with docker : 'docker-compose up --build'
Fourth : You can stop it. You havn't UI swagger interface but the application works. You can start it from Docker Desktop now.


