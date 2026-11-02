# Legendary Armors (Fabric, Minecraft 26.3)

Two armor sets in one mod. Works on a server (vanilla clients can join) and in singleplayer/LAN.

- **Necromancer Lord** - SHIFT + JUMP summons 3 Wither Skeleton minions with the full set.
- **Shadow Assassin** + **Corrupted Pigman Sword** - buffs, teleport and kill tracking.

Get everything: `/function legendary_armors:give_all`
Necromancer only: `/function necromancer_lord:give_all`
Shadow Assassin only: `/function shadow_assassin:give_all`
All pieces are also craftable (recipes unlock automatically).

Build: upload to GitHub, run the "build" workflow, download artifact `legendary-armors-jar`.
Install: put the jar and Fabric API in `mods/`.

## Necromancer Lord: Second Life (full set)
- Wear all 4 pieces. When you would die, you cheat death: full health + Health Boost, Absorption,
  Resistance, Speed, Saturation, Regeneration, Jump Boost and Fire Resistance for 2 minutes.
- Then a 5 minute cooldown starts after the effects end. Chat/actionbar messages tell you when it fades and when it is ready.
- Like a totem, /kill and the void cannot be cheated.
- Each piece also gives a small passive boost while worn (Luck, knockback resistance, speed, jump).
- Cooldowns are saved in `config/legendary_armors/second_life.properties`.

This version contains Java code, so it must be built on GitHub (artifact `legendary-armors-jar`).
