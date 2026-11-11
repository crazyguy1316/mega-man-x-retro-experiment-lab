# Mega Man X Retro Experiment Lab

## Development of both the game and its codebase will be on hold for a while. This does NOT mean the project is being abandoned or discontinued. Due to some development challenges, I've decided to move the entire project to Godot 4 and rewrite it from scratch earlier than originally planned.

## Project Overview

### Short Description
> **Disclaimer:** Mega Man, Mega Man X, and all related character sprites, artwork, music, sound effects, and associated intellectual properties used from the original games are owned by Capcom Co., Ltd. This is a non-commercial fan game project created for entertainment, learning, and experimentation purposes. No copyright infringement is intended.

This project is a Mega Man X fan game inspired by the SNES version of Mega Man X. The current goal is to recreate the classic gameplay experience while expanding it with additional playable characters from across Capcom franchises, including Mega Man himself, allowing players to experience Mega Man X stages from new perspectives.

As the project is still far from its final vision, content will be released incrementally. Major additions such as new playable characters, stages, and bosses will be delivered through individual updates rather than waiting for a complete release. This approach allows players to experience new content earlier, provide feedback, and helps the project evolve through ongoing balancing and refinement.

If you're interested in the project and use a Windows PC, feel free to download and try the latest available build.


[Download link] (update at 260818)
[https://drive.google.com/file/d/1VrNiATqRXDuZGkWyjtbizCxVKH1GbkUE/view?usp=sharing]

### Current feature and fix (update at 261107)
- add Flame Mammoth and other features


Video Demo and SNS link
- Youtube: [https://www.youtube.com/@CrimsonCrazyGuy]
- Reddit: [https://www.reddit.com/user/CrimsonCrazyGuy/submitted/]
- X/Twitter: [https://x.com/CrimsonCrazyGuy]

### Gameplay Screenshots
![zero_gif](images/zero/20260625_zero_show_case_gif.gif)

![mm_gif](images/megaman/20260625_megaman_show_case_gif.gif)

![protoman_gif](images/protoman/20260625_protoman_show_case_gif.gif)

![bass_gif](images/bass/20260625_bass_show_case_gif.gif)

![Screenshot 1](images/screenshot/screenshot-01.png)

![Screenshot 2](images/screenshot/screenshot-02.png)

![Screenshot 3](images/screenshot/screenshot-03.jpg)

![Screenshot 4](images/screenshot/screenshot-04.png)

![Screenshot 5](images/screenshot/screenshot-05.png)

![Screenshot 6](images/screenshot/screenshot-06.png)

Since the key configuration page is not finished yet, please use the keyboard mapping below for AutoHotKey or play directly with the keyboard:

### Control buttons:
- Dash -> Z
- Jump -> X
- Attack1 -> C
- Attack2 -> V
- Weapon change Left -> A
- Weapon change Right -> D
- Special action1 -> S
- Special action2 -> F
- Up / Down / Left / Right -> Arrow keys

### System

Some mechanics have been intentionally adjusted from the original games. For example, bosses can still take reduced damage during invincibility frames, and some attack like Zero Saber can produce normal damage to Boss in i-frame. Besides, attacks build up impact value that can eventually cause stagger or guard break. And some enemy projectiles or objects which cannot be destroied in original game are breakable with certain attack.

## Playable Characters

### Mega Man X
![Mega Man X](images/megamanx/mmx.png)

![LV2 charge](images/megamanx/x_b_c_lv2.png)
![LV3 charge](images/megamanx/x_b_c_lv3.png)
![Shotgun Ice](images/megamanx/shotgunIce.gif)
![Shotgun Ice charge](images/megamanx/shotgunIceCharge.gif)
![Shotgun Ice charge use](images/megamanx/shotgun_ice_charge_vs_spark_mandrill.gif)
![Homing Torpedo](images/megamanx/homing_torpedo_1.png)
![Homing Torpedo Charge](images/megamanx/homing_torpedo_charge_1.png)
![Chameleon Sting](images/megamanx/chameleon_sting_1.png)
![Chameleon Sting Charge](images/megamanx/chameleon_sting_charge_1.png)
![Rolling Shield](images/megamanx/rolling_shield_2.png)
![Rolling Shield Charge](images/megamanx/rolling_shield_charge_2.png)
![Fire Wave](images/megamanx/fire_wave_1.png)
![Fire Wave Charge](images/megamanx/fire_wave_charge_1.png)
![Storm Tornado](images/megamanx/storm_tornado_1.png)
![Storm Tornado Charge](images/megamanx/storm_tornado_charge_1.png)
![Electric Spark](images/megamanx/electric_spark_1.png)
![Electric Spark Charge 1](images/megamanx/electric_spark_charge_1.png)
![Electric Spark Charge 2](images/megamanx/electric_spark_charge_2.png)
![Boomerang Cutter](images/megamanx/boomerang_cutter_1.png)
![Boomerang Cutter Charge](images/megamanx/boomerang_cutter_charge_1.png)

![Hadouken](images/megamanx/mmx_hadouken.png)

Mega Man X, the main character of the Mega Man X series, is currently built with Mega Man X8 as the temporary development base, so his abilities are a little stronger for now. Once the armor set is finished, some of his functions will be adjusted to be closer to Mega Man X1.

He is intended to be the main playable character and the baseline for game difficulty, so in theory playing as X should provide the lowest difficulty experience.

#### Abilities:

- Dash / Air Dash: A movement action similar to the original games. The Air Dash may later have situational restrictions depending on the final design.
- Wall Kick: A signature move exclusive to X-series characters. This should not need much explanation.
- Level 3 X-Buster Charge Shot: Based on the third charge level from Mega Man X8. Compared to Level 2, it has higher impact value and damage. In the future this may be limited, and once the armor is completed it will at least be replaced by the Spiral Crush Shot.
- Armor: Work in progress. This is a huge amount of work, so please be patient. There is a first armor prototype test with Spiral Crush Buster Currently.

Here is the Armor list in plan:
- First Armor
- Giga Armor
- Max Armor (include golden)
- Fourth Armor (and Ultimate Armor)
- Falcon Armor
- Gaia Armor
- Blade Armor
- Shadow Armor

#### Special weapons:
- Shotgun Ice: Design as GameBoy xtreme version, normal shot still can reflect by wall, but charge version also can reflect by wall and cause large damage
- Electric Spark: WIP, next version of Godot 4 will have new feature on normal shot
- Rolling Shield: A tribute to the original weapon, with several enhancements. It features a higher Impact Value, allowing it to partially break through enemy defenses, along with powerful projectile-canceling capabilities that make it an effective defensive weapon. While the charged shield is active, you can switch to other weapons without losing its protection.
- Homing Torpedo: Its mechanics remain largely faithful to the original. However, thanks to system modifications, it can continue dealing damage to bosses even during their invincibility frames (i-frames). Even against bosses that aren't weak to this weapon, the charged version's five-projectile spread can still deliver respectable damage.
- Boomerang Cutter: The standard shot stays as close to the original as possible. However, the charged version features a redesigned trajectory and benefits from system modifications, giving it considerable offensive power at mid-range against both regular enemies and bosses.
- Chameleon Sting: Like Rolling Shield, this weapon will remain largely faithful to the original, with only minor adjustments. However, the ability to switch weapons during the charged version's invincibility period should make it considerably more effective than in the original SNES version.
- Storm Tornado: The standard shot remains similar to the original, dealing high multi-hit damage to enemies directly ahead. However, the charged version has been redesigned into a larger and more powerful tornado, capable of inflicting devastating damage on nearby enemies.
- Fire Wave: The standard shot is based on the adjusted version from Mega Man Xtreme, using a modified version of the original SNES charged attack. It now produces only six pillars of fire. The charged version has been redesigned as an enhanced attack that generates pillars of fire directly from the ground, with several times the original's hitbox coverage and damage output.

#### Special Attack:

##### Hadouken: A famous Street Fighter finishing move that everyone knows well. In this game it is also an extremely powerful special attack. It will only become a condition-based unlock after the full game is completed, but during the test phase you can use it freely.


##### Shoryuken: WIP. Another well-known Street Fighter finishing move, still under development.

#### Controls
- Dash -> Z
- Air dash (mid-air) -> Z
- Jump -> X
- Attack1 (X Buster and charge)  -> C
- Attack2 (Rapid X Buster) -> V
- Hadouken -> Down, Down Forward, Forward
- Up / Down / Left / Right -> Arrow keys


### Zero
![Zero](images/zero/zero.png)

![zero_gif](images/zero/20260625_zero_show_case_gif.gif)

![ZeroSaberSlashCombo](images/zero/zero_zs3combo.gif)
![ZeroSaberSlashCombo2](images/zero/zero_zs3combo2.gif)
![zero_zs_u_d](images/zero/zero_zs_u_d.gif)
![zero_zs3comboSP](images/zero/zero_zs3comboSP.gif)
![zero_zs_5_hit_combo](images/zero/Zero_5_hit_combo.gif)
![zero_zs_ryuenjin](images/zero/zero_zs_ryuenjin.gif)
![zero_zs_hyoretsuzan](images/zero/zero_zs_hyoretsuzan.gif)
![zero_zs_raikousen](images/zero/raikousen_1.png)
![zero_zs_enbuzan](images/zero/enbuzan.png)
![lethal_slasher](images/zero/lethal_slasher_1.png)
![Reppumai](images/zero/Reppumai_1.png)

![pulse_shain](images/zero/pulse_chain_1.png)

![Shuneimai](images/zero/Shuneimai_1.png)
![Shuneisyu](images/zero/Shuneishu_1.png)
![Shuneisyu](images/zero/Shuneishu_2.png)
![Roueisyu](images/zero/Roueisyu_1.png)
![Roueimai](images/zero/Roueimai_1.png)
![Roueimai](images/zero/Roueimai_2.png)
![Roueimai](images/zero/Roueimai_3.png)

![lethal_slasher](images/zero/lethal_slasher_1.png)


Zero is different from X. His design is primarily based on Mega Man X4, and in addition to the Zero Saber he is planned to have two normal weapons as well, both of which are still in development.

The Zero Saber takes inspiration from the Zero series, with adjusted feel and combo behavior. Against bosses during invincibility frames, most moves can ignore reduced damage and still deal very high damage. Special moves now consume energy, but energy can be restored by landing normal attacks, and it will also recover slowly when he is not attacking. Zero will probably receive the most development effort of all characters, and I hope he can offer an experience that feels different from the original games.

#### Abilities:

- Double Jump
- Air Dash
- Wall Kick
- Zero Saber Combo
- Pulse Chain
- Lethal Slasher

#### Normal Weapons:

- Zero Saber: His ground normal attacks use Slash 1, 2, and 3, similar to the three-hit sword combo from Mega Man X4. 
In the middle of the combo, he can cancel into Upper Slash or Drop Slash.
These combo routes have weaker impact, but they shorten attack time and allow higher DPS.
The combo options for Upper Slash and Drop Slash can also be swapped into the special moves Ryuenjin and Hyouretsuzan.
Their effects are similar: weaker impact during execution, but faster attack timing and higher DPS.
- Earth Crush [Z. Saber]: Inspired by a similar technique from X2. Zero slams the ground, triggering a massive energy explosion that deals heavy damage to enemies around him. It can also inflict considerable impact damage on bosses.
- Pulse Chain: A mid-range weapon with weaker damage, but it can quickly replenish weapon energy, and can attack with 8 directions.
- Lethal Slasher: A close-range weapon that can be used while moving.


#### Special moves (Japanese name will show kanji):

- Flame Mammoth => Ryuuenjin(龍炎刃) [Z. Saber]: A fire-element rising slash with multiple hits.
- Chill Penguin => Hyouretsuzan(冰烈斬) [Z. Saber]: An ice-element descending slash that hits once but dealing with high damage.
- Spark Mandrill => Raikousen(雷光閃) [Z. Saber]: A lightning-element invincible horizontal dash slash that also supports air dashing. Zero is invincible during the move and briefly afterward.
- Armored Armadillo => Ennbuzan(圓舞斬) [Z. Saber]: A fast 360-degree spinning slash with projectile-clearing effect.
- Launcher Octupus => Reppumai(烈風舞) [L. Slasher]: Fires four homing blade waves simultaneously, one in each direction (up, down, left, and right), each delivering multiple consecutive slashes.
- Storm Eagle => Reppujin(烈風刃) [L. Slasher]: A burst of four-times-speed rapid slashes. One input = four normal attacks as storm type attack.
- Launcher Octupus => Shuneimai(瞬影舞) [P. Chain]: Activated by charging P. Chain. Creates a life-draining vortex centered around Zero, similar to Launcher Octopus's attack. Enemies caught inside take continuous damage, and hitting an enemy a sufficient number of times restores a small amount of Zero's HP.
- Boomer Kuwanger => Shuneishu(瞬影襲) [P. Chain]: After hitting a normal P. Chain attack on an enemy, press the special attack button to instantly dash to the target and deliver a high-damage slash. Zero is invincible during the move and for a short period afterward.
- Sting Chameleon => Roueisyu(朧影襲) [P. Chain]: While equipped with P. Chain, press the special attack button to rapidly launch explosive kunai. The explosions also inflict additional impact damage. 
- Sting Chameleon => Roueimai(朧影舞) [P. Chain]: Activated by pressing the special attack button, Zero throws a smoke bomb at his current position, creating a stunning effect. Zero is invincible during the move and briefly afterward.



#### Controls:
- Dash -> Z
- Air dash (mid-air) -> Z
- Jump -> X
- Double Jump (mid-air) -> X
- ZeroSaber:
- ZeroSaberSlash1,2,3 combo (on ground) -> C,C,C
- Upper Slash (on ground) -> Up + C
- Drop Slash (mid-air) -> Down + C
- Ryuuenjin (on ground) -> Up + V
- Hyouretsuzan (mid-air) -> Down + V
- Ennbuzan (on ground or mid-air) -> V
- Raikousen -> DASH + V (on ground) or Left or Right + V (mid-air)
- Earth Crush (on ground) -> F
- Lethel Slasher:
- Reppujin -> V
- Reppumai -> F
- Pulse Chain:
- Shuneishin -> S (when hit enemy with aiming sign)
- Shuneimai -> C Pressed (charge)
- Roueisyu -> V
- Roueimai -> F
- Up / Down / Left / Right -> Arrow keys


### Mega Man
![Megaman](images/megaman/mm.png)
![mm_gif](images/megaman/20260625_megaman_show_case_gif.gif)
![Megaman sliding](images/megaman/mm_slide.png)
![Megaman Charge Lv2](images/megaman/mm_charge2.png)
![Jet Megaman](images/megaman/jet_mm.png)
![Power Megaman](images/megaman/power_mm.png)
![Blizzard attack](images/megaman/bliaazrd_attack_charge_hd.gif)
![Flame Blast](images/megaman/flame_blast_1.png)
![Flame Blast Charge](images/megaman/flame_blast_charge_1.png)
![Super Cutter](images/megaman/super_cutter_1.png)
![Air shooter](images/megaman/air_shooter_1.png)

Mega Man, the main character from the original series, faces enemies that are more than ten decades ahead in technology in Mega Man X. That means he has a much harder time against them than before, but his built-in Jet and Power Adapters also give him more options in battle than ever. It all comes down to how the player uses each form's tactics.
Due to lower attack and defense compared to X, this cause a much higher difficulty mainly suited for experienced players.

#### Abilities:

- Sliding: A faithful recreation of the original slide that also reduces his hurtbox.
- Level 2 Mega Buster Charge Shot: Based on the charge shot from Mega Man 5, with higher power.
- Jet Mega Man Adaptor: Based on the Jet Adaptor from Mega Man 6. In addition to flight, it also increases running speed and greatly improves mobility.
- Power Mega Man Adaptor: Based on the Power Adaptor from Mega Man 6. Compared to the original, it deals stronger damage, can destroy special objects and some boss projectiles, and has a higher impact value than the Mega Buster Charge Shot.



#### Special weapons: 
- Blizzard Attack: Designed as NES Mega Man 6, can spawn 4 snow flake behind Mega man and shoot, but Mega man can charge to summon a ice sculpture of Blizzard man, then Blizzard man sculpture will roll to attack every enemy he hit.
- Flame Blast: Its basic functionality is inspired by the NES version of Mega Man 6, but the fire pillars now pierce through enemies and can deal continuous damage. The charged version summons Flame Man to unleash a series of fire pillar attacks, followed by Zero transforming into a fireball and charging forward.
- Rolling Cutter: Its basic functionality is similar to the NES version of Mega Man. Once fired, the blade follows an arc-shaped trajectory before returning to Zero. The charged version has been redesigned after the Super Cutter attack in Cut Man's stage, launching five powerful blades simultaneously, with piercing capabilities and multi-hit damage.
- Air Shooter: Its basic functionality is similar to the NES version of Mega Man 2. The charged version combines several of Air Man's signature tornado patterns into a single powerful barrage. It covers an enormous area, and the tornadoes can pierce through enemies to deal multiple hits, making it particularly effective against large enemies.
- Triple Blade: (WIP)
- Dive Missile: (WIP)
- Leaf Shield: (WIP)
- Spark Shot: (WIP)

#### Controls
- Jump -> X
- Sliding (on ground) -> Down + X
- Attack1 (Mega Buster and charge) -> C
- Attack2 (Rapid Mega Buster) -> V
- Special action1 (Jet Adaptor and cancel) -> S
- Special action2 (Power Adaptor and cancel) -> F
- Return to Normal Mega Man -> S+F
- Up / Down / Left / Right -> Arrow keys


### Proto Man
![Proto Man](images/protoman/protoman.png)

![protoman_gif](images/protoman/20260625_protoman_show_case_gif.gif)

![ProtoShield](images/protoman/protoman_shield.png)
![ProtoStrike](images/protoman/protoman_strike.png)

Proto Man follows the Mega Man series concept where his defense is only half of Mega Man's. To compensate for this reduced defense, his Buster is designed so that Charge Shots can be fired directly by spending energy. As long as he has enough energy, he can keep rapid firing. When energy is low, he can use his normal Buster, which only fires two shots once, and restore energy quickly by hitting enemies. Energy also slowly recovers when he is not attacking.

In addition, Proto Shield can be activated while standing or jumping. Making good use of the shield allows him to block most enemy projectiles, greatly improving both survival and strategic depth.

Besides Proto man can use more energy to perform Proto Shield Dash, this skill use more energy but brings i-frames to Proto man, and also has a good damage output.


#### Abilities:

- Sliding
- Proto Man Strike
- Proto Buster
- Proto Shield
- Proto Shield Dash
- Proto Coil
- Movement Support (WIP)

#### Special weapons: 
- (WIP)

#### Controls
- Jump -> X
- Sliding (on ground) -> Down + X
- Attack1 (Proto Strike) -> C
- Attack2 (Rapid Proto Buster) -> V
- Summon Proto Coil -> S
- Proto Shield Dash (need enough energy) -> F
- Up / Down / Left / Right -> Arrow keys



### Bass
![Bass](images/bass/bass.png)

![bass_gif](images/bass/20260625_bass_show_case_gif.gif)

![BassDashJump](images/bass/bass_dash_jump.png)
![BassTreblaBoost](images/bass/bass_treble_boost_buster.png)

Bass is based on Mega Man & Bass.

His gameplay revolves around Dash Jump and Double Jump mobility, and his Bass Buster is a rapid-fire weapon with lower damage than the Mega Buster, but a much higher firing rate and projectile speed.

Because the Bass Buster deals less damage per shot, it ignores the reduced damage normally caused by boss invincibility frames, allowing Bass to maintain consistent damage output.

When combined with Treble, Bass gains the ability to fly and unleash more powerful attacks. While in this form, he fires a spread of five Bass Buster shots straight ahead. Each shot deals damage independently, allowing Bass to inflict massive damage at close range when multiple shots connect with the same target.

However, attacking consumes even more energy than flying, making energy management a key part of mastering this form. Players must carefully decide whether to spend their limited energy on mobility or firepower.

Energy gradually recovers when not in use, and landing hits with the normal Bass Buster restores additional energy. Effective energy management allows players to maximize the potential of this powerful form.

#### Abilities:

- Dash
- Slide
- Double Jump
- Bass Buster Rapid Shot
- Treble Boost

#### Special weapons: 
- (WIP)

#### Controls
- Dash -> Z
- Jump -> X
- Double Jump (mid-air, can use in dash jump) -> X
- Attack1 (Bass Buster rapid fire)  -> C
- Special action1 (Treble Boost transform and cancel) -> S
- Treble Boost Buster (during Treble Boost) -> C
- Up / Down / Left / Right -> Arrow keys


### Knight Arthur (WIP)
[image]

Knight Arthur is the main character of the Ghosts 'n Goblins series, famous for its brutally punishing difficulty and for challenging players who want to push their limits.

However, his original performance is far too weak. Aside from the armor that absolutely must remain as fragile as ever, the rest of his details are still being adjusted. Please look forward to it.

### Axl (WIP)

### Sigma (WIP)

### Iris (WIP)

### Future feature of other Capcom Characters

#### Street Fighters (WIP)

##### Ryu (WIP)

#### Resident Evil series (WIP)

##### Leon (WIP)

## Bosses & stages (WIP)

### Chill Penguin
![ChillPenguin](images/boss/chill_penguin/chill_penguin.png)

This is the boss with the highest level of completion so far, but some small details are still being adjusted. In the playtest version, you should be able to experience things that feel noticeably different from the original game.


### Spark Mandrill
![SparkMandrill](images/boss/spark_mandrill/spark_mandrill.png)
![SparkMandrill_railgun](images/boss/spark_mandrill/spark_mandrill_railgun.gif)
Spark Mandrill is designed to be a high-pressure close-range boss that excels at overwhelming players with aggressive movement and powerful melee attacks.

Compared to the original game, his AI has been expanded with additional behaviors and conditional attack patterns, allowing him to react more dynamically to different situations and playable characters. While he remains vulnerable to Ice-based weapons, repeatedly freezing him will gradually increase his freeze resistance, preventing players from defeating him through permanent freeze loops alone.

### Armored Armadillo (WIP)
[TODO]

### Launch Octopus (WIP)
[TODO]

### Boomer Kuwanger (WIP)
[TODO]

### Sting Chameleon (WIP)
[TODO]

### Storm Eagle (WIP)
[TODO]

### Flame Mammoth

Compared to the original, Flame Mammoth will feature a much wider variety of fire-based attacks, along with a significant increase in difficulty. However, his flames can be extinguished using wind-element weapons, providing a way to reduce the challenge.

Just like in the original, using the appropriate weapon can sever his trunk and weaken him.
More details will be included in the first Godot 4 release.

### Bospider (WIP)
[TODO]

### Rangda Bangda (WIP)
[TODO]

### D-Rex (WIP)
[TODO]

### Velguarder (WIP)
[TODO]

### Sigma (WIP)
[TODO]

## Nes Bosses
Nes character cannot use SNES character's special weapon, so there will be 8 bosses in Original Mega Man series for nes Characters to get their weapon.

### Blizzard Man (WIP)

### Elec Man (WIP)

### WIP

### Dive Man (WIP)

### Cut Man (WIP)

### WIP

### Air Man (WIP)

### WIP

## Development Status

### Current Version
20260721 - can test with boss fight:
- Chill Penguin
- Spark Mandrill

### In Progress
- Mega Man - weapon: flame blast
- Mega Man X - weapon: fire wave

### Planned Features
- Stages
- Special Weapons for Mega Man and X


## Credits

**Project Creator**

Programming, gameplay design, and the majority of sprite artwork were created by project owner **CrimsonCrazyGuy(Kaiji1315)**.

**Special Thanks**

- **firstjectsnowflakes35**
  - For sharing Godot source code that served as a valuable reference during the implementation of various gameplay systems.
  - https://www.youtube.com/@firstjectsnowflakes35

- **fallensoldier420**
  - Some character sprites used in this project are based on artwork created by fallensoldier420 and are used with the author's permission.
  - https://www.deviantart.com/fallensoldier420

- **mistermike**
  - For preparing and sharing high-quality character sprite resources through The Spriters Resource.
  - https://www.spriters-resource.com/profile/mistermike/

- **masque**
  - For preparing and sharing high-quality character sprite resources through The Spriters Resource.

- **Lord Zymeth**
  - For preparing and sharing high-quality character sprite resources with Castlevania Dracula X through The Spriters Resource.