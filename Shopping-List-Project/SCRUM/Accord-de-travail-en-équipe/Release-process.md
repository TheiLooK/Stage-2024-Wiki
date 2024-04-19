# SNAPSHOT  / RELEASE
The SNAPSHOT value refers to the 'latest' code along a development branch, and provides no guarantee the code is stable or unchanging. Conversely, the code in a 'release' version (any version value without the suffix SNAPSHOT) is unchanging.

In other words, a SNAPSHOT version is the 'development' version before the final 'release' version. The SNAPSHOT is "older" than its release.

During the release process, a version of x.y-SNAPSHOT changes to x.y. The release process also increments the development version to x.(y+1)-SNAPSHOT. For example, version 1.0-SNAPSHOT is released as version 1.0, and the new development version is version 1.1-SNAPSHOT.

# Release process

``mvn release:clean``


``mvn release:prepare``

- Changement de version dans le pom (ex: 00.01-SNAPSHOT -> 00.01)
- Build + JUnit Test application
- Tag version dans git
- Changement de version dans le pom (ex: 00.01 -> 00.02-SNAPSHOT) pour les prochains developpements

