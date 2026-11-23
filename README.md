# Chiikawa Pocket Upgrade Planner

An unofficial, fan-made planner for Chiikawa Pocket. It ranks your upgrades (outfits, food, keychains, little house,
training, study, gacha and more) by how much damage each adds, using numbers from the game's data and checked against
in-game results.

**Open it:** https://radswouse.github.io/chiipock-planner/

- Works in any browser on iPhone, iPad, Android or a computer. Nothing to install and no account needed.
- Your data is saved in the browser you use. To move it to another device, use **Stats → Your data → Copy backup**,
  then **Restore backup** on the other device.
- **iPhone/iPad:** open the link in Safari, tap Share → **Add to Home Screen**. It then opens like an app, works
  offline, and Safari won't clear its saved data.

Not affiliated with the game or its makers.

## When a new outfit set comes out

The boss-fight model needs each new outfit's **hit time**: the seconds from its special starting to its damage (and any
buff or debuff) landing. Known hit times are in `HIT_S` in `index.html`; an outfit without one uses the average of that
character's other outfits until it's added. The easiest sources, best first:

1. The game's downloaded asset files from a phone that has the new set (the same kind of files as the OctoPreinstallation
   zips), which give exact times.
2. A screen recording of a boss fight with the new outfit in slot 1, recorded at 60 fps, from the moment the fight starts.
   The time from its special's animation starting to its damage number appearing is the hit time.

New outfits also need their skill numbers (multiplier, cooldown, effects) from the game's masterdata.

### Waiting on

- **Winter Holiday 2026 (out 12/1/26):** a screen recording of a boss fight with the new free Kurimanju outfit in slot 1
  for its hit time, plus the set's skill numbers and the new Holiday Tree home item.
