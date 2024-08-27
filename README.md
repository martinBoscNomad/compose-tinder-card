## How to build the library locally

Include the following snippet in your `local.gradle` file and do a Gradle Sync:
```gradle
sonatypeStagingProfileId=
ossrhUsername=
ossrhPassword=
signing.keyId=
signing.key=
signing.password=
```

The above parameters are used for publishing the library and are not required for development.

## Compile jar file

In `build.gradle` `lib` module, run task `createJar`
The generated jar with be there: root/lib/libs/jars/



