---
aliases: Obsidian Demo
tags: obsidian_demo
---

# Obsidian Demo
Presented by *Mark Snyder*

---

## Intro

- What is Obsidian?
- [Get Obsidian](https://obsidian.md/)
- Opening up Obsidian
- [The Help Vault](obsidian://open?vault=Obsidian%20Help&file=Start%20here)
- Navigating Obsidian


### What is Obsidian?

Obsidian is a note taking program not unlike:
- OneNote
- Notion
- Evernote
- Roam Research

Obsidian focuses on keeping notes in simple, local files. Notes are stored on your computer (though [cloud support](https://obsidian.md/sync) is a thing, as are git repos),  so your notes are yours and will always be. Notes are stored locally as markdown files, which means they will always be usable even if you move away from obsidian in the future.

It also has cool graphs!

---

## What We'll Be Covering

- [[markdown-basics|Markdown Basics]]
- [[links|Links]]
- [[embedding-notes-and-files|Embedding Notes and Attachments]]
- [[tags|Tags]]
- [[metadata|Metadata]]
- [[latex|LaTeX]]
- [[plugins|Plugins]]

There's even more that I didn't cover, but the Help Vault covers everything in depth.

---

## Tips & Tricks

**Tip**: If you don't remember how to do something, just press `Ctrl/Cmd + P` to open the "command palette" and type what you're looking for.

**Tip**: Settings can be changed by clicking on the cog in the bottom left, or with the `Ctrl/Cmd + ,` shortcut.

***Pro* Tip**: Obsidian settings are located in each vault (hidden under a folder called `.obsidian` in the root of vault folder), so to synchronize them between vaults you need to symlink the settings. I personally have an `obsidian-config` folder that all my vaults link to.

You need to link the following files:

- `plugins` (directory)
- `app.json`
- `appearance.json`
- `community-plugins.json`
- `core-plugins.json`
- `hotkeys.json`
