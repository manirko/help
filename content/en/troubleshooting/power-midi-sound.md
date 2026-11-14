---
title: "Device plugged in, but no sound: check the signal path"
slug: power-midi-sound
section: troubleshooting
summary: "Check whether your computer sees the device, your app receives notes, and your software instrument makes sound."
order: 7
segment: ["music-producer", "gift-recipient"]
status: draft
last_edited: 2026-11-14
human_verified: false
emoji: 🔇
---

A lit LED does not prove that your app receives notes. Check each stage: your computer sees the device, your app receives notes, and your software instrument makes sound.

## Does my computer see the device?

Close other music apps and MIDI browser tabs. Plug the device in with a cable you know carries data. A charging-only cable will not work.

On a Mac, open **Audio MIDI Setup → Window → Show MIDI Studio**. On Windows, open **Device Manager** and look for the device. A system entry does not yet prove that notes reach your app.

If the device is missing, follow [Device will not connect](/troubleshooting/wont-connect/). Do not start with firmware recovery.

## Does my app receive notes?

Select your device as the MIDI input. In a browser, allow MIDI access if prompted. For a browser test, use desktop Brave or Chrome and the page named in your device guide.

Watch incoming notes or the MIDI indicator while you play. System or service messages alone do not prove that notes reach your instrument.

- If the device is listed but notes are missing, check the selected input and your device's playing instructions.
- If incoming notes appear, check the sound next.

For Playtron, check [Ground](/sound/grounding/). For another device, use its own guide: each device produces its signal differently.

## Notes arrive, but I still hear nothing

Load a software instrument on the MIDI track. MIDI itself is not sound.

In Ableton, enable **Track** for the device's input and select it in **MIDI From**. Use **Monitor: In**, or **Monitor: Auto** with **Arm** enabled. Check the track volume, instrument volume, and selected audio output.

Press a key on the on-screen instrument, if available. If that is silent too, check the app's audio settings first. If it plays but your device's incoming notes do not, check the track's MIDI input and channel.

For app-specific steps, see:

- [Ableton Live](/software/ableton/).
- [Logic and GarageBand](/software/logic-garageband/).
- [FL Studio and other DAWs](/software/fl-studio-and-other-daws/).

## Ask the community

> 🤝 **Other Playtronica users have probably hit this before.** The [Playtronica Friends Facebook group](https://www.facebook.com/groups/playtronica) has 4,400 members and is the fastest source of creative and technical help. Search the group's history first (use the magnifying glass at the top — try `playtron grounding`, `biotron calibration`, `touchme no sound`, or whatever fits your problem). If your question is not already answered, post a new one with a `[Device]` prefix in the title. See [the community page](/site/community/) for what to ask there, what to email instead, and where to find the WhatsApp regional groups.

## What should I email support?

[Email support@playtronica.com](mailto:support@playtronica.com) with the subject `No sound #[your order number]`.

Include your device model, operating system, and app. Attach screenshots of the MIDI device list and track settings. Tell us whether incoming notes appear and whether the on-screen instrument plays. These observations help us choose the next check.
