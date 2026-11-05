# Install LocalEase

Download packages from the [latest release](https://github.com/ITineGTS/localease/releases/latest). Internet access is required to use the hosted API.

## Android

1. Download `LocalEase-android-release.apk` on your Android device.
2. Open the APK and follow Android's installation prompts. If required, permit APK installation for the trusted app you used to download it.
3. Open LocalEase and sign in or create a resident/provider account.

Build 5 is version 1.0.3 with Android version code 5. The APK supports Android 7.0 or later and uses the LocalEase release certificate. Existing installations use the same signing certificate to update.

Android remote push remains dependent on backend sender activation and real-device delivery tests; publishing this APK does not activate the sender.

## Windows x64

1. Download `LocalEase-windows-x64-release.zip`.
2. Extract the entire ZIP into a folder.
3. Run `firtsapp.exe` inside that folder.

Keep its DLLs and `data` directory beside the executable. The current Windows application is portable and unsigned.

## Earlier Apple packages

Build 5 is distributed for Android and Windows only. Apple packages below refer to earlier releases and are not part of the latest download.

### macOS

Download `LocalEase-macos-release.zip` and extract the application bundle. It supports Intel and Apple Silicon on macOS 12 or later.

The current app is ad hoc signed. Trusted public distribution requires Developer ID signing and notarization; an unsigned/ad hoc package may be rejected by macOS security policy. Use an appropriately signed release for ordinary deployment.

### iOS

`LocalEase-ios-unsigned.ipa` contains an iPhoneOS arm64 release build targeting iOS 15 or later. It is a developer artifact and cannot be installed directly on ordinary devices. Apple signing and a matching provisioning profile are required. It is not an App Store or TestFlight link.

## Web

The simplest way to use the browser version is to [open LocalEase](https://localease-api.onrender.com/).

No downloadable web package is included in the releases.

## Verify downloads

Compare the downloaded file with its SHA-256 hash in the release notes or the `SHA256SUMS` asset:

```bash
sha256sum LocalEase-android-release.apk
```

On macOS use `shasum -a 256 FILE`; on Windows use `Get-FileHash FILE -Algorithm SHA256` in PowerShell.

## First use and help

Sign in or register through the application. Providers complete their profile, service rates and availability. Residents can browse and request a booking. Map permissions are requested when relevant; saved-location previews are labelled separately from live GPS. In location search, small pointed markers show each store's category. Tap a marker to view its saved address or use it as the search centre. The map shows published stores; search results follow the distance and filters you choose.

Use Forgot Password for account recovery and the in-app LocalEase support flow for booking/account concerns. EasePay demo funds do not represent real payments. Check the release notes for package signing limits and known deployment requirements.
