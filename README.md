# Melody Sketch

A melody sketchpad: one sine voice, custom pitches and grace notes, editable bends, rhythm controls, and WAV/MIDI export.

## Mac beta 0.8.0-beta.1

[Download the Mac installer](https://github.com/aakash-rajan/melody-sketch-releases/releases/download/v0.8.0-beta.1/Melody-Sketch-0.8.0-beta.1-macOS-universal-release.pkg) · [Release notes](https://github.com/aakash-rajan/melody-sketch-releases/releases/tag/v0.8.0-beta.1) · [Website and browser instrument](https://melodysketch.in/)

One universal installer includes AU, VST3 and standalone for Apple Silicon and Intel. It is signed by Aakash Rajan, notarized by Apple, and has a stapled ticket. The exact package passed automated installation, upgrade, AU/VST3 validation, Gatekeeper and standalone launch checks on both Mac architectures.

**Early beta: hands-on Logic Pro and Ableton Live verification is still pending.** macOS 11 is the build target; automated checks ran on macOS 15. Older versions remain unverified. Start in a new session or a copy of a project. The [first-run check](https://github.com/aakash-rajan/melody-sketch-releases/releases/download/v0.8.0-beta.1/DAW-First-Run-Check.txt) covers the remaining listening, transport, session and export tests.

Version 0.8 introduces a shared four-tab layout: Shape, Notes, Rhythm and Ideas. The browser and Mac editor now use consistent controls, clearer values, mixed note-name/cents entry, a simple Export menu, improved Undo and easier kept-idea management. The melody engine is unchanged: Phrase flow, varied main-scale openings, grace notes, bends, custom meter, swing and the root drone remain available. Native musical changes take effect at the next phrase boundary during playback; the browser auditions changes immediately.

The native release is Mac only. The browser instrument works without installation.

## Install

Close your DAW, open the downloaded .pkg and follow the standard macOS installer. Logic uses the AU on a software instrument track. Live uses the VST3 on a MIDI track (enable the VST3 system folder and rescan if needed). Leave DAW sync on and press DAW Play; if stopped in the plugin, press Play to arm it; no MIDI clip is required.

For standalone, open Melody Sketch in Applications, choose an audio output and press Play.

## Support

[Report a bug or ask a question](https://github.com/aakash-rajan/melody-sketch-releases/issues/new/choose). Include your version, system, browser or DAW, and steps to reproduce the problem. Reports are public; do not attach private projects or credentials.

MIDI receivers need a pitch-bend range of ±24 semitones. WAV preserves the exact sine melody, including bends and edits, while excluding the click, root drone, backing tracks and DAW effects. Scale notes are chosen manually; automatic audio-to-scale detection is not included.

Installer SHA-256: `8f57da723fa64a773ed7972fd8d0bc735789fa722a65df4aa6cbc9372e6af419`.

This repository contains public release information and support. GitHub's Source code archives are not the plugin installer and do not contain the private native source.
