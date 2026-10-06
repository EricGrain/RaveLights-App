<div align="center">

# RaveLights

**An unofficial, experimental Android remote for RaveLights Bluetooth rope lights.**

[![Download](https://img.shields.io/github/v/release/EricGrain/RaveLights-App?label=download&color=7048E0)](https://github.com/EricGrain/RaveLights-App/releases/latest)
![Android 8+](https://img.shields.io/badge/Android-8.0%2B-3DDC84)
![Unofficial](https://img.shields.io/badge/status-unofficial%20%26%20experimental-FF5FC8)

</div>

> **Not the official RaveLights app.** This is a fan-made remote by Eric Gray. It is not affiliated with, endorsed by, or supported by the RaveLights company. RaveLights and its logo belong to their owners.

<!-- Screenshots: edit this file on GitHub and drag your images in here. -->

---

## What it does

Pick colors, set the brightness and mode, run light shows, and see all your lights at once, from your phone.

| | |
|---|---|
| **Colors and modes** | Tap a glowing coil to pick a palette, drag the brightness bar, switch between the three modes. |
| **Your lights, on screen** | Every light shows up as its own rope. Drag them around, rename them, and the app remembers them. Lights it can't hear turn grey instead of vanishing. |
| **Light shows** | Beat-timed dances: Beat chase, Heartbeat, Build & drop, Pop song and Random disco, with tap tempo and half-time. |
| **Patterns** | Breathe, Crossfade, Sparkle, Sunrise and your own Playlist of colors. |
| **Learn palettes** | The lights only say "palette 12". Teach the app what color that is, and hide the palettes that don't work. |
| **Pairing guide** | A step-by-step guide inside the app, including what to try with a single light. |

## Install

1. On your Android phone, open the [**latest release**](https://github.com/EricGrain/RaveLights-App/releases/latest).
2. Download **RaveLights-1.0.apk** and open it.
3. If Android asks, allow your browser (or Files app) to **install unknown apps**. Android also warns about apps that don't come from the Play Store. That is expected here.
4. Open RaveLights, read the quick heads-up, and allow **Nearby devices** (Android asks for Location on some versions too, because Bluetooth scanning needs it. The app doesn't read your location).

Needs Android 8.0 or newer and a phone with Bluetooth Low Energy.

## Getting your lights connected

For best results the lights should be **paired to each other first**, then the app follows them. The full steps are in the app under **More > Pairing guide**. The short version:

1. Update your lights to the latest firmware.
2. Pair two (or more) lights with each other using the buttons on the lights.
3. Open RaveLights. Your lights appear under **My lights**. If they don't, tap **Use** under one.
4. **Can't see your lights?** Cycle through a few colors on the lights themselves. Lights can go quiet when nothing is changing, and a color change makes them speak up so the app can find them.

A single unpaired light often ignores the app. You can try putting it in pairing mode and tapping **Use**, but it may not work.

## How it works

RaveLights lights talk to each other with small Bluetooth messages. This app listens for those messages and sends the same kind, so your lights treat the phone like another light in their group.

- It doesn't connect to your lights or change their firmware.
- It can only do what the lights already know how to do: three modes, a set of palettes, and brightness.
- Because it never touches the firmware, damage is unlikely, but that can't be promised.

## Good to know

- **Experimental.** It may not work with every light or firmware version, and a firmware update on your lights can change how it behaves.
- **Beat-timed shows will drift.** Bluetooth has a delay, so shows that follow a BPM are very likely to look a little out of time. Slower tempos work best, and the Lead and Half-time settings help.
- **Changes may not land on every light at the same moment.** Range is limited and busy places can drop messages.
- **Flashing lights can trigger seizures** in people with photosensitive epilepsy. Use the Slow patterns if you're unsure, and warn anyone nearby.
- **Danger zone.** Experimental tools (raw packets, hidden-mode lab, the packet log) live behind a locked **More > Danger zone**. Leave it locked unless you know what they do.

**Use it at your own risk. I'm not responsible for any problem, damage or loss that results from using this app, including to your lights, your phone, your event, or your dance moves.**

## Updates and privacy

The app can check this page for a newer version when it opens (at most once a day, and you can turn it off under **More > About**). It only downloads one small text file, `latest.json`. Nothing about you or your lights is sent. That's the only time the app uses the internet.

When an update is available, **Download** opens the new APK in your browser. Open the file to install it. Your settings are kept.

## Found a problem?

Please [open an issue](https://github.com/EricGrain/RaveLights-App/issues). It helps a lot to include:

- your phone model and Android version
- the app version (**More > About**) and, if you know it, your lights' firmware version
- what you did, and what you expected to happen
- optionally, the packet log: **More > Danger zone > unlock > Log > Copy all**

---

<div align="center">
Made by Eric Gray. Not affiliated with the official RaveLights company.
</div>
