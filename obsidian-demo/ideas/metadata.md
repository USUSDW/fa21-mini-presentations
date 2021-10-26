---
aliases: Metadata
tags: obsidian_demo, definition
---

# Metadata

Metadata can be added to the beginning of files for better organization and convenience.

At the time of presenting, the main supported metadata keys are `tags` and `aliases`. More advanced tags can be found in the [help vault for YAML front matter](obsidian://open?vault=Obsidian%20Help&file=Advanced%20topics%2FYAML%20front%20matter) (requires having opened the "Help" vault at least once).

---

## Adding Metadata

To add metadata to a file, create a metadata block at the beginning of the file. Open and close it with `---`, and put the metadata inside. For example:

```
---
aliases: Your Custom Alias, YCM
tags: tag_a, tab_b
---
```

---

## Aliases

Aliases make linking files easier, especially if you name all your files using `a-standard-format.md`. For example, [[obsidian-demo-index]] is aliased as `Obsidian Demo`, so when linking to it, Obsidian will auto complete the link and the link text.

Another example use case for this would be if you had a file called `artificial-intelligence`. You could alias it as `artificicial intelligence` if you don't want the dash, as `AI` if you want it to be an acronym, etc.

[[embedding-notes-and-files|Embedding Notes and Attachments]]

---

## Tags

Adding tags via the metadata is an easy way to keep files clean an organized. For more info, see the [[tags|tags page]].

---

For more info, see [the official documentation](obsidian://open?vault=Obsidian%20Help&file=Advanced%20topics%2FYAML%20front%20matter) (requires having opened the "Help" vault at least once)