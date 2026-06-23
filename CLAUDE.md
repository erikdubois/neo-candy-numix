# CLAUDE.md — neo-candy-numix

## Project overview

Standalone repo for the **neo-candy-numix** folder-icon theme — the same folder set as
`erikdubois/surfn-numix` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-numix/` — folders only. Packaged as `neo-candy-numix-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-numix/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
