# Runic Roots

The 54 races of Runic Races as Townstead Roots: every race's active
ability, passive strength and weakness as genes, with its height, wings, particles and signature
effects. Villagers and players can be any of them.

Requires Townstead 0.8 or newer (1.21.1 NeoForge or 1.20.1 Forge). One pack: drop `pack/` (or the
built zip) into a world's `datapacks/`. Townstead syncs its textures, models and translations to
players, so no resource pack is needed.

## Peoples

All races share Townstead's humanoid species. Each is a lineage of the people (ancestry) it is
born into:

| Ancestry | Lineages |
| --- | --- |
| Human (Townstead's own) | Primian, Celeron, Magi, Valen, Colossan, Auroran |
| Elf | High, Dark, Moon, Blood, Ice, Grove, Tide and Astral Elves |
| Dwarf | Deep, Forge, Frost, Iron, Sky, Runic, Mountain, Moss and Crystal Ones |
| Bestial | Arachnid, Avian, Canine, Feline, Kitsune, Serpen, Bovine, Saurian, Chelon |
| Fae | Changeling, Dryad, Sprite, Nymph, Faerie, Zephyr |
| Draconic | Fire, Ice, Terra and Volt Drakes, Sea Serpen, Wind Wyrm, Scaleheir, Wyvernkin |
| Revenant | Zombie, Skeleton, Wraith, Reaper, Nightborn, Returned, Wailer |
| Fiend | Demon |

Revenants are ageless and bear no children. The Draconic hatch from eggs in clutches of two.
Half-human children are named Half-Elf, Half-Dwarf, Half-Fae, Drakeblood or Beastblooded.

## With Classic Fantasy

Install alongside Townstead's Classic Fantasy pack in any order and the races adapt on their own:
Runic elves and dwarves become lineages of the Classic Elf and Dwarf ancestries (taking their
ears, beards and stature), the Demon becomes a Tiefling lineage, and Half-Elf and Half-Dwarf
become Classic's own. Where both packs have a race of the same name, Townstead tells them apart:
**Classic High Elf** and **Runic High Elf**.

With Skeleton Folk installed, the Skeleton joins the Skeletownies and wears their skeleton body.

## Fidelity

How each power came across is listed in [docs/FIDELITY.md](docs/FIDELITY.md).

To check that Townstead loads every document, from a Townstead checkout:

```text
gradlew :1.21.1-neoforge:runPackCheck -PpackCheck="<path>/runic-roots/pack" -PpackCheckNamespaces=runic_roots
```

## Art

Horns, crests and tails are Blockbench projects in `art/` (with skin overlays in `art/*/skin/`). Each `.bbmodel` embeds its textures: the first is the base, the second, when present, glows.
