# Privacy Policy — TreadSpeed

**Effective date: 20 September 2026**

TreadSpeed is an Android application published by Paolo Villaflores
("the developer"). This policy explains what information the app handles —
in short: **none leaves your device**.

## What the app does

TreadSpeed turns your Android phone into a Bluetooth Low Energy (BLE)
"foot pod"/speed sensor. It broadcasts a treadmill speed you choose, plus
optionally a cadence value, so that a paired Garmin watch (or another BLE
receiver) can use it as a pace source during indoor runs.

## Data collection and sharing

- The app does **not** collect, store, transmit, or share any personal
  data. There is no analytics, no advertising, no tracking, no crash
  reporting, and no account system.
- The app has **no internet permission**. It is technically incapable of
  sending anything anywhere over the network.
- The app does not access your contacts, photos, files, location, or
  microphone.

## Bluetooth data

The app broadcasts speed, distance, and cadence values over BLE to
devices you explicitly pair (for example, your own Garmin watch). This
data exists only for the duration of your activity, lives only on your
phone and your watch, and is never transmitted to the developer or any
third party. Your watch's own app (e.g. Garmin Connect) handles that
device's data under its own privacy policy.

## Permissions the app requests and why

| Permission | Purpose |
|---|---|
| Bluetooth Advertise / Connect / Scan | To advertise the phone as a BLE sensor and manage the connection to your watch. Location is **not** used to derive position (scan permission is declared `neverForLocation`). |
| Foreground service (connected device) | Keeps the BLE broadcast alive while you run with the screen off. |
| Notifications | Shows a static "broadcasting" status notification required for the foreground service. |

## Children

The app is not directed at children under 13 and does not knowingly
collect any data from anyone, of any age.

## Changes to this policy

If the app's behaviour changes, this policy will be updated on this page
with a new effective date. The version of the app you install will always
be accompanied by the policy in effect for it.

## Contact

Questions about this policy or the app:


pbvillaflores@gmail.com
