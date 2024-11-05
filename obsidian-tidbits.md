---
share: "true"
updated: 2024-11-05 19:50
title: Obsidian tidbits
nav_order: 3
layout: default
---
# Obsidian tidbits
{: .no_toc }

<details open markdown="block">
  <summary>
    Contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

This page describes how I currently use [Obsidian](https://obsidian.md). Hope you find this useful 🐱 The page is published using the excellent [Enveloppe plugin](https://enveloppe.github.io/).
## Add word variants as alias properties
You can use the note’s `alias` property to add singular or plural forms of note titles. For example,
![400](./Images/obsidian-tidbits-use-aliases-for-plurals.png)
## Two-sided notes with Excalidraw
To do.
I find this especially useful for source notes.
Setup checklist:
- Saving > Files: use .md for Excalidraw
- Add these properties to your note template: todo
- Add a shortcut to be able to switch between the two sides of the page
- Auto-export settings: Keep filenames in sync. Enable autoexport.
- Misc: Fade out Excalidraw markup

To create the drawing page for a note, use the Convert markdown to Excalidraw drawing. This will add these two properties to your note:
```yaml
excalidraw-plugin: parsed
excalidraw-open-md: true
```

You can transclude the svg version of the Excalidraw page as usual:
```markdown
![[pagename.svg]]
```

See Nicole van der Hoeven’s lovely video: [Visual note templates with Obsidian Excalidraw - YouTube](https://youtu.be/zmgqMZi6QL8)

The only disadvantage I’ve found is the extra svg files in the vault.
## Single-page presentations using Excalidraw
To do.

For details, see Zsolt Viczian’s [A detailed walkthrough of the Excalidraw-Obsidian Slideshow 3.0 script - YouTube](https://www.youtube.com/watch?v=JwgtCrIVeEU)
