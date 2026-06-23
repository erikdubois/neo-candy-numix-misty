# CLAUDE.md — neo-candy-numix-misty

## Project overview

Standalone repo for the **neo-candy-numix-misty** folder-icon theme — the same folder set as
`erikdubois/surfn-numix-misty` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-numix-misty/` — folders only. Packaged as `neo-candy-numix-misty-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-numix-misty/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
