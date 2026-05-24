# Floof Database

A self-contained, single-page Floof petal & mob reference plus a DPS calculator.

## Files

- **`index.html`** — the whole app, no server or build step needed. Open it locally or host it on any static web server (e.g. GitHub Pages).
- **`petals.json`** — every petal's stats and ability calls, the machine-readable source of truth.
- **`data.txt`** — the same info as a quick-to-skim aligned text table (index, name, cooldown, health, damage).

## Tabs

1. **Petal Stats** — every petal at every tier with the in-game icon and tooltip. Search, pick a rarity, hover for the full tooltip.
2. **Mob Stats** — every mob with stats scaled to each rarity. Unbalanced (no-drop) rarities are hidden.
3. **DPS Calculator** — equip 10 petals, pick a mob, run the 20-TPS sim. Petals orbit at 2.5 rad/s (boosted by any equipped *Faster*), mob hitbox edge sits 130 px from center, each tick of overlap counts as a hit on both sides.

## Credits

Credits: @Tiger200830, @Itzshovel
