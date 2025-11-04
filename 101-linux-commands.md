---
title: 101 Linux Terminal Commands
topic: linux
blurb: |
  Everyday commands that save you from Googling “how to tar” for the hundredth time.
level: beginner → intermediate
popularity: 9/10
last_reviewed: 2025-11-04
---

# 101 Linux Terminal Commands

> Survival kit for the Debian family.

## Legend
$(cat meta/legend.md)

1. `ls -lh --color=auto`  
   ⭐ Long listing, human sizes, colourised.  
   Example: `ls -lh *.deb`

2. `find . -type f -size +100M`  
   📌 Locate fat files.  
   Common follow-up: `… -delete` (⚠️)

… (98 more)

---

## Mini glossary
- **stdin/stdout/stderr** – the three default streams …
- **pipe** – connects stdout of left cmd to stdin of right cmd …

## Further reading
- `man 7 hier` – filesystem layout
- [tldr-pages](https://tldr.sh) – community cheatsheets
