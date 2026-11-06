# Install LocalEase

Download packages from the [latest release](https://github.com/ITineGTS/localease/releases/latest). Internet access is required to use the hosted API.

## Android

1. Download `LocalEase-android-release.apk` on your Android device.
2. Open the APK and follow Android's installation prompts. If required, permit APK installation for the trusted app you used to download it.
3. Open LocalEase and sign in or create a resident/provider account.

The current APK is version 1.0.7 (build 9), with Android version code 9. The APK supports Android 7.0 or later and uses the LocalEase release certificate. Existing installations use the same signing certificate to update.

Android remote push remains dependent on backend sender activation and real-device delivery tests; publishing this APK does not activate the sender.

## Windows x64

1. Download `LocalEase-windows-x64-release.zip`.
2. Extract the entire ZIP into a folder.
3. Run `firtsapp.exe` inside that folder.

Keep its DLLs and `data` directory beside the executable. The current Windows application is portable and unsigned.

## Linux x64

1. Download `LocalEase-linux-x64-release.tar.gz`.
2. Extract the complete bundle:

   ```bash
   tar -xzf LocalEase-linux-x64-release.tar.gz
   cd LocalEase-linux-x64
   ./firtsapp
   ```

Keep the executable, `lib` and `data` directories together. This is an x86-64 Linux
application, not an ARM build. It requires GTK 3, glibc 2.34 or newer, and compatible
system runtime libraries (including libstdc++ with GLIBCXX 3.4.21 or newer).
Ubuntu 22.04/newer or an equivalent supported desktop Linux distribution meets the
glibc baseline when the required GTK/runtime packages are installed. Distribution
and real-device acceptance beyond the build host remain separate checks.


## Web

The simplest way to use the browser version is to [open LocalEase](https://localease-api.onrender.com/).

No downloadable web package is included in the releases. The hosted web app and backend were updated together on November 6, 2026; native packages keep their own release version. If an already-open browser shows the older interface, reload the page (Ctrl+Shift+R on Windows/Linux, or Command+Shift+R on macOS).

## Verify downloads

Compare the downloaded file with its SHA-256 hash in the release notes or the `SHA256SUMS` asset:

```bash
sha256sum LocalEase-android-release.apk
```

On Windows use `Get-FileHash FILE -Algorithm SHA256` in PowerShell.

## First use and help

Sign in or register through the application. Providers complete their profile, service rates and availability. Residents can browse and request a booking. Map permissions are requested when relevant; saved-location previews are labelled separately from live GPS. In location search, small pointed markers show each store's category. In the updated web app, tap a provider/store result marker to open its details and booking options; centre-selection controls remain separate. Version 1.0.7 native builds use this updated flow; older native builds may show the saved-address/centre-selection flow instead. The map shows published stores; search results follow the distance and filters you choose.

The assistant uses Photon’s best mapped address match as a chat-local search point, not a verified house entrance or an automatically confirmed booking destination.

Use Forgot Password for account recovery and the in-app LocalEase support flow for booking/account concerns. EasePay demo funds do not represent real payments. Check the release notes for package signing limits and known deployment requirements.
