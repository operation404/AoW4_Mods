# Lich Empire Tweaks

## Changelog

### 0.1

- Empire Skills
  - Astral
    - **Rite of Conjuration** - Fixed the broken logic as well as added Pale Tidebloom as a possible spawn.
      - *This rite's script was somewhat poorly implemented, as it randomly chose a single province in the player's capital city and attempted to spawn a magic material there with no check whether it succeeded or not. If the player had any provinces that couldn't support land-based magic materials, such as ocean provinces... in the ocean themed dlc update... then the script would fail and no material would spawn, the rite would go on cooldown and the player would have their imperium taken still.*
      - *The new version isn't 100% fool-proof but is significantly better. It first decides a random magic material, finds all provinces that are potentially valid spawns, and tries them all until one works. If none work, it will attempt this process 10 times in total before stopping, which should hopefully make it so that in practice this rite never wastes your imperium again.*
