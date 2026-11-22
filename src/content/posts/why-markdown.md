---
title: why this is just markdown
description: a short note on why there's no database behind this site.
pubDate: 2026-11-12
tags:
  - notes
---

someone asked why i didn't just use a blog platform with an editor. honestly, because i write in a text editor anyway.

a post here is one `.md` file with a bit of frontmatter at the top. the file name is the url. there's no admin panel to log into and nothing to back up except the repo itself, which is already on github.

the annoying part is that publishing means opening a terminal. the nice part is that i can write offline, keep everything in git, and move the whole site to another host whenever i feel like it.

drafts work too. `draft: true` keeps a post out of the build but lets me look at it locally. that's enough for me.
