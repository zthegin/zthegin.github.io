# Unofficial English translation editor for Gintama: Gintoki vs. Hijikata!? Kabukichou Gintama Dai Soudatsusen!!

Help translate this Nintendo DS game in your browser. Load your own legally obtained ROM, edit a line, then send it as a GitHub issue. You do not need to install anything or write code to contribute.

The playable game is built separately on your computer. This repository hosts the editor, not a game download.

I do not own Gintama, the original game or its characters, story, artwork, music, text or trademarks. All game rights belong to their respective holders. This is an unofficial fan and educational project, with no affiliation or endorsement from the rights holders.

This project translates this particular game. It is not a translation of the Gintama manga, anime or franchise as a whole.

This is unofficial fan translation.

## Choose what you want to do

- [I just want to play](#i-just-want-to-play)
- [I want to help translate (no code)](#i-want-to-help-translate)
- [I want to update the website](#i-want-to-update-the-website)

[Current progress](https://github.com/zthegin/Gintama---Gintoki-vs-Hijikata-game-english-translation#current-progress) · [Installation help](https://github.com/zthegin/Gintama---Gintoki-vs-Hijikata-game-english-translation/blob/main/docs/APPLY_PATCH.md) · [Review a suggestion](https://github.com/zthegin/Gintama---Gintoki-vs-Hijikata-game-english-translation/blob/main/docs/REVIEW_SUGGESTIONS.md)

Most users and translation contributors need no coding. **Suggest on GitHub is the easiest no-code contribution route.**

### I just want to play

1. Get the source from the [main project repository](https://github.com/zthegin/Gintama---Gintoki-vs-Hijikata-game-english-translation#i-just-want-to-play).
2. Follow its [short Python setup](https://github.com/zthegin/Gintama---Gintoki-vs-Hijikata-game-english-translation/blob/main/docs/APPLY_PATCH.md#install-python-on-windows), then copy the build commands in its README. Python 3.13 is recommended on Windows; 3.11 is also tested.
3. Give the command the path to your own legally obtained, matching ROM. The translated copy is created on your device; the original stays unchanged.

**Before you build:** this project supplies no ROMs, unauthorized download links or help finding unauthorized copies. If you are unsure whether you may use a ROM, stop and check first. A matching checksum confirms compatibility, not ownership or permission. Keep rebuilt ROMs and extracted game assets private; remove personal file paths from public bug reports.

Prefer Claude Code, Codex or another local coding assistant? The [source README has a copyable setup request](https://github.com/zthegin/Gintama---Gintoki-vs-Hijikata-game-english-translation#i-just-want-to-play). It must get your ROM path from you, keep the original unchanged and never download or upload game files.

### I want to help translate

**No coding is required.**

1. Open the [dialogue editor](https://zthegin.github.io/) and select your own legally obtained, matching ROM. It stays on your computer.
2. Choose a batch and a line, then write the English and any translator note.
3. Click **Suggest on GitHub**, review the suggestion and submit the issue. You need a GitHub account.

Accepted suggestions are credited to the GitHub account that submitted the issue. The translators page records accepted issues and merged PRs, with entry, revision, word and character counts and a link back to each contribution. The maintainer uses the [review and acceptance guide](https://github.com/zthegin/Gintama---Gintoki-vs-Hijikata-game-english-translation/blob/main/docs/REVIEW_SUGGESTIONS.md) to check the text against a local ROM and prepare it for review. Applying a suggestion does not publish it automatically.

No Python, Git, fork or file upload is needed for this route. For several lines or image labels, follow the [contribution guide](https://zthegin.github.io/guide.html). Download the tools from the source repository’s `main` branch; send batch PRs to `staging`. Two current account approvals mark valid translation edits for owner review. Reviews help prioritize work, but nothing merges automatically. Only the owner merges into `staging` or `main`.

### I want to update the website

The repository was recreated on 31 October 2026. If you cloned before that date, save your edits privately and make a fresh clone. Do not merge or push the old history.

Edit the website source in the project repository, rebuild it and copy the generated files here. Follow the [two-repository setup guide](https://github.com/zthegin/Gintama---Gintoki-vs-Hijikata-game-english-translation/blob/main/docs/TWO_REPOSITORIES.md). GitHub Pages uses **Deploy from a branch**, `main`, `/ (root)`. A separate CI audit checks public files, page notices, local links, module imports and batch assets without a ROM. It uses an audited source commit pinned by its full SHA. Keep the `.github` workflow when synchronizing generated files. Audit failures need maintainer attention; they do not automatically stop Pages.

## Background

This website supports an English fan translation of Banpresto’s 2006 Nintendo DS game, *Gintama: Gintoki vs. Hijikata!? Kabukichou Gintama Dai Soudatsusen!!* The game follows Gintoki and Hijikata through Kabukicho, drawing on Hideaki Sorachi’s manga and its anime adaptation. See the [game and anime background](https://github.com/zthegin/Gintama---Gintoki-vs-Hijikata-game-english-translation/blob/main/docs/ABOUT_THE_GAME.md).

The builder applies the bundled English text, graphics and UI labels on your computer. See [current progress](https://github.com/zthegin/Gintama---Gintoki-vs-Hijikata-game-english-translation#current-progress) for entry and batch counts. Much of the game is still Japanese, and the full game still needs playtesting.

The website handles field dialogue, [the opening script](https://zthegin.github.io/cutscenes.html), image labels and [battle dialogue](https://zthegin.github.io/battle.html). Loading your own ROM reveals supported untranslated opening and battle records. Send one line as an issue, or follow the editor guide to submit a checked English-only batch PR to `staging`. Use the local builder to check downloads with `--cutscene` or `--battle`. Other cutscene scripts remain unsupported. Japanese is decoded from your local ROM and is not included in exports or suggestions.

## Further docs

- [Installation and troubleshooting](https://github.com/zthegin/Gintama---Gintoki-vs-Hijikata-game-english-translation/blob/main/docs/APPLY_PATCH.md)
- [First contribution walkthrough](https://github.com/zthegin/Gintama---Gintoki-vs-Hijikata-game-english-translation/blob/main/docs/START_HERE.md)
- [Translators and contribution totals](https://github.com/zthegin/Gintama---Gintoki-vs-Hijikata-game-english-translation/blob/main/TRANSLATORS.md)
- [Project code, translations and discussions](https://github.com/zthegin/Gintama---Gintoki-vs-Hijikata-game-english-translation)

## Piracy and rights-holder requests

I do not support piracy and discourage it. Use only your own legally obtained ROM. Do not share game files or link to unauthorized downloads.

I take rights concerns seriously. If Bandai Namco, Hideaki Sorachi or another rights holder or authorized representative contacts me, I will promptly review the request and verify the sender's authority and the material concerned. For a verified request, I will remove or disable the affected material I control and stop the related work. If the concern covers the project as a whole, this may mean taking it offline. I will follow GitHub's takedown process and applicable legal requirements.

This covers material I control. I cannot guarantee removal of other people's forks, clones or cached copies. Fan or educational intent, owning a game copy and these notices do not establish translation permission or resolve any earlier rights issue. The repository includes English adaptations; those game-related rights are not granted by Apache 2.0. See [RIGHTS.md](RIGHTS.md).

## Rights and project limits

The playable ROM is built only on the user’s device from their own game file. GitHub builds the website and checks the tools without a ROM. No ROMs, resource packs, music or original font files are provided. The repository does include English adaptations of game text. These are subject to the underlying game rights; a code license does not establish permission to distribute them. Keep ROMs, extracted assets, saves and game captures on your own computer. The maintainer does not own the game or any original Gintama content.

[Apache 2.0](LICENSE) covers project code, original documentation and original lettering. It grants no game or franchise rights. See [RIGHTS.md](RIGHTS.md) for third-party terms and the contribution policy.
