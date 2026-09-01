# Awesome Ultimate Hacking Keyboard

A curated list of awesome things related to the Ultimate Hacking Keyboard (UHK). ⌨️

The Ultimate Hacking Keyboard is a family of fully programmable, split mechanical keyboards made by Ultimate Gadget Laboratories.

The line includes the UHK 60 and UHK 80, add-on pointing modules, Agent (the configurator), and open firmware with a smart macro engine.

- [Awesome Ultimate Hacking Keyboard](#awesome-ultimate-hacking-keyboard)
  - [Official Resources](#official-resources)
  - [Products](#products)
  - [Software](#software)
  - [Firmware and Hardware](#firmware-and-hardware)
  - [Documentation](#documentation)
  - [Community](#community)
  - [Keymaps and Macros](#keymaps-and-macros)
  - [Tools](#tools)
  - [Tutorials](#tutorials)
  - [Reviews](#reviews)
  - [History](#history)

## Official Resources

- [Website](https://uhk.io)
- [Shop](https://uhk.io/shop)
- [Agent](https://uhk.io/agent) - Official configurator for Linux, macOS, and Windows.
  - [Agent web demo](https://ultimatehackingkeyboard.github.io/agent/) - Browser demo if you do not own a UHK yet.
  - [Agent releases](https://github.com/UltimateHackingKeyboard/agent/releases)
- [Knowledgebase](https://uhk.io/knowledgebase)
- [Blog](https://uhk.io/blog)
- [Forum](https://forum.uhk.io) - Official Discourse forum. The company prefers this over Discord.
- [GitHub: Ultimate Hacking Keyboard](https://github.com/UltimateHackingKeyboard)
- [Crowd Supply campaign](https://www.crowdsupply.com/ugl/ultimate-hacking-keyboard) - Original 2015 crowdfunding campaign and shipping history.

## Products

- [UHK 80](https://uhk.io/uhk80) - Wireless 80% tenkeyless split with OLED display, advanced thumb cluster, integrated palm rest, BLE, and USB dongle support.
  - [UHK 80 product page](https://uhk.io/product/uhk80)
- [UHK 60](https://uhk.io/uhk60) - Compact 60% split. Current retail model is the UHK 60 v2.
  - [UHK 60 v2 product page](https://uhk.io/product/uhk60v2)
- [Key cluster module](https://uhk.io/uhk80) - Left-side thumb module with extra keys and a mini trackball.
- [Trackball module](https://uhk.io/uhk80) - Right-side pointing module.
- [Trackpoint module](https://uhk.io/uhk80) - Right-side pointing module.
- [Touchpad module](https://uhk.io/uhk80) - Right-side pointing module.
- [Dongle](https://uhk.io/shop) - 2.4 GHz USB dongle for lower-latency wireless than BLE, especially for mouse movement.
- [Riser 80 manual](https://uhk.io/manuals/riser80) - Tenting stand for the UHK 80.

## Software

- [agent](https://github.com/UltimateHackingKeyboard/agent) - Official configurator. Keymaps, 12 layers per keymap, mouse keys, dual-role keys, one-shot keys, macros, and smart macro editing.
- [current-window-linux](https://github.com/UltimateHackingKeyboard/current-window-linux) - Official CLI that reports the current window on Linux, useful for host-aware macros.

## Firmware and Hardware

- [firmware](https://github.com/UltimateHackingKeyboard/firmware) - Official firmware for UHK 60 and UHK 80, including the smart macro engine.
  - [Firmware releases](https://github.com/UltimateHackingKeyboard/firmware/releases)
  - [Smart macro user guide](https://github.com/UltimateHackingKeyboard/firmware/blob/master/doc-dev/user-guide.md)
  - [Smart macro reference manual](https://github.com/UltimateHackingKeyboard/firmware/blob/master/doc-dev/reference-manual.md)
- [bootloader](https://github.com/UltimateHackingKeyboard/bootloader) - Official bootloader.
- [cad](https://github.com/UltimateHackingKeyboard/cad) - Mechanical CAD files.
- [datasheets](https://github.com/UltimateHackingKeyboard/datasheets) - Datasheets for ICs used in the keyboards and modules.
- [uhk60v2-electronics](https://github.com/UltimateHackingKeyboard/uhk60v2-electronics) - Schematics and PCBs for the UHK 60 v2.
- [uhk60v1-electronics](https://github.com/UltimateHackingKeyboard/uhk60v1-electronics) - Schematics and PCBs for the UHK 60 v1.
- [keycluster-electronics](https://github.com/UltimateHackingKeyboard/keycluster-electronics) - Electronics files for the key cluster module.
- [trackball-electronics](https://github.com/UltimateHackingKeyboard/trackball-electronics) - Electronics files for the trackball module.
- [trackpoint-electronics](https://github.com/UltimateHackingKeyboard/trackpoint-electronics) - Electronics files for the trackpoint module.
- [touchpad-electronics](https://github.com/UltimateHackingKeyboard/touchpad-electronics) - Electronics files for the touchpad module.
- [ugl-kicad-lib](https://github.com/UltimateHackingKeyboard/ugl-kicad-lib) - KiCad library from Ultimate Gadget Laboratories.
- [flasher](https://github.com/UltimateHackingKeyboard/flasher) - Scripts to flash bootloader and firmware images.
- [kareltucek/firmware](https://github.com/kareltucek/firmware) - Historical firmware fork that introduced the extended macro engine. Merged into official firmware; use stock firmware now.

## Documentation

- [Advanced UHK configuration](https://uhk.io/blog/2024/06/28/advanced-uhk-configuration) - Official write-up of smart macros, Agent editor features, and pointers to docs and the forum.
- [Agent 2: Next-level UHK and module configuration](https://uhk.io/blog/2022/11/18/agent-2-next-level-uhk-and-module-configuration) - Introduction of 12 layers, module acceleration, macro events, and smart macros.
- [Introducing the UHK 80](https://uhk.io/blog/2024/11/07/introducing-the-uhk-80) - Official announcement of the UHK 80.
- [Ultimate configurability](https://uhk.io/blog/2015/11/06/ultimate-configurability) - Early explanation of keymaps, layers, and actions.
- [Smart macros design notes](https://github.com/UltimateHackingKeyboard/firmware/issues/351) - Original design discussion for smart macros and macro events.

## Community

- [Forum](https://forum.uhk.io) - Official community. Look at the "My configuration" and "Configuration question" categories for keymap and macro examples.
- [UHK community Discord](https://nicd.gitlab.io/uhk-discord/) - Unofficial community Discord (also tunneled to IRC). Not affiliated with Ultimate Gadget Laboratories.
- [r/ErgoMechKeyboards](https://www.reddit.com/r/ErgoMechKeyboards) - Common place for UHK discussion among split and ergo boards.
- [@UltHackKeyboard on X](https://x.com/UltHackKeyboard)
- [YouTube: Ultimate Hacking Keyboard](https://www.youtube.com/@UltimateHackingKeyboard)
- [Mastodon](https://mastodon.social/@UltimateHackingKeyboard)
- [Bluesky](https://bsky.app/profile/uhk-keyboard.bsky.social)
- [Instagram](https://www.instagram.com/ultimatehackingkeyboard/)

## Keymaps and Macros

- [uhkm-spec](https://github.com/hastefuI/uhkm-spec) - Unofficial file format specification for Ultimate Hacking Keyboard Macros (UHKM)
- [uhk-macros](https://github.com/hastefuI/uhk-macros) - A collection of maintained and portable UHK macros in the UHKM format
- [TransitNow/uhk-agent-macro-gpt-prompt](https://github.com/TransitNow/uhk-agent-macro-gpt-prompt) - Daily-driver smart macros and a GPT prompt for writing Agent macros. Featured in the official advanced configuration post.
- [Setup: My keymaps in progress](https://forum.uhk.io/t/setup-my-keymaps-in-progress-qwerty-qwertz-based/234) - Detailed community keymap write-up covering Space-Mod, navigation layers, and secondary-role macros.

## Tools

- [uhk-learn-layout](https://github.com/mhantsch/uhk-learn-layout) - Generate an Agent macro that probes the host layout so the UHK can learn it.

## Tutorials

- [Advanced UHK configuration (video)](https://uhk.io/blog/2024/06/28/advanced-uhk-configuration) - Walkthrough of smart macros: dual-function keys, `$onInit` / `$onKeymapChange`, OS-specific keymaps, macro recording, mouse jiggler, gaming hold/tap, and one-shot modifiers.
- [Xah Lee UHK 80 review in depth](https://www.youtube.com/watch?v=qbq6rBjhILg) - Long-form hardware and Agent walkthrough from a long-time UHK user.

## Reviews

- [Xah Lee: Ultimate Hacking Keyboard 80](http://www.xahlee.info/kbd/Ultimate_Hacking_Keyboard_80.html) - Written review covering layout, Agent, modules, and a decade of UHK use.
- [Cheese Turbulence: The UHK80](https://www.cheeseturbulence.com/uhk80/) - Software-focused review that treats the board as a modular sandbox.
- [TechBroll: UHK 80 review](https://techbroll.com/2026/03/ultimate-hacking-keyboard-80-review.html) - Hardware and connectivity review from someone who also reviewed the original UHK.
  - [YouTube](https://www.youtube.com/watch?v=CzfEW6mcXy0)
- [CalmCode: UHK80 Review](https://www.youtube.com/watch?v=0y1jKq6RzjY) - Review focused on tenting, modules, mouse mode, and the standard staggered layout.
- [wabi sabi: UHK 80 Review](https://www.youtube.com/watch?v=FFmNoLdfqAQ) - Unboxing, specs, features, and sound test.
- [GBAtemp: UHK V2 hardware review](https://gbatemp.net/review/ultimate-hacking-keyboard-v2.2287/) - Review of the UHK 60 v2.

## History

- [Crowd Supply: Ultimate Hacking Keyboard](https://www.crowdsupply.com/ugl/ultimate-hacking-keyboard) - The campaign that launched the UHK 60.
- [firmware80](https://github.com/UltimateHackingKeyboard/firmware80) - Archived UHK 80 firmware fork. Merged back into official firmware after release.
- [agent80](https://github.com/UltimateHackingKeyboard/agent80) - Archived UHK 80 Agent fork. Merged back into official Agent after release.
