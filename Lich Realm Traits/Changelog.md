# Lich Realm Traits

## Changelog

### 0.3

- Realm Trait Changes:
  - The **Lich Volcanic Eruptions** realm trait was removed, and its changes were applied to the original trait.
  - **Arctic Blizzards**
    - Changed health recovery modifier from 0% to 50%.
      - Units with thematically relevant properties such as frozen immunity aren't affected.
    - Vision penalty increased from -1 to -2.
    - The combat effect property was changed from dealing 6 frost damage to all non-Frostling units to instead be a 60% chance for all units to gain a stack of Chilled.
  - **Hostile Oceans**
    - Changed health recovery modifier from 0% to 50%.
      - Units with thematically relevant properties such as aquatic movement aren't affected.
    - Removed the -6 hp drain.
    - Decreased the vision penalty from -3 to -2.
    - Now applies to all units instead of only player/ai empire controlled units.
  - **Volcanic Eruptions**
    - Changed health recovery modifier from 0% to 50%.
      - Units with thematically relevant properties such as burning immunity aren't affected.

### 0.2

- New Realm Trait:
  - **Lich Regenerating Infestations** - A variant of the base game trait which scales based on world threat level, number of players, and what stage the game is in.
    - The vanilla trait is very basic. Every 10 rounds it loops through every surface province, checking if it's valid for a land infestation, and then has a 3% chance of placing one. Only the wild beast nest, great bird nest, and large monster den are used.
    - This version has multiple differences:
      - Infestations are placed near player cities.
      - Infestations do not respawn on fixed rounds, and each player has their own respawn timer.
      - The amount and tier of the infestations scales with both the world difficulty and the game state of the player.
      - Infestations can be placed on water and underground sectors.
      - Every type of base game infestation is used.
    - There are still a few improvements that need to be done, and initial values may need adjusting.
      - A less robust but faster method of picking sectors is in consideration.
      - There is no system for skewing one type of infestation versus another within the same tier. In the future, I'd like realm inhabitant traits to be considered, and for lists to be weighted towards certain types of spawners.
- Other Changes:
  - Bandit Camp infestation can now spawn underground.

### 0.1

- General Realm Changes:
  - Max player count increased from 9 to 12.
  - Three new realm sizes added that increase in scale from the largest base game size.
- New Realm Traits:
  - **Lich Volcanic Eruptions** - A variant of the base game trait where the Volcanic Heat effect had its healing reduction effect changed from 100% to 50%, allowing units to still heal in Ashlands at a reduced rate.
  - **Lich Agnostic Magic Materials** - Removes the province type restrictions from magic material spawning logic, allowing any magic material to spawn on any kind of valid land province.
