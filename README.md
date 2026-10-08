# Kaizo Ironmon (For Busy People):

Kaizo Ironmon (For Busy People) is a ROM patch for **Pokémon FireRed**. It's meant for Ironmon runs: it cuts out a lot of the early-game busywork and grinding but keeps the challenge.

**Please do not stream this patch, it is mainly meant for parents or busy people who enjoy Kaizo Ironmon but dont have time to stream or play the normal challenge.**

<img width="480" height="320" alt="title_preview_4x" src="https://github.com/user-attachments/assets/ad199a04-116e-4496-bde0-22ac60610a20" />


## Built on Faster-FireRed

This patch is built on top of **[Faster-FireRed](https://github.com/DrMaple/Faster-FireRed) by DrMaple**. Faster-FireRed is the base: all of its speed-ups and quality-of-life changes are included, and the changes below are added on top. Huge thanks to DrMaple. This project wouldn't exist without it.

You don't need to apply Faster-FireRed separately. The Kaizo Ironmon IPS already includes it, so you apply **one patch** to a clean FireRed (U) v1.1 ROM.

## Compatibility

Every change is made in place on the original game. No vanilla code or data moves, so these work **unmodified**:

- the stock **Ironmon Tracker**
- the stock **Universal Pokémon Randomizer ZX** (PokeRandoZX)

Randomize the patched ROM as usual. Features that depend on wild Pokémon (encounter cycling, area Poké Balls) read the encounter tables while you play, so they follow whatever the randomizer put there.

---

## Gameplay Changes

### Early game

- **Weaker first rival battle.** The rival's Pokémon in the Oak's Lab battle is Lv. 6 instead of Lv. 8.
- **+1 Master Ball.** When Professor Oak gives you the Pokédex, you get a Master Ball along with the usual 5 Poké Balls.
- **Oak's Lab PC boosts friendship.** The PC in Oak's Lab offers the same friendship boost as the old man in Viridian City, so you don't have to walk back for it.

### Wild encounters

- **Deterministic encounter cycling.** On **Route 1, Route 2, Route 22 and Viridian Forest**, grass encounters cycle through every species that lives in that area, in order, instead of rolling randomly. You'll see each species before any repeats. Levels are still random. The cycle starts over each time the game is powered on.
- **Area Poké Balls.** Once you have the Pokédex, a row of Poké Balls appears on **Route 1, Route 2, Route 22 and in Viridian Forest**, one for each species in that area's grass. Look in a ball to see what's inside and its level, then take **one per area**; the rest disappear.
  - The Pokémon is at the area's highest wild level. Viridian Forest is capped at Lv. 8.
  - If your party is full, it goes to the PC.
- **Catch rate ×1.15.** Every catch attempt is about 15% more likely to succeed.

### Field moves and HMs

- **HMs work without a Pokémon that knows them.** With the right badge and the HM in your bag, you can use **Cut, Surf, Strength, Rock Smash and Waterfall** even if nobody in your party knows the move. Badge requirements are unchanged, so you can't skip a gym.
- **Fly from the Town Map.** With the **Thunder Badge** and **HM02** in your bag, using the Town Map opens the Fly map. Fly still only works outdoors.
- **Cut trees removed.** Once you get HM01, the cut trees in Vermilion City (the one blocking the gym) and Celadon City are gone for good.
- **Rock Tunnel is lit.** Both floors are fully lit, so you don't need Flash.

### Healing

- **HEAL on the START menu.** A new **HEAL** option fully heals your party. It follows the same rules as Fly:
  - you need the **Thunder Badge** and **HM02** in your bag
  - you have to be outdoors (not in caves or buildings)
  - if a party Pokémon is poisoned, it needs at least 2 HP, so HEAL can't save a Pokémon that's about to faint from poison

  The option only shows up when you're allowed to use it.

### Items

- **Mt. Moon mushrooms always spawn.** The six recurring Tiny/Big Mushrooms on Mt. Moon B1F are always there from the start of a **new game** and stay collected once taken. Normally they only appear 40%/10% of the time.

---

## Cosmetic Changes

- **New title screen.** It reads "**Kaizo Ironmon**" with the subtitle "**For Busy People**", and Kangaskhan replaces Charizard. The "PRESS START" text moved slightly left to make room. The original copyright footer is unchanged.

---

## Credits

- **[iateyourpie](http://twitch.tv/iateyourpie)** for creating the Kaizo Ironmon challenge.
- **[Faster-FireRed](https://github.com/DrMaple/Faster-FireRed)** by DrMaple: the base patch this is built on.
