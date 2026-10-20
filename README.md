<div align="center">

# RaveLights

**An unofficial, experimental Android remote for RaveLights Bluetooth rope lights.**

[![Download](https://img.shields.io/github/v/release/EricGrain/RaveLights-App?label=Download&color=12B5F5)](https://github.com/EricGrain/RaveLights-App/releases/latest)
![Android 8+](https://img.shields.io/badge/Android-8.0%2B-3DDC84)
![Unofficial](https://img.shields.io/badge/Status-Unofficial%20%26%20Experimental-FF5FC8)

</div>

> **Not the official RaveLights app.** This is a fan-made remote by Eric Gray / Monkey. It is not affiliated with, endorsed by, or supported by the RaveLights company. RaveLights and its logo belong to their owners. The Howloween name and logo belong to Howloween, and this app is not made or endorsed by them.

<!-- Screenshots: edit this file on GitHub and drag your images in here. -->

---

## What it does

Pick colors, set the brightness and mode, run light shows, and see all your lights at once, from your phone.

| | |
|---|---|
| **Colors and modes** | Tap a glowing coil to pick a palette, drag the brightness bar, switch between the three modes. |
| **Your lights, on screen** | Every light shows up as its own rope, with your own lights always first. Drag them around, rename them, and the app remembers them. Lights it can't hear turn grey instead of vanishing. |
| **Busy rooms** | At a party, other people's lights fold away under one row so yours don't get lost, and the app forgets them after a while. Long-press any light to pin it to the top or hide it. **Find my light** picks yours out of the crowd: change the color on your light and the app spots which one changed. |
| **Light shows** | Beat-timed dances: Beat chase, Heartbeat, Build & drop, Pop song and Random disco, with tap tempo and half-time. |
| **Patterns** | Breathe, Crossfade, Sparkle, Sunrise and your own Playlist of colors. |
| **Palette colors** | The lights only say "palette 12". The app knows what color each one is out of the box. If yours look different, re-teach them in More > Colors, and hide the palettes you don't use. |
| **Getting started** | A "Just got your lights?" welcome for first-time users, plus a step-by-step guide in More. |
| **Easter egg** | There's a little surprise hidden in this version for a certain October event. You'll know it when you see it. |
| **What's new** | A change log pops up once after each update and lives in More > About. |

## Install

1. On your Android phone, open the [**latest release**](https://github.com/EricGrain/RaveLights-App/releases/latest).
2. Download the **RaveLights APK** (the file ending in `.apk`) and open it.
3. If Android asks, allow your browser (or Files app) to **install unknown apps**. Android also warns about apps that don't come from the Play Store. That is expected here.
4. Open RaveLights, read the quick heads-up, and allow **Nearby devices** (Android asks for Location on some versions too, because Bluetooth scanning needs it. The app doesn't read your location).

Needs Android 8.0 or newer and a phone with Bluetooth Low Energy.

**A light has to be paired with another light once.** After that it works with the app on its own, even with the other light switched off and after restarts. Only own one light? Pair it once with a friend's. A brand-new or unpaired light has its radio switched off, so the app can't talk to it.

## Getting your lights connected

For best results the lights should be **paired to each other first**, then the app follows them. The full steps are in the app under **More > Getting started**. The short version:

1. Update your lights to the latest firmware.
2. Pair two (or more) lights with each other using the buttons on the lights.
3. Open RaveLights. Your lights appear under **My lights**. If they don't, tap **Use** under one. Lots of lights around? Tap **Find my light** and change the color on yours.
4. **Can't see your lights?** Cycle through a few colors on the lights themselves. Lights can go quiet when nothing is changing, and a color change makes them speak up so the app can find them.

## How it works

RaveLights lights talk to each other with small Bluetooth messages. This app listens for those messages and sends the same kind, so your lights treat the phone like another light in their group.

- It doesn't connect to your lights or change their firmware.
- It can only do what the lights already know how to do: three modes, a set of palettes, and brightness.
- Because it never touches the firmware, damage is unlikely, but that can't be promised.

## Good to know

- **Experimental.** It may not work with every light or firmware version, and a firmware update on your lights can change how it behaves.
- **Beat-timed shows will drift.** Bluetooth has a delay, so shows that follow a BPM are very likely to look a little out of time. Slower tempos work best, and the Lead and Half-time settings help.
- **Smart Brightness can fight the app.** Newer light firmware can manage its own brightness to save battery, which can override what you set here. The app shows whether it's on and has a **Smart Brightness switch** on the Lights tab to turn it on or off. You can also switch it off on a light: hold + and − and move the brightness indicator away from the magnet position.
- **Foldable phones.** The app re-fits itself when you fold, unfold or rotate, and a running show keeps going. When your phone is half-folded (flex mode), the Lights screen splits at the fold: the lights on one half and the controls on the other, and scrolling the controls doesn't move the lights. On tablets and other wide screens, each side scrolls on its own too. The options are under More → Screen.
- **Lay the ropes out.** The ropes are stiff and springy like a real rope light. Drag them with one finger or several, even both ends of one rope at once. Where you drop a rope, it stays. Double-tap a rope to coil it again.
- **Changes may not land on every light at the same moment.** Range is limited and busy places can drop messages.
- **Flashing lights can trigger seizures** in people with photosensitive epilepsy. Use the Slow patterns if you're unsure, and warn anyone nearby.
- **Danger zone.** Experimental tools (raw packets, hidden-mode lab, the packet log) live behind a locked **More > Danger zone**. Leave it locked unless you know what they do.

**Use it at your own risk. I'm not responsible for any problem, damage or loss that results from using this app, including to your lights, your phone, your event, or your dance moves.**

## Updates and privacy

The app can check this page for a newer version when it opens (at most once a day, and you can turn it off under **More > About**). It only downloads one small text file, `latest.json`. Nothing about you or your lights is sent. That's the only time the app uses the internet.

When an update is available, **Download** opens the new APK in your browser. Open the file to install it. Your settings are kept.

## Found a problem?

Tap **More > Report a problem** in the app: it opens a new issue here with your phone and app details already filled in. Or [open an issue](https://github.com/EricGrain/RaveLights-App/issues) yourself. It helps a lot to include:

- your phone model and Android version
- the app version (**More > About**) and, if you know it, your lights' firmware version
- what you did, and what you expected to happen
- optionally, the packet log: **More > Danger zone > unlock > Log > Copy all**

---

<div align="center">
Made by Eric Gray / Monkey. Not affiliated with the official RaveLights company.<br>
Thank you to Toxmo and Howloween for the artwork. This app is not affiliated with Howloween.
</div>
