# ITSAppUsesNonExemptEncryption for Cordova

[![Build Status](https://travis-ci.org/adriano-di-giovanni/cordova-plugin-ITSAppUsesNonExemptEncryption.svg?branch=master)](https://travis-ci.org/adriano-di-giovanni/cordova-plugin-ITSAppUsesNonExemptEncryption)

> This plugin adds [export compliance](Add export compliance information for apps using exempt encryption only) information to apps using exempt encyption only.

This plugin should be used only if the app meets any of the following:

* Qualifies for one or more exemptions provided under category 5 part 2
* Use of encryption is limited to encryption within the operating system (iOS or macOS)
* Only makes call(s) over HTTPS
* App is made available only in the U.S. and/or Canada

The information is provided by adding the following key to the `Info.plist` file.

```xml
<key>ITSAppUsesNonExemptEncryption</key><false/>
```

## Installation

```
cordova plugin add cordova-plugin-itsappusesnonexemptencryption
```

## Supported platforms

* iOS

## License

This project is [MIT-licensed](LICENSE)
