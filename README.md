# MCPETransfer

[![Join the chat at https://gitter.im/ImagicalCorp/MCPETransfer](https://badges.gitter.im/ImagicalCorp/MCPETransfer.svg)](https://gitter.im/ImagicalCorp/MCPETransfer?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

MCPETransfer is a fork of @jython234's BouncyBall proxy for PocketMine that makes transferring clients from one PocketMine server to another possible,

## Software Requirements

- [Oracle JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Apache Maven](https://maven.apache.org/)

If you are on Windows, you might need to add the JDK and Maven bin folders to your PATH. 

## How to use MCPETransfer

You can download a pre-compiled STABLE JAR [here](http://teamcity.beaconpe.net/repository/download/BouncyBall_BouncyBuild/27:id/BouncyBall-1.0-SNAPSHOT.jar) (When prompted, click "login as guest" button).

If you want to compile from source (to get a latest build), read on:

After you installed JDK and Maven, just download a zip of the repo and then do:

```
mvn package
```

Running the Maven package will create a JAR for you in the "target" folder.

To run the software do:

```
java -jar BouncyBall-1.0-SNAPSHOT.jar
```

You can edit config.yml to your liking.

## Any Problems?
Contact @jython234 at jython234@blockserver.org, or on the BeaconPE forums: http://beaconpe.net/forums.
