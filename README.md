# Melon Mix: Saltlord's Remix (Android)

A personal passion project to create my ultimate way to play the Kingdom Hearts DS games on Android. 👑❤️

358/2 Days is my favourite game in the KH franchise, and it’s always bothered me that there’s no easy, modern way to properly play it. So, despite not being an app developer, I decided to do something about it.

This melonMix fork uses AI heavily throughout development and is being built specifically around Android and touch: custom controls, display ratios and positioning, context-sensitive buttons, tailored overlay layouts and more.

358/2 Days is already working exactly how I envisioned it. Re:Coded is next.

I’ll release it publicly once it looks and feels like a proper app that anyone can pick up and use without fuss, and I intend to keep it updated alongside the main melonMix project.

I’m not an app developer. I’m just a crazy KH superfan who apparently decided a port of a port needed another port. 💀

Bug reports will absolutely be welcome when some of you inevitably try this thing, and I’ll do my best to squash them.

And a MASSIVE thank you to [Nireves333](https://github.com/Nireves333), the original developer behind the melonMix Android port. None of what I’m doing here would exist without the work they put into bringing melonMix to Android in the first place. This fork is built on top of their work, and I’m incredibly grateful to have it as the foundation for this ridiculous little passion project. 💗

---

# Original melonMix Android Port

The following is the original README from Nireves333's melonMix Android port, which this fork is built upon.

---

#KH Melon Mix on Android. 

I couldn't find an Android port of KH Melon Mix so I attempted to make one that runs on my Anbernic RG505. One
widescreen screen, camera on the right stick, HD cutscenes, remastered music. It's
[melonDS-android](https://github.com/rafaelvcaetano/melonDS-android) with the [KH Melon Mix](https://github.com/vitor251093/KHMelonMix) features ported into it.

| Game select | 358/2 Days | Re:coded |
|---|---|---|
| ![Game select](./.github/images/game_select.png) | ![358/2 Days](./.github/images/days_gameplay.png) | ![Re:coded](./.github/images/recoded_gameplay.png) |

I built and tested this on an RG505 and nothing else. You're welcome to run it on
other devices and to build on the code, but I can't promise anything beyond my own
setup. If something breaks, open a bug report in [Discussions](https://github.com/Nireves333/melonMix-android/discussions) here, not on KH Melon Mix or melonDS. I'll try to fix issues when I can :)

There's a ready-made APK on the
[releases page](https://github.com/Nireves333/melonMix-android/releases). Setup,
building from source, asset packs and known issues are all in
**[the guide](./GUIDE.md)**.

## Features

- The whole game on one widescreen screen. The HUD, minimap and command menu are
  moved onto it.
- Upscaled internal resolution. 3x holds (mostly) 60fps on the RG505 in normal non-overclocked mode.
- Camera on the right stick. Lock On and Switch Target get their own buttons, and
  the command menu goes on the d-pad.
- A "KH layout" button in the settings that applies all the recommended bindings
  at once.
- HD cutscene replacement with subtitles in six languages (Days only).
- Remastered music replacement with proper loop points (both games).
- The app itself is reworked for the two games: KH styled game select screen, menu
  sounds, and settings cut down to what these games actually need/use.

Not in it: texture replacement, HD cutscenes for Re:coded (upstream doesn't have
those yet either), Lua scripting.

Possible update: Touch controls, when I have time :)

## ROMs

This repo has no ROMs, no BIOS files and no game assets, and I won't link to any.
Dump your own games, and use the **US versions**: that's what the Melon Mix
enhancements are made for. EU and JP ROMs work with limited support and can
glitch (see the guide). Please don't ask.

## Credits

This project is a port of other people's work:

- [KH Melon Mix](https://github.com/vitor251093/KHMelonMix). All the enhancements
  come from them: vitor251093, justedni, Kite2810, sandwichwater, DaniKH1 and their
  community. If you're on PC, use their version.
- [melonDS-android](https://github.com/rafaelvcaetano/melonDS-android) by
  rafaelvcaetano, the app this is built on.
- [melonDS](https://github.com/melonDS-emu/melonDS), the emulator under everything.

## License

GPLv3, same as melonDS, melonDS-android and KH Melon Mix. See [LICENSE](./LICENSE).
The modified emulator core is public in the
[melonMix-android-lib](https://github.com/Nireves333/melonMix-android-lib) submodule.

<sub>This repository is co-authored by Anthropic's Claude.</sub>
