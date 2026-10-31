# Install LocalEase

Download packages from the [latest release](https://github.com/ITineGTS/localease/releases/latest). Internet access is required to use the hosted API.

## Android

1. Download `LocalEase-android-release.apk` on your Android device.
2. Open the APK and follow Android's installation prompts. If required, permit APK installation for the trusted app you used to download it.
3. Open LocalEase and sign in or create a resident/provider account.

The APK supports Android 7.0 or later and uses the LocalEase release certificate. Existing installations must use the same signing certificate to update. The `.aab` file is for distribution tooling and cannot be installed by opening it on a phone.

## Windows x64

1. Download `LocalEase-windows-x64-release.zip`.
2. Extract the entire ZIP into a folder.
3. Run `firtsapp.exe` inside that folder.

Keep its DLLs and `data` directory beside the executable. The current Windows application is portable and unsigned.

## Linux x64

Download and extract `LocalEase-linux-x64-release.tar.gz`, then run the executable inside the complete bundle:

```bash
tar -xzf LocalEase-linux-x64-release.tar.gz
./LocalEase-linux-x64/firtsapp
```

Keep `lib` and `data` with the executable. This build was produced and dependency-checked on Ubuntu 26.04.1 x64; another distribution needs compatible GTK/GLib and runtime libraries.

## macOS

Download `LocalEase-macos-release.zip` and extract the application bundle. It supports Intel and Apple Silicon on macOS 12 or later.

The current app is ad hoc signed. Trusted public distribution requires Developer ID signing and notarization; an unsigned/ad hoc package may be rejected by macOS security policy. Use an appropriately signed release for ordinary deployment.

## iOS

`LocalEase-ios-unsigned.ipa` contains an iPhoneOS arm64 release build targeting iOS 15 or later. It is a developer artifact and cannot be installed directly on ordinary devices. Apple signing and a matching provisioning profile are required. It is not an App Store or TestFlight link.

## Web

The simplest way to use the browser version is to [open LocalEase](https://localease-api.onrender.com/).

No downloadable web package is included in the releases.

## Verify downloads

Compare the downloaded file with its entry in the release's `SHA256SUMS`:

```bash
sha256sum LocalEase-android-release.apk
```

On macOS use `shasum -a 256 FILE`; on Windows use `Get-FileHash FILE -Algorithm SHA256` in PowerShell.

## First use and help

Sign in or register through the application. Providers complete their profile, service rates and availability. Residents can browse and request a booking. Map permissions are requested when relevant; saved-location previews are labelled separately from live GPS.

Use Forgot Password for account recovery and the in-app LocalEase support flow for booking/account concerns. EasePay demo funds do not represent real payments. Check the release notes for package signing limits and known deployment requirements.
