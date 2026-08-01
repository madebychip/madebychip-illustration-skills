<p align="center">
  <img src="assets/banner.svg" alt="Illustration Skills — open-source prompt systems for generating consistent, on-brand illustrations with ChatGPT" width="100%">
</p>

<p align="center">
  <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg">
</p>

# Illustration Skills

A growing collection of **illustration skills** — ready-made instruction sets you paste into a ChatGPT Project to generate a consistent, on-brand family of illustrations, over and over, without opening a design tool.

**Guild Enamel** (metal-and-enamel achievement badges) is the first one. More are on the way.

**📺 Watch the walkthrough:** [youtu.be/J_Cum67TpNA](https://youtu.be/J_Cum67TpNA) — full setup, start to finish.

## What this is, in plain English

If you ask ChatGPT for an image, then ask again, you'll usually get two images that don't quite look like they belong together — different style, different colors, different quality. That's fine for a one-off, but useless if you need a whole *family* of on-brand images: a set of badges, a set of icons, a set of illustrations for a website.

An "illustration skill" fixes that. It's a small folder of text files that lock in the rules ChatGPT should always follow — material, color, composition — plus a few reference images to anchor the style. Set it up once, and every image you generate after that follows the same rules automatically. You just type a short sentence describing what you want.

No design software. No design background needed. Just a ChatGPT account (the free plan works) and about ten minutes of one-time setup per skill.

## Available skills

| Skill | What it makes | Setup guide |
|---|---|---|
| **Guild Enamel** | Metal-and-enamel achievement badges — achievement badges, distance milestones, streak chips, and limited editions | [guild-enamel/README.md](guild-enamel/README.md) |
| *More coming soon* | — | — |

## How every skill is put together

Every skill folder follows the same shape, so once you've set one up, you already know how to set up the next:

- **`SKILL.md`** — the brain. The construction rules ChatGPT always follows, plus the logic that decides what kind of image you're asking for.
- **`prompt-library.md`** — backup, fully-written-out prompt text for each format the skill supports.
- **`references/`** — a handful of finished example images that anchor the visual style.
- **`README.md`** — the plain-English setup guide for that specific skill.

## The general setup shape

The exact steps live in each skill's own README, but every skill follows the same pattern:

1. Create a ChatGPT Project.
2. Open `SKILL.md`, swap in your own brand colors, and paste the whole thing into the Project's Instructions.
3. Upload `prompt-library.md` and the images in `references/` to the Project's Sources tab.
4. Start a new chat inside the Project, describe what you want in a sentence, attach your own logo directly to the message, and send.

## Who this is for

Founders, marketers, indie developers, design teams — anyone who wants a consistent set of on-brand illustrations without hiring a designer or learning design software. If you can copy and paste, you can use this.

## License

The workflow, instructions, and prompt text in this repository are [MIT-licensed](LICENSE) — free to use, adapt, and republish.

Some example reference images are licensed separately — check each skill's `IP-NOTICE.md` before reusing images directly. The intent is for you to generate your own reference set for your own brand, not republish the examples.

## About

Made by [Chip](https://madebychip.com). Guild Enamel is the first of several illustration skills I'm planning to open-source — if this is useful, watch this repo to catch the next one.

If you build something with this, I'd love to see it — open an issue or [get in touch](https://madebychip.com).
