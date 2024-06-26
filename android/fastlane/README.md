fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## Android

### android flutter_refresh_dependencies

```sh
[bundle exec] fastlane android flutter_refresh_dependencies
```

Get , Upgrade flutter dependencies and Statically analyze the Dart code for any errors.

### android decode_keystore

```sh
[bundle exec] fastlane android decode_keystore
```

Decode Keystore

### android set_up_key_properties

```sh
[bundle exec] fastlane android set_up_key_properties
```

Set up key.properties

### android build_apk

```sh
[bundle exec] fastlane android build_apk
```

Build apk

### android deployAndroid

```sh
[bundle exec] fastlane android deployAndroid
```

Deploy android

### android firebase_upload_android_local

```sh
[bundle exec] fastlane android firebase_upload_android_local
```

Firebase upload android using terminal

### android firebase_upload_android_pipeline

```sh
[bundle exec] fastlane android firebase_upload_android_pipeline
```

Firebase upload android using pipeline

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
