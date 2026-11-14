---
title: "I downloaded firmware: is the update installed?"
slug: firmware-download-vs-installed
section: troubleshooting
summary: "A download, update mode, file copy, and installed version confirm different stages of a firmware update."
order: 9
segment: ["music-producer"]
status: draft
last_edited: 2026-11-14
human_verified: false
emoji: 💾
---

A firmware file in your Downloads folder does not mean your device has been updated. Follow the instructions for your device and check the result after plugging it in again.

## Which stage did I reach?

| What you see | What it confirms |
|---|---|
| A file appears in Downloads | The file is saved on your computer. Installation is not confirmed. |
| An `RPI-RP2` drive appears, where your device guide specifies it | The device is in bootloader mode. This is not confirmation of a newly installed version. |
| The file copy finishes | The transfer finished. Check the restart and result using your device guide. |
| The device appears as MIDI again | MIDI access has returned. This alone does not identify the installed version. |
| The expected version appears after reconnecting | If your Settings version supports reading firmware versions, compare this value with the expected version. |

If your app does not display a version, do not infer it from the filename. Save what you see and ask us how to check.

## What should I check before continuing?

Confirm that the instructions and file match your device model and board revision. A matching USB connector name is not enough.

Use a file from the update process confirmed for your device, or supplied by Playtronica support. A file for another model is not suitable.

If support has not identified the board yet, unplug USB and photograph both sides. Email the photos with your order number. Do not bridge contacts based on a similar photo online.

## The update drive did not appear

Record which instructions you followed and what your computer sees. Do not automatically erase memory or bridge contacts manually.

Read [Firmware recovery](/troubleshooting/firmware-reset/) and check whether its route matches your board. If that is unclear, stop and ask us.

## There is still no sound after the update

Check separately whether the system sees the device, notes arrive, and the app makes sound. Start with [the signal-path checks](/troubleshooting/power-midi-sound/). Silence alone does not prove that firmware is damaged.

## Ask the community

> 🤝 **Other Playtronica users have probably hit this before.** The [Playtronica Friends Facebook group](https://www.facebook.com/groups/playtronica) has 4,400 members and is the fastest source of creative and technical help. Search the group's history first (use the magnifying glass at the top — try `playtron grounding`, `biotron calibration`, `touchme no sound`, or whatever fits your problem). If your question is not already answered, post a new one with a `[Device]` prefix in the title. See [the community page](/site/community/) for what to ask there, what to email instead, and where to find the WhatsApp regional groups.

## What should I email support?

[Email support@playtronica.com](mailto:support@playtronica.com) with the subject `Firmware check #[your order number]`.

Include board photos, your computer's operating system, the instructions you followed, the filename, and the exact error. Tell us whether `RPI-RP2` appeared, whether copying finished, and what appeared after reconnecting. If a version is displayed, attach a screenshot.
