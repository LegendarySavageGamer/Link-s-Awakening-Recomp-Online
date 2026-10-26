# The Legend of Zelda: Link's Awakening — Recomp Online

### A fan-made online co-op project by ThyHeroOfTime

**Project status:** Beta / active development  
**Foundation:** [LAS Recomp by peiikai and contributors](https://github.com/peiikai/LASRecomp)  
**Focus:** Playing *Link's Awakening* together, not replacing the original single-player adventure

> **Important:** This is an unofficial community project. It is not affiliated with, sponsored by, or endorsed by Nintendo. Multiplayer features are still in development, and beta builds can contain bugs. Back up your saves before testing.

## ❤️ Why I made this project

I started **Link's Awakening Recomp Online** for a very personal reason: **I wanted to play The Legend of Zelda: Link's Awakening with my son and my kids.**

*The Legend of Zelda* has always represented adventure, discovery, puzzles, and memorable moments to me. But while exploring Koholint Island, I kept coming back to one thought: *Wouldn't it be amazing if I could share this whole journey with my children instead of experiencing it alone?*

I wanted to be able to stand beside my son in Mabe Village, head into the Mysterious Woods together, explore dungeons as a team, face enemies, find secrets, help each other through difficult parts of the story, and make memories as a family. Not just see another Link on the screen, but actually **play together**.

That's what inspired this project.

I am not making this because I want to replace what makes *Link's Awakening* special. I love the original game. My goal is to build something on top of that experience so families, friends, and longtime Zelda fans can share the adventure online.

What began as something I wanted to enjoy with my son has grown into a community project. Seeing players offer feedback, test builds, and get excited about the possibility of exploring Koholint Island together has given me even more motivation to keep going.

This project has involved a lot of experimentation, broken builds, debugging, and learning. Some things have worked beautifully; other parts have been much harder than I expected. I'm still committed to improving it and sharing the progress with everyone who wants to be part of the journey.

**At the heart of LA-Online is something simple: I want to be able to sit down, connect with my son and my kids, and enjoy this adventure together.** I hope that, one day, other families and friends can make their own memories with it too.

— **ThyHeroOfTime**

## 🎮 What is Link's Awakening Recomp Online?

**LA-Online Recomp** is an experimental, fan-made online multiplayer extension built around the native PC recompilation of the Nintendo Switch version of *The Legend of Zelda: Link's Awakening* (2019).

The long-term vision is a complete online cooperative adventure where connected players have their own Link, their own controls and personal resources, but can share appropriate parts of the world and story.

Development areas include:

- **Online sessions:** Hosting, joining, player identities, and connected-player status.
- **Remote Links:** Rendering other players with independent movement, facing, animations, and distinct appearances.
- **Multiplayer HUD:** Player usernames, their individual hearts, and location information.
- **Text chat:** Chat input, overhead speech bubbles, typing indicators, and a compact chat feed.
- **Navigation:** Teammate markers and a small multiplayer minimap.
- **Shared discoveries:** Cooperative item and rupee pickup handling, with each player's personal resources kept separate.
- **Story co-op:** Safe synchronization of supported quest progression, dungeon doors, puzzles, key items, and boss events.
- **Enemy and companion synchronization:** Shared encounters and companions such as BowWow where supported.
- **Beta testing tools:** Co-op settings, diagnostics, and bug-reporting workflows.

**Not everything above is finished or fully verified.** Some features have working interfaces or partial implementations while gameplay synchronization and cross-platform stability are still being tested. The release notes for each beta should say exactly which features are available in that build.

### The goal: two independent players, one shared adventure

Each person should control **only their own Link**. Other players' Links should reflect real network data—not copied local inputs or unrelated enemy AI. Shared progression must be applied safely, without blindly merging save flags or overwriting another player's personal save.

Original single-player gameplay should remain available independently of Co-op.

## 🧪 Beta status and known limitations

This is **an active-development beta**, not a promise of completely finished online story co-op.

Areas still requiring ongoing verification and refinement include:

- Remote Link visibility during room and scene transitions.
- Reliable health, item, reward, and companion replication.
- Safe reconciliation when players join with different story progression.
- Dungeon, overworld enemy, and boss synchronization.
- Chat and controller-input stability.
- Native PC, real Nintendo Switch, and compatible emulator interoperability.
- Correct operation of every exposed Co-op settings control.

**Please back up your save data before testing**, especially when you and a friend are at different points in the story. If a beta becomes stuck, avoid overwriting your only working save.

## 💻 Platforms and the original game

LA-Online development focuses on the **native PC recompilation**, while cross-platform online co-op with **real modded Nintendo Switch hardware** and compatible Switch emulators is part of the project's goal. A platform should only be considered supported by a particular beta when that specific combination has been tested and documented.

This repository does **not** provide a copy of *The Legend of Zelda: Link's Awakening*, Nintendo-owned game files, ROMs, decryption keys, or copyrighted game assets. You must supply your own legally obtained game files as required by the upstream recompilation and applicable law.

For upstream setup and requirements, visit [LAS Recomp](https://github.com/peiikai/LASRecomp). For LA-Online-specific installation and version compatibility, follow the instructions bundled with the particular beta release. Do not assume every upstream release or game revision is automatically compatible with every LA-Online build.

## 🐛 Bug reports and community feedback

If you encounter a problem, your reports genuinely help. Useful bug reports include:

1. The exact LA-Online beta/build and LAS Recomp version you used.
2. Whether you were the host or client, and which platforms were connected.
3. What area or dungeon you were in and what you were doing.
4. What happened, what you expected to happen, and how to reproduce it.
5. Relevant screenshots and logs, with private information removed.

If the in-game **Report A Bug** feature is available and functional in your build, you can use it. Otherwise, use the repository's GitHub Issues page or the support channel announced with the release. Please do not publicly upload private server credentials or unredacted save data.

## 🙏 Special thanks and credits

### Original recompilation — peiikai and the LAS Recomp contributors

A huge, heartfelt **thank you to [peiikai](https://github.com/peiikai)**, the creator and maintainer of **[LAS Recomp](https://github.com/peiikai/LASRecomp)**, and to everyone who has contributed to that project.

The native PC recompilation is the foundation that makes this particular LA-Online project possible. The work involved in recompilation, reverse engineering, tooling, rendering, platform support, fixes, and documentation is substantial. I want to recognize that work and make clear that **I did not create the original LAS Recomp project**.

Thank you for making the adventure accessible through a native PC application and for sharing your work with the community. Please also see the upstream project's own [README and credits](https://github.com/peiikai/LASRecomp#credits) for its full contributor acknowledgments.

### The original game and its creators

Thank you to the designers, artists, composers, programmers, and everyone responsible for creating *The Legend of Zelda: Link's Awakening* and its Nintendo Switch remake. The world of Koholint Island is why this fan project exists in the first place.

All original Zelda characters, names, designs, game content, and related trademarks remain the property of their respective rights holders.

### Our beta testers and community

A very special thank you to the players who have spent their own time testing online sessions, reporting bugs, sending screenshots, investigating broken story progression, and giving constructive ideas:

- **Velvet / Velvet_Charm** — thank you for your detailed feedback, gameplay testing, and suggestions for making multiplayer communication cleaner.
- **Sanic** — thank you for testing cooperative story progression and helping expose the kinds of issues that only show up when players are at different stages of the adventure.
- **Kit** — thank you for supporting the project and helping with community testing and feedback.
- **Raygar** — thank you for being part of the testing community and helping the project improve.
- **LunarFrankie** — a special thank you to my son, and one of the biggest reasons I wanted to make this project at all.
- **Every other beta tester and community member** who has played, submitted logs, reported bugs, suggested improvements, or simply encouraged the project along the way.

If I've missed your name, that doesn't mean your help went unnoticed. This is a growing community effort, and I appreciate everyone who has helped get it this far.

**The community isn't just testing this project—it is helping shape what it can become.**

## 📜 Licensing, attribution, and legal notice

- LA-Online Recomp is an **unofficial fan-made modification/extension**. It is **not affiliated with or endorsed by Nintendo**, the original game's developers, or the upstream LAS Recomp maintainers.
- **LAS Recomp's own original code is published under the MIT License**, with third-party components retaining their separate licenses. If this repository distributes or modifies upstream code, retain the applicable upstream copyright and license notices and any relevant third-party notices. See the [upstream license](https://github.com/peiikai/LASRecomp/blob/main/LICENSE) and documentation.
- Any LA-Online-specific licensing terms must be stated in this repository's actual `LICENSE` file; this README does not grant rights beyond the licenses that apply.
- This project does not grant rights to distribute Nintendo game files, assets, or other protected game material.

## 💙 A final message

I started this because I wanted to share one of my favorite kinds of adventures with my children. I never imagined how much time, troubleshooting, and community effort would go into something as simple-sounding as “let's play Link's Awakening together.”

To the original recompilation developer and contributors: **thank you for building the foundation.**

To Velvet, Sanic, Kit, Raygar, my son, and everyone who has helped test: **thank you for your patience, honesty, ideas, and support.**

And to everyone following the project: thank you for believing that an adventure through Koholint Island could be even more memorable when shared with someone else.

**Made with dedication, for family, friends, and the Zelda community.**

**— ThyHeroOfTime**
