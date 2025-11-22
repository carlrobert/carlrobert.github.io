---
layout: default
nav_order: 3
share: "true"
title: Obsidian tidbits
updated: 2025-11-22 17:56
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

This page describes how I currently use [Obsidian](https://obsidian.md). Hope you find this useful 🐱 The page is published using the excellent [Enveloppe plugin](https://enveloppe.github.io/) for Obsidian.
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
##### TODO: Merge the above with this detailed description
Setting up notes to combine markdown with Excalidraw makes sure you always have a scratch pad for diagrams and visual 🧠-storming. Configure Excalidraw in Obsidian as follows:
1. Saving > Filename > .excalidraw.md or .md: set to off
2. Embedding Excalidraw > Auto-export Settings > Auto-export SVG: set to on
3. Basic > Excalidraw template file or folder: “templates”
4. Use the ‘excalidraw-open-md:’ property to tell Obsidian how to open notes with integrated Excalidraw
5. Miscellaneous features > Fade out Excalidraw markup. This helps avoid visual clutter at the bottom of each note file

* You can convert an existing (textual) note to incorporate Excalidraw. Use the “Convert markdown note to Excalidraw Drawing” command
* Use the Excalidraw option to keep the svg export name in synch with the main file
* You can see both sides by putting them side by side – use stacked tabs
## Four note types

![Images/obsidian-tidbits-four-note-types.png](./Images/obsidian-tidbits-four-note-types.png)

## In a nutshell
![Images/obsidian-tidbits-funnel-practice-1.png](./Images/obsidian-tidbits-funnel-practice-1.png)
Todo: elaborate

## What’s in a note?
* Name – you can change it and links will update automatically
* Frontmatter = metadata, including aliases for more 
names/variants
* Textual content – markdown, rendered live
* Image content – Excalidraw, rendered as SVG
* Inline links to other notes

Backlinks and the local graph are automatically generated for you. They are a great way of discovering connections.
## You can navigate your notes in many ways
* Find or create a note option (ctrl-O)
* Good ol' find (ctrl-F)
* Via outgoing links from a note
* Linked mentions – at the bottom of each note
* Unlinked mentions
* Via the Files explorer – I use this mostly for organizing

On a related topic, there are good plugins for spaced repetition
## KISS: 😽


| Less …                     | is more                                    |
| -------------------------- | ------------------------------------------ |
| folders                    | 🔗 links                                   |
| vaults, docs, notebooks    | 🔗 links, again 😆                         |
| organizing ahead of time   | 🎨 emergent themes via links 😊            |
| word count per ‘note’ note | 🤔 reusability – linking trains of thought |
| cloud                      | ⏳ future proofing                          |

## Vault gardening – ways of learning and (re)discovering
* Find orphaned files and broken links plugin
* Improved random note plugin – re-visit stuff you might have forgotten
* Use the local graph with neighbour links enabled (Filters)
* Good ol’ search is always available
* Try the Global graph view – your mileage may vary

## Single-page presentations using Excalidraw
To do.

For details, see Zsolt Viczian’s [A detailed walkthrough of the Excalidraw-Obsidian Slideshow 3.0 script - YouTube](https://www.youtube.com/watch?v=JwgtCrIVeEU)
## My favourite community plugins for Obsidian
* Auto Link Title
* Calendar
* Completr – word completion
* Emoji toolbar 🦄
* Excalidraw 
* Find orphaned files and broken links
* Front matter time stamps
* Improved random note
* Paste image rename
* Smart typography
* Unicode search ☂️ꭅ
* Virtual linker / glossary

These add small, nifty features. Excalidraw is the big exception
## Learn more
* Morganeua: Make Your Notes Last A Practical Guide for Students. https://youtu.be/eId19ggnE4E
	* Applies to projects as well as university courses
* Same: Take RANDOMIZED zettelkasten notes with me! https://youtu.be/bmolnULA3KY
	* Vault gardening in a fun way, embracing serendipity
* Elizabeth Filips: You’re Not Stupid: How to Easily Learn Difficult Things.
https://youtu.be/Kz_brQBl8xk
* Justin Sung: Building a Perfect Learning System for a Professional in 45 
Minutes. https://youtu.be/D95rCKo8vac
* Ahrens: How to take smart notes book – for some backstory

