# Changelog

## 2026.06.23 — neo-candy colour split

**Install docs:** the README install section now lists the meta packages (top-level `*-icons-meta`, plus the group meta where applicable) alongside the per-variant `*-icons-git` package — replacing the outdated single `pacman -S` line.

### What Changed

Initial standalone repo. The **neo-candy-numix-misty** folder icons mirror `erikdubois/surfn-numix-misty` but fall
back to **neo-candy-icons** instead of Surfn. Packaged as `neo-candy-numix-misty-icons-git`, depending on `neo-candy-icons-git`.

### Files Modified

- Initial scaffold + usr/share/icons/neo-candy-numix-misty/
