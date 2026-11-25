<div align="center">

# RaveLights

**An unofficial, experimental Android remote for RaveLights Bluetooth rope lights.**

[![Download](https://img.shields.io/github/v/release/EricGrain/RaveLights-App?label=Download&color=12B5F5)](https://github.com/EricGrain/RaveLights-App/releases/latest)
![Android 8+](https://img.shields.io/badge/Android-8.0%2B-3DDC84)
![Unofficial](https://img.shields.io/badge/status-Unofficial%20%26%20Experimental-FF5FC8)

</div>

> **Not the official RaveLights app.** This is a fan-made remote by Eric Gray / Monkey. It is not affiliated with, endorsed by, or supported by the RaveLights company, Howloween or VancouFur. Their names, logos and artwork belong to their owners.

<!-- Screenshots: edit this file on GitHub and drag your images in here. -->

---

## What it does

Pick colors, set the brightness and mode, run light shows, and see all your lights at once, from your phone. It can also pair a light with your phone, so you don't need a second light to get started.

| | |
|---|---|
| **Colors and modes** | Tap a glowing coil to pick a palette, drag the brightness bar, switch between the three modes. |
| **Pair with your phone** | Tap **+ Add a Light**, hold − and + on the light until it pulses purple, and the phone does the rest. No second light needed, and it's also how you add a light to your group. |
| **Scenes** | Save a look (mode, colors and brightness) and bring it back with one tap. |
| **Your lights, on screen** | Every light shows up as its own rope, with your own lights always first. Drag them around, rename them, and the app remembers them. A light it can't hear stays in your list, greyed out, with when it was last seen. |
| **Busy rooms** | At a party, other people's lights fold away under one row so yours don't get lost, and the app forgets them after a while. Hold any light to pin it to the top or hide it. **Which Light Is Mine?** picks yours out of the crowd: change the color on your light and the app spots which one changed. Once you have your lights, **Find My Light** shows a signal bar that fills as you get closer. |
| **Light shows** | Beat-timed dances: Beat Chase, Heartbeat, Build & Drop, Pop Song and Random Disco, with tap tempo and Half-Time. Change the built-in ones or make your own. |
| **Patterns** | Breathe, Crossfade, Sparkle, Sunrise and your own Playlist of colors. Change them or make your own. |
| **More than one group** | Have lights that aren't paired together? Control up to eight extra groups of your own lights along with your main one, all together or each with its own colors, and build Group Shows that move colors between them, in seconds or on the beat. |
| **Without opening the app** | Controls in the notification shade (pick your own buttons), a Quick Settings tile and a home screen widget (they work while the app is running in the background). Shows keep running with the screen off. There is also a brightness bar you can drag in the shade (Android 10 and up) and a brightness slider for your phone's device controls (Android 11 and up). |
| **Palette colors** | The lights only say "palette 12". The app knows what color each one is out of the box, and you can hide the palettes you don't use. |
| **Themes** | Classic, or Material You to match your wallpaper, plus an icon picker. |
| **Getting started** | A "Just Got Your Lights?" tour for first-time users (you can skip it), plus a guide in More > Help. |
| **Easter eggs** | There are a couple of surprises hidden for certain events. You'll know them when you see them. |
| **What's new** | A change log pops up once after each update and lives in More > About. |

## Install

1. On your Android phone, open the [**latest release**](https://github.com/EricGrain/RaveLights-App/releases/latest).
2. Download the **RaveLights APK** (the file ending in `.apk`) and open it.
3. If Android asks, allow your browser (or Files app) to **install unknown apps**. Android also warns about apps that don't come from the Play Store. That is expected here.
4. Open RaveLights, read the quick heads-up, and allow **Nearby devices** and **Location** when Android asks (Bluetooth scanning needs them. The app doesn't read your location).

Needs Android 8.0 or newer and a phone with Bluetooth Low Energy.

**A brand-new light has to be paired once before it listens.** Until then its radio is switched off, so the app can't talk to it. You can pair it with your phone (see below) or with another light. After that it works with the app on its own, also after restarts.

## Getting your lights connected

The full steps are in the app under **More > Help > Getting Started**. The short version:

1. Update your lights to the latest firmware if you can.
2. **Pair with your phone.** On the Lights tab tap **+ Add a Light**. Hold **−** and **+** on the light for 2 seconds until it pulses purple, keep it next to the phone and tap **Start**. Do the same for each light. They all end up in one group, so they follow each other too.
3. **Already paired your lights with each other?** Then there is nothing to do: they appear under **My Lights**. If they don't, tap **Use** next to one. Lots of lights around? Tap **Which Light Is Mine?** and change the color on yours.
4. **Can't see your lights?** Cycle through a few colors on the lights themselves. Lights can go quiet when nothing is changing, and a color change makes them speak up so the app can find them.

Pairing uses the lights' own pairing mode. A light that pairs with your phone joins your group and leaves the one it was in. If your phone has no group yet, the phone joins the light's group instead, so the light stays with any lights it was already paired with.

## How it works

RaveLights lights talk to each other with small Bluetooth messages. This app listens for those messages and sends the same kind, so your lights treat the phone like another light in their group.

- In normal use it doesn't connect to your lights, and it doesn't change their firmware.
- It can only do what the lights already know how to do: three modes, a set of palettes, and brightness.
- Because it doesn't touch the firmware, damage is unlikely, but that can't be promised.

## Good to know

- **Experimental.** It may not work with every light or firmware version, and a firmware update on your lights can change how it behaves.
- **Beat-timed shows will drift.** Bluetooth has a delay, so shows that follow a BPM are very likely to look a little out of time. Slower tempos work best, and the Lead and Half-Time settings help.
- **Smart Brightness can fight the app.** Newer light firmware can manage its own brightness to save battery, which can override what you set here. The app shows whether it's on and has a **Smart Brightness switch** on the Lights tab to turn it on or off. You can also switch it off on a light: hold + and − and move the brightness indicator away from the magnet position.
- **Foldable phones.** The app re-fits itself when you fold, unfold or rotate, and a running show keeps going. When your phone is half-folded (flex mode), the Lights screen splits at the fold: the lights on one half and the controls on the other, and scrolling the controls doesn't move the lights. On tablets and other wide screens, each side scrolls on its own too. The options are under More → Screen.
- **Lay the ropes out.** The ropes are stiff and springy like a real rope light. Drag them with one finger or several, even both ends of one rope at once. Where you drop a rope, it stays. Double-tap a rope to coil it again.
- **Changes may not land on every light at the same moment.** Range is limited and busy places can drop messages.
- **Flashing lights can trigger seizures** in people with photosensitive epilepsy. If you're not sure, stick to Solid or Calm, or a slow pattern like Breathe or Sunrise, and warn anyone nearby.
- **Developer options.** Testing tools (a packet recorder, raw packets, a hidden-mode lab) are hidden. Tap the version under **More > About** seven times to show them. Leave the risky ones alone unless you know what they do.

**Use it at your own risk. I'm not responsible for any problem, damage or loss that results from using this app, including to your lights, your phone, your event, or your dance moves.**

## Updates and privacy

The app can check this page for a newer version when it opens (at most once a day, and you can turn it off under **More > About**). It only downloads one small text file, `latest.json`. Nothing about you or your lights is sent. That's the only time the app uses the internet.

When an update is available, **Download** opens the new APK in your browser. Open the file to install it. Your settings are kept.

## Found a problem?

Tap **More > Report a Problem** in the app: it opens a new issue here with your phone and app details already filled in. Or [open an issue](https://github.com/EricGrain/RaveLights-App/issues) yourself. It helps a lot to include:

- your phone model and Android version
- the app version (**More > About**) and, if you know it, your lights' firmware version
- what you did, and what you expected to happen
- optionally, a recording: **More > Developer Options > Packet Recorder > Start Recording**, make the problem happen, then tap **Copy** (tap the version under More > About seven times to show Developer Options)

---

<div align="center">
Made by Eric Gray / Monkey. Not affiliated with the official RaveLights company.<br>
Thank you to the RaveLights team for the lights and for letting me build this, to Toxmo and Howl for the Project Chimera artwork,<br>
and to Chebitz and the VancouFur team for the Nightfall artwork. This app is not affiliated with Howloween or VancouFur.
</div>
