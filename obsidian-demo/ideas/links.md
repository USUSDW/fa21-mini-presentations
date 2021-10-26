---
aliases: Links
tags: obsidian_demo
---

# Links

Links can be implemented two ways:
- The traditional markdown method: `[Link Text](http://url.com/)`
- Or the Obsidian method (*recommended*): `[[link-to-file]]`

---

## The Traditional Markdown Method

The markdown method for doing notes is fairly straight forward. Put the `link text` inside `[]` and follow it with the `url` in `()`. e.g. [This goes to Google](http://google.com/).

This method of linking is especially helpful if you're linking to external URLs.

---

## The Obsidian Method

To create an internal link, simply type `[[`. This will prompt you with the list of notes you can link to. Use `Up arrow` and `Down arrow` to navigate the suggestion list and `Enter` to select the current highlighted link.

### Changing the Link Text

If you, like me, prefer to have file names follow a standard like `this-is-a-file-name`, or just want to change the text of a link, simply follow it with the `|` character like so: `[[obsidian-demo-index|custom link text]]` which creates this: [[obsidian-demo-index|custom link text]]

### Linking to Headings

You can also link to specific headers in files. Start typing a link like you would normally. When the note you want is highlighted, press `#` instead of `Enter` and you'll see a list of headings in that file. Continue typing or navigate with arrow keys as before, press `#`again at each subheading you want to add, and `Enter` to complete the link.

For example, [[obsidian-demo-index#What We'll Be Covering|this link]] goes to the *What We'll Be Covering* header on the main file for this demo. 

### Linking to Specific Blocks

A "block" can be a paragraph, a blockquote, a list item, etc. In general, anything that has empty lines before and after is a block.

To link to a block in a specific file, first type `[[filename` to bring up a list of matched files. After selecting a file, type `^` and continue typing to search for blocks to link to.

Once you hit enter, a link to that block will be generated for you, in the format similar to `[[filename#^dcf64c]]`, where `dcf64c` is the block ID that was just generated for you.

For example, [[markdown-basics#^c8ed99|this link]] goes to the code block on the [[markdown-basics|Markdown Basics]] file.

---

For more info, see [the official documentation](obsidian://open?vault=Obsidian%20Help&file=How%20to%2FInternal%20link) (requires having opened the "Help" vault at least once)


---

[[links#|Hi Mom, I'm on Zoom]]