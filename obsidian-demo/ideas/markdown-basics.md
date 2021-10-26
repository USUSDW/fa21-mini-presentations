---
aliases: Markdown Basics, markdown basics
tags: obsidian_demo
---

# Markdown Basics

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

#not_a_heading, but a tag

This is just normal text.

This is *italics*, as is _this_.
This is **bold**, as is __this__.
Both ***bold and italic***, if you're a masochist

Highlighting ==text== can be done like so

> Blockquotes (see below)

Unordered Lists:
- Item 1
- Item 2
- So on
- and so forth
	- You can indent these too

Ordered Lists:
1. The first item
2. The second item
3. This is good for a step by step guide

You can do inline code with `back ticks`,
and code blocks with triple back ticks (see below).

Horizontal Rule (line that spans across the page):

---

Links will be covered in the next section.

```

> This is an example of a blockquote
> >You can nest them too

This is what ==highlighted text== looks like.

This is what an `inline code statement` looks like.

```javascript
// This is how you do code blocks

console.log('hello world');
```

^c8ed99

<pre>
```javascript
// This is how you do code blocks

console.log('hello world');
```
</pre>

## Task List

You can also make task lists like so:

```md
- [x] #tags, [links](), **formatting** supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [?] this is also a complete item (works with every character)
- [ ] this is an incomplete item
- [ ] tasks can be clicked in Preview to be checked off
```

- [x] #tags, [links](), **formatting** supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [?] this is also a complete item (works with every character)
- [ ] this is an incomplete item
- [ ] tasks can be clicked in Preview to be checked off