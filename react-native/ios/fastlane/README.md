fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios match_certificates

```sh
[bundle exec] fastlane ios match_certificates
```

Sync certs, profiles, keys for all targets

### ios prepare_certs

```sh
[bundle exec] fastlane ios prepare_certs
```

Get appstore certs

### ios bump_version

```sh
[bundle exec] fastlane ios bump_version
```

Bump build numbers from latest testflight. Setup version number

### ios build

```sh
[bundle exec] fastlane ios build
```

Build ios app

### ios deploy_testflight

```sh
[bundle exec] fastlane ios deploy_testflight
```

Build and push a new release build to testflight

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
