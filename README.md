# Drazor's Homebrew

Homebrew content for Aurora and Borealis (D&D 5e, 2014 rules):

- **Way of the Soul Sword** — Monk tradition
- **Gromman** — race
- **Eldritch Beam** — Eldritch Invocation (by Rev)
- **Spells** — Wildshard's Macabre Projection, Dethrone (by Rev, listed under the "Rev's Homebrew" source)
- Magic weapons (all by Rev: Fang of the Dragon of Statues, Fatestealer, Klauth's Scalerender Glaive) and armor
- More items by Rev:
  - Dragon hoard items with Slumbering/Stirring/Wakened stages: Greatsword of the Black Doom, Klauth's Staff of Brimstone, Lost Secrets of Icingdeath, Venom's Gilded Jewels
  - Blooddrinker Axe; Sarialax, Bow of the Dranorri Rangers; Vampiric Draught
  - YET gear: Hexfire Pistol, Magelock Rifle, Silenced Sniper, Tactical Baton, Hex Grenade, Smokecharge Grenade

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
