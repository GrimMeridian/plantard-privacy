# Plantard Privacy Policy

**Effective date:** May 19, 2026
**App:** Plantard for iOS
**Developer:** GrimMeridian LLC
**Contact:** njmalack97@outlook.com

This is the privacy policy for the iOS app Plantard. It explains what the app collects, where that information lives, and what we do (and don't do) with it.

The short version: **Plantard stores everything you enter on your device. We do not run servers, we do not have user accounts, we do not collect analytics, and we do not share or sell your data.** The only network call Plantard makes is to Apple's WeatherKit service for local weather, described below.

---

## What Plantard stores on your device

The following information is saved locally on your iPhone or iPad and never leaves it:

- **Plant entries** you create — nickname, species, watering frequency, last-watered date, optional potted and repotted dates, and any notes you type.
- **Plant photos** you take with the camera or choose from your photo library. Photos are stored inside the app's local database (Apple's SwiftData store). They are not uploaded anywhere.
- **Your garden name** and the time of day you'd like watering reminders to fire — saved as device preferences (`UserDefaults`).

All of this data is included in your iCloud Device Backup if you have backups enabled, and is removed when you delete the app.

## Notifications

If you grant notification permission, Plantard schedules local reminders on your device using iOS's `UserNotifications` framework. These are generated and delivered by iOS itself; nothing is sent to or from a server. You can revoke notification permission at any time in iOS Settings → Notifications → Plantard.

## Location and Weather

If you grant location permission (When in Use), Plantard reads your approximate location and sends it to **Apple's WeatherKit service** to fetch the current temperature and conditions, which are displayed as a small chip on the main screen.

- Plantard does **not** store your location.
- Plantard does **not** transmit your location anywhere except to Apple's WeatherKit.
- Apple's handling of WeatherKit requests is governed by [Apple's privacy policy](https://www.apple.com/legal/privacy/).

If you deny location permission, Plantard works normally — the weather chip is simply hidden.

## Camera and Photos

If you grant camera or photo-library access, Plantard uses that access **only** to let you attach a photo to a plant. The selected or captured image is stored in Plantard's local database alongside that plant's other data. Plantard does not upload, share, or analyze your photos.

## What Plantard does *not* do

- We do not collect analytics, telemetry, crash reports, or usage data.
- We do not use any third-party SDKs (no Firebase, no Crashlytics, no advertising networks).
- We do not show ads.
- We do not track you across apps or websites. The App Tracking Transparency framework is not used because we do not track.
- We do not have user accounts, logins, or cloud sync. There are no servers operated by GrimMeridian LLC that store Plantard user data.
- We do not sell, rent, or share any information with third parties.

## Children's privacy

Plantard does not knowingly collect any information from anyone, including children under 13. Because all data stays on the device and there are no accounts, there is no information for us to receive from a child's use of the app.

## Your choices

- **Delete a plant** to remove its data (including its photo) from the device.
- **Revoke permissions** at any time in iOS Settings → Plantard. The relevant toggles are Notifications, Location, Camera, and Photos.
- **Delete the app** to remove all Plantard data from your device. There is no separate "delete account" step because there is no account.

## Changes to this policy

If we change this policy in a future version of Plantard, the updated text will be posted at this URL and the effective date at the top will be updated. Material changes will also be noted in the App Store release notes for the version that introduces them.

## Contact

Questions or concerns? Email njmalack97@outlook.com

— Grim Meridian LLC
