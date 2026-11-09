# LocalEase

LocalEase helps residents find nearby service providers, request appointments, message about the job and follow its progress. Providers can manage their services, pricing, availability and assigned work.

**[Open the web app](https://localease-api.onrender.com/)** · **[Download the latest release](https://github.com/ITineGTS/localease/releases/latest)** · **[Installation guide](INSTALL.md)**

## What you can do

- Residents and guests can browse services and search for providers; provider/admin/developer accounts use their role-specific workspace.
- Review provider details, service prices and customer reviews.
- Book a service using an address, saved destination and confirmed map pin.
- View available hours and discuss quotes or appointment changes.
- Search around a chosen location with an editable distance and category filters.
- Refine provider discovery with multiple service categories, rating, billing basis, standard-rate range, verified-provider and completed-job filters.
- Chat naturally with the assistant without being forced to provide an address. Add or change an optional map pin for nearby service results, or open a private LocalEase support case when reporting a problem.
- View compact pointed map pins with category icons and colors; tap a provider/store result marker to open its details and booking options.
- Offer multiple service categories and request new categories for admin review.
- Providers can decline pending requests but cannot cancel ongoing jobs; residents can cancel their own active booking, and administrators can cancel active bookings.
- Start work after the resident accepts the required quote, with clear feedback when a booking action is unavailable.
- Message the other participant and follow the booking's progress.
- Use provider-shared GPS or clearly labelled saved-location previews.
- Leave reviews with up to three photos and submit private reports to LocalEase support.
- Reach support from more screens, use clearer notification delivery status, and navigate wide-screen pages with desktop scrollbars.
- Get consistent loading, empty, offline, expired-session and retry states across the marketplace, communication, provider and administration screens.
- Providers can use explicit foreground or active-job background GPS sharing with clearer consent and status controls on supported mobile platforms.
- Use English or Filipino and light or dark appearance.

EasePay currently uses **demo balances**, alongside Cash on Site records. Demo funds are not real money or a payment gateway. LocalEase is a capstone application; current downloads should not be taken as app-store certification or a guarantee about providers.

The demo catalogue includes 120 stores spread across all 17 NCR cities and municipalities. Their addresses and map pins use imported street reference points and represent synthetic demo locations.

## Release update — November 9, 2026

LocalEase 1.0.8 (build 10) updates the native applications with clearer administration analytics, responsive summaries, improved search-centre/radius controls, location selection and live-map/GPS controls.

The coordinated backend update adds persistent login sessions, transaction sorting, a detailed management report and faster bounded tracking responses. The compiled web bundle and backend source are prepared privately. Hosted activation is separate from native publication; consult the release notes for its verified status.

Review photos are public while their review is visible. Avoid faces, addresses and private documents.

## Downloads

**Current release: LocalEase 1.0.8 (build 10).**

| Platform | Package | Notes |
|---|---|---|
| Android | APK | Signed app for direct installation; Android 7.0 or later. |
| Windows x64 | ZIP | Portable unsigned application. |
| Linux x64 | tar.gz | Complete compiled application bundle; GTK 3 and glibc 2.34 or newer. |

The [release page](https://github.com/ITineGTS/localease/releases/latest) contains compiled native downloads, including Linux; SHA-256 hashes appear in the release notes and `SHA256SUMS`. Older releases remain available in the release history. The [installation guide](INSTALL.md) explains which package to use.

Android remote push delivery still requires backend sender activation and real-device verification; this release does not certify foreground, background or closed-app delivery.

## Source and privacy

This repository contains only the app overview and installation guide. Application development source is maintained privately and is not published in this Git history or its automatic source archives.

Release downloads contain compiled applications and required runtime assets. Third-party dependency notices remain bundled with the applications; debugging maps and private signing/backend credentials are excluded from public downloads.

Use in-app LocalEase support for account or booking concerns. Avoid putting passwords, verification codes, private addresses or other account information in public GitHub posts.
