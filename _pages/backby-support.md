---
title: "BackBy Support"
permalink: /projects/backby/support/
---

BackBy helps you explore freely and get back on time by estimating when you should return to a chosen location.

## Contact

For support, contact `web [at] jacksuzuki [dot] com`.

When reporting a problem, please include:

- The BackBy app version and build number.
- Your iOS version and device model.
- The travel mode you were using: Walk, Cycle, Drive, or Transit.
- Whether Location, Notifications, Motion Activity, and Alarm access were allowed.
- What you expected to happen and what actually happened.

## Diagnostics

BackBy includes an Observability screen that can export diagnostics for troubleshooting.

Diagnostics are not sent automatically. You choose when to email or share them. Enhanced Diagnostics is off by default. When Enhanced Diagnostics is off, exported diagnostics remove path history and round coordinates to an approximate location. When Enhanced Diagnostics is on, diagnostics may include high-precision coordinates and a short recent path history.

If you are asked to send diagnostics, use the in-app diagnostics export and review the email or share sheet before sending.

## Common Questions

### Why does BackBy ask for location access?

BackBy uses your location to estimate how long it will take to return to your selected target. During an active session, BackBy may request Always location access so it can keep estimates and alerts working more reliably while your phone is locked or the app is in the background.

### Why does BackBy ask for notification or alarm access?

BackBy uses notifications and alarms to alert you when it is time to head back. If alarm access is not available or not allowed, BackBy falls back to regular notifications with reduced reliability.

### Why does BackBy ask for motion activity access?

BackBy may use motion activity during active sessions, especially Transit sessions, to avoid unnecessary ETA refreshes while you are already moving between stops.

### Why is my ETA unavailable or out of date?

BackBy relies on location quality, Apple MapKit routing, and network availability for some travel modes. Driving and Transit estimates may require network access. If the current estimate cannot be refreshed, BackBy may show an unknown or stale ETA until better data is available.

### Why did I not receive a turn-back alert?

Check that notifications are allowed for BackBy, that Focus or silent settings are not suppressing alerts, and that alarm access is enabled if your iOS version supports it. Background refresh and exact timing are best-effort on iOS, so BackBy also keeps the active session visible in the app and through Live Activities when available.

### Does the Tip Jar unlock features?

No. Tips are optional one-time App Store purchases and do not unlock features or change app behavior.

### How do I delete BackBy data?

BackBy stores normal app data locally on your device. Delete the app to remove local BackBy data from the device. If you sent support email or diagnostics and want those messages deleted, contact `web [at] jacksuzuki [dot] com`.

## Links

- [BackBy project page]({{ '/projects/backby/' | relative_url }})
- [BackBy privacy policy]({{ '/projects/backby/privacy/' | relative_url }})
