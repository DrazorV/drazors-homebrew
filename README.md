# Drazor's Homebrew

Homebrew content for Aurora and Borealis (D&D 5e, 2014 rules):

- **Way of the Soul Sword** — Monk tradition
- **Gromman** — race
- **Eldritch Beam** — Eldritch Invocation
- **Spells** — Wildshard's Macabre Projection, Dethrone (from Rev's Homebrew)
- Magic weapons and armor

## Install

**Aurora:** Additional Content → paste this index URL → Import:

```
https://raw.githubusercontent.com/DrazorV/drazors-homebrew/main/drazors-homebrew.index
```

**Borealis:** import the same index URL, or download this repo as a zip and import the zip.

## Layout

- `drazors-homebrew.index` — the index file Aurora/Borealis read
- `drazors-homebrew/` — the element XML files the index lists

When you change a file, bump its `<update version>` and the index's version so the apps pick up the update.
