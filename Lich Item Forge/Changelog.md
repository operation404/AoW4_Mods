# Lich Item Forge

## Changelog

### 0.3

- New Infusions
  - Armor
    - **Torso 20% Magic Crit Chance** - 2 cost.
    - **Torso 10% Magic Crit Chance** - 1 cost.
    - **Torso 10% Melee Crit Chance** - 1 cost.
    - **Torso 20% Melee Crit Chance** - 2 cost.
    - **Torso 10% Ranged Crit Chance** - 1 cost.
    - **Torso 20% Ranged Crit Chance** - 2 cost.
    - **Torso Quill Hide** - 1 cost. Applies bleeding to melee attackers.
    - **Torso Charge Resistance** - 2 cost. Gives charge resistance, countered by heavy charge.
    - **Torso Obscured** - 4 cost. Gives 40% accuracy penalty to ranged attackers.
    - **Torso Phase** - 2 cost. Gives the Phase ability, full action leaves one point teleport.
    - **Head Ignore 1 Status Resistance** - 1 cost. Attacks ignore 1 status resistance.
    - **Head Ignore 2 Status Resistance** - 2 cost. Attacks ignore 2 status resistance.
    - **Head Ignore 3 Status Resistance** - 3 cost. Attacks ignore 3 status resistance.
    - **Head Demoralizing Vision** - 3 cost. Melee attacks have a chance at gaining Remorsed.
    - **Head Brave** - 1 cost. Lose 50% less morale.
    - **Head Control Loss Immunity** - 2 cost. Gain immunity to loss of control effects.
    - **Legs Fiery Wake** - 2 cost. Ignites flammable obstacles and grants immunity to Burning.
    - **Legs Freedom of Movement** - 2 cost. Grants immunity to Slowed and Immobilized.
    - **Legs Pass Through** - 2 cost. Grants the ability to move through obstacles.
  - Amulets & Misc Items
    - **Amulet HP +10** - 2 cost.
    - **Amulet Cloud in a Bottle** - 2 cost. Free action ability to push units back and apply wet.
  - Rings
    - **Opportunist** - 1 cost. Gives +30% damage to retaliation attacks.
    - **Lucky Ring** - 1 cost. Gives +5% crit chance.
    - **Natural Regeneration** - 3 cost. Gives Natural Regeneration, healing 10% hp per turn in combat and 10 hp per turn in the world map.
    - **Life Steal** - 3 cost. Gives life steal on attacks.
    - **Lightning Immunity** - 5 cost.
    - **Blight Immunity** - 5 cost.
    - **Fire Immunity** - 5 cost.
    - **Frost Immunity** - 5 cost.
    - **Spirit Immunity** - 5 cost.
    - **Morale Immunity** - 5 cost. Gives immunity to morale status effects.
- Fixes
  - Fix staves using a different Raise Dead ability than wands.
  - Fix Summon Spirit Hawk infusion cost, is now properly 2 cost.

### 0.2

- Fixes
  - Fixed broken tag links in filter for % damage infusions, now correctly prevents applying a 10% and 20% damage infusion to the same item.
  - Fixed ranged damage infusion cost, from 1 to the correct value of 2.

### 0.1

- Staff & Wand Item Abilities
  - **Spawn Hatchling Ability** - Once per battle restriction removed. Action cost set to single. Cooldown set to 4.
  - **Summon Spider Ability** - Once per battle restriction removed. Action cost set to single. Cooldown set to 4.
  - **Summon Spider Monarch** - Once per battle restriction removed. Cooldown set to 5.
  - **Cryptblade** - Cooldown increased to 3.
  - **Summon Spirit Hawk** - Infusion cost increased to 2. Once per battle restriction removed. Action cost set to single. Cooldown set to 4.
  - **Heal** - Once per battle restriction removed. Cooldown set to 2.
  - **Mass Heal** - Once per battle restriction removed. Cooldown set to 3.
  - **Raise Undead** - Once per battle restriction removed. Cooldown set to 3.
  - **Polymorph** - Once per battle restriction removed. Cooldown set to 3.
  - **Resurrection** - Once per battle restriction removed. Cooldown set to 4.
  - **Domination** - Once per battle restriction removed. Cooldown set to 4.
  - **Wand of Fire Breath** - Once per battle restriction removed. Cooldown set to 2.
    - *(This only affects the premade Wand of Fire Breath. The infusion variants already worked this way, this just changes the premade item to parity.)*
  - **Summon Rose Knight** - Once per battle restriction removed. Cooldown set to 5.
  - **Summon Umbral Demon** - Once per battle restriction removed. Cooldown set to 4.
    - *(Cooldown set to 4 instead of 5 because it can summon units between tier 2 and 4, unlike Rose Knight or Spider Monarch.)*
  - **Hysteria Storm** - Once per battle restriction removed. Cooldown set to 4.
    - *(Only affects the item forge infusion ability, the unit ability is unchanged.)*
- Dual Wield Weapons
  - **Pistol and Sword** - Fire Magelock ability range increased to 4.
    - *(Compared to the Sword and Crossbow weapons, the pistol has less range, a 1 turn cooldown, and less damage in exchange for 50% armor pen. I think this is a bit much, so the range was bumped to match the offhand crossbows.)*
- New Infusions
  - **Quickloader** - 1 cost. A new infusion for the Pistol and Sword and Breachgun and Axe weapons that reduces the cooldown of their firearm abilities by 1. This reduces the pistol cooldown to 0, removing it entirely.
  - **Cryptblade** - 5 cost. A new infusion for misc items that gives the Cryptblade's effect from the removed Shadow rite.
  - **Torso 10% Melee Damage** - 1 cost. Melee variant of the magic damage infusion.
  - **Torso 20% Melee Damage** - 2 cost. Melee variant of the magic damage infusion.
  - **Torso 10% Ranged Damage** - 1 cost. Ranged (missile) variant of the magic damage infusion.
  - **Torso 20% Ranged Damage** - 2 cost. Ranged (missile) variant of the magic damage infusion.
  - **Head 10% Magic Damage** - 2 cost. Magic damage increase for the head slot.
  - **Head 10% Melee Damage** - 2 cost. Melee damage increase for the head slot.
  - **Head 10% Ranged Damage** - 2 cost. Ranged (missile) damage increase for the head slot.
