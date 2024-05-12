# Developer Guide

This document describes how to build and run **shopsync3** for **backend**

# Docker

## Build

./mvnw spring-boot:build-image -Dspring-boot.build-image.imageName=kamilmucik/shopsync3-middletier:0.0.1-SNAPSHOT


# Release

## dry run

```markdown
mvn -B -DdevelopmentVersion="0.0.2-SNAPSHOT" -DreleaseVersion="0.0.1" -Dresume=false release:prepare release:perform
```

```markdown
git push
```
