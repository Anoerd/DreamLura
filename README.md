<p align="center">
  <img src="https://dreamlyra.com/brand/og/dreamlyra-en.png" alt="DreamLyra: let your MIDI play inside the game" width="820">
</p>

# DreamLyra

**Auto piano player for in-game instruments on Windows.** DreamLyra reads a MIDI file, or your MIDI keyboard, and presses the game's instrument keys for you. Full songs play in Heartopia, Roblox piano games, Genshin Impact and more. No AutoHotkey, no scripts to write.

**[Download for Windows](https://dreamlyra.com/?lang=en)** · [Website](https://dreamlyra.com/?lang=en) · [9-minute beginner's guide](https://www.youtube.com/watch?v=2nxCl4pKbws) · [Discord](https://discord.gg/CTWuUgBDRy)

> DreamLyra is commercial, closed-source software with a 3-day free trial. This repository hosts the installers and this page. The source code is not published here.

## What it does

- **Plays MIDI files for you.** Open any `.mid` file and DreamLyra performs it on the in-game instrument.
- **6,800+ ready-to-play songs.** The built-in store has 2,500+ English, 2,400+ Chinese, 950+ Japanese and 370+ Korean songs across pop, anime and game music. You don't have to hunt for sheets or MIDI files. A few songs are free; the rest are bought with credits.
- **Plays live from a MIDI keyboard.** Connect a MIDI controller and your character plays what you play. You can record the performance as a MIDI file.
- **Key layouts for 6 games are built in.** You can change any key and save your own profile.
- **Finds a key that fits the instrument.** The Key button rates every transposition for the current layout, and Auto picks the best one.
- **Playback controls.** Speed, semitone transpose, start delay, and global hotkeys. Press F8 in the game to pause or resume.
- **Library.** Search, favorites and playlists.
- **Interface languages.** English, 繁體中文, 简体中文, 日本語.

<p align="center">
  <img src="https://dreamlyra.com/ui/en/store.webp" alt="The DreamLyra song store, showing English, Chinese, Japanese and Korean songs" width="820">
</p>

## Supported games

| Game | Built-in layout | Guide |
|---|---|---|
| Heartopia | 22-key piano with semitones, and 15-key instruments | [Heartopia auto piano](https://dreamlyra.com/games/heartopia?lang=en) |
| Roblox piano games | 88-key layout, Shift for black keys | [Roblox auto piano](https://dreamlyra.com/games/roblox?lang=en) |
| Genshin Impact | 21-key Windsong Lyre and Floral Zither | [Genshin auto lyre](https://dreamlyra.com/games/genshin-impact?lang=en) |
| Neverness to Everness | 36-key piano and 36-key guitar | [All key layouts](https://dreamlyra.com/docs/keymaps?lang=en) |
| Where Winds Meet | 36-key | [All key layouts](https://dreamlyra.com/docs/keymaps?lang=en) |
| Identity V | 21-key with semitones | [All key layouts](https://dreamlyra.com/docs/keymaps?lang=en) |

Playing a different game? If its instrument is played from the PC keyboard, you can build your own layout in KEY SETUP.

## Quick start

1. [Download the installer](https://dreamlyra.com/?lang=en) and run it. When DreamLyra opens, Windows shows a User Account Control prompt. Click Yes.
2. Open the instrument in your game and press a few keys by hand to check that it makes sound.
3. In DreamLyra, choose your game from the KEY MAPPING PROFILE list.
4. Find a song in the built-in store, or click SELECT MIDI FILE to open a MIDI file you already have.
5. Set START DELAY to 3 or 5 seconds, press play, and switch back to the game before the countdown ends.

The full walkthrough is in the [quick start guide](https://dreamlyra.com/docs/quickstart?lang=en). To play live, see [Connect a MIDI keyboard](https://dreamlyra.com/docs/midi?lang=en).

## Price

- **Free trial:** 3 days, no credit card.
- **Lifetime license:** a one-time purchase on [Gumroad](https://anoerdia.gumroad.com/l/qcgnse). The license is bound to the device you activate.
- **Songs:** bought separately with credits. Some are free.

Refunds are handled by Gumroad. Details are in the [terms of use](https://dreamlyra.com/terms?lang=en).

## How it works

- DreamLyra sends ordinary keyboard input to the window in front, using the standard Windows `SendInput` API. These are the same keys you would press by hand.
- It does not inject code into the game, read or write game memory, or change game files.
- It runs as administrator so it can send keystrokes to the game.
- Games, platforms and communities may have their own rules about tools like this. Check those rules and decide for yourself before you use DreamLyra there.

## Before you install

- **The installer is not code-signed yet.** Windows SmartScreen may show "Windows protected your PC". Click More info, then Run anyway. If Smart App Control is turned on in Windows 11, it blocks unsigned apps and has no per-app exception; [contact support](https://dreamlyra.com/support?lang=en) if that happens.
- **You can check your download.** Every file on the [Releases](https://github.com/Anoerd/DreamLura/releases) page shows its SHA-256 digest.
- **What the app sends.** The [privacy policy](https://dreamlyra.com/privacy?lang=en) lists the data used for the trial, licensing and the store.

## Requirements

- Windows 10 or Windows 11, 64-bit
- A game whose instrument is played from the PC keyboard
- Optional: a MIDI keyboard or controller for live play

DreamLyra does not run on phones, Mac or consoles.

## Help

- [FAQ](https://dreamlyra.com/docs/faq?lang=en) covers the trial, licenses, device binding and store credits.
- [Discord](https://discord.gg/CTWuUgBDRy) is best for tutorials, song sharing and general questions.
- Email dreamlyra.music@gmail.com for license, purchase and account questions. Please do not post a full license key in public.
- [Release notes](https://dreamlyra.com/changelog?lang=en)
