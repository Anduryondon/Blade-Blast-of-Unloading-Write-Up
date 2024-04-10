# Blade Blast of Unloading - SSF Progression

Preface: this write-up is still work in progress.

# Build Strengths and Weaknessess

### Strengths:

#### High Evade Chance due to Evasion + Blind + Dread Banner
- even the basic level 90 setup has 80% chance to evade, which means due to evasion entropy we deterministically get 4 consecutive evades after being hit once
- enemies require an additional roll against our evade chance to determine whether a hit is a critical strike

### Screen-wide Freeze

- most enemies in maps will be frozen before they reach you
- bosses are chilled by 30% which makes evading anything dangerous a lot easier

### Damage

- the damage of the build is high for a starter build
- for a rough dps estimate use the PoB setting of `Blade Hits per Sec` and set it to `10`. In reality the DPS is higher compared to other hit builds -- from my bossing experience this is comparable to the DPS values of a dot skill in hectic fights. 
-  for an in-depth look into your real DPS you can have a look at [Primaeva's DPS Calculator](https://docs.google.com/spreadsheets/d/1bMDbaIPas-ER6-Nv2n6RUU0pCzodxDb-QNA6TY6fnEM/edit#gid=521806397). I haven't looked into the details, but when I compared some of the numbers I get for my PoB's when put into the calculator it's roughly what I would have guessed was my real bossing DPS. It also confirms my own experiments where runebinder is roughly a 20% dps increase and Like Clockwork is not better than Bomb Specialist on day 1-3 gear.

#### Option to get Stun Immunity
- Since we path next to Perfectionist we can sacrifice 3 passive points to get 60% chance to avoid stuns. We can then either have a flask suffix with stun avoidance or an abyss jewel with stun avoidance. This particularly helps on day 1 and Pinnacle Bossing.

### Weaknesses:

#### Recovery:
- By far the biggest downside of the build: we do not get any life recovery from our tree and have to solve this by other means.
- We solve this by getting **Cold Leech** and **Enduring Cry + Call to Arms**
- Personally I also recommend a non-instant `Sapping Eternal Life` flask. The flask recovers 4000 HP over 2 seconds, which means you recover 1000 hp in 0.5s after pressing the flask. Note that a `Seeting Divine Flask` recovers 1000 hp instantly. Due to high evasion and freeze it is very unlikely that you receive two consecutive hits before you recover the same amount on a non-instant flask compared to an instant flask. If you have never tried this out after they buffed flask life recovery values in 3.16 I recommend to at least give it a try.

#### Hit-based spell build

- We actually have to cast our spells to deal damage
- This means any form of reduced action speed does not only feel bad to play but is also dangerous since it might lock us in our cast animation
- To solve this partially we get 100% reduced chill effect, but reduced action speed debuffs from Delirium are still dangerous

#### No physical mitigation

- This particularly hurts for physical dots. Hits are not that dangerous due to freeze + evasion
- As a partial solution we run Leethe Shade. I did not have much issues with Ignite or Poison since a) a non-instant flask is very potent against dots; b) we do not get hit frequently so we do not get high stacks of poison
- For bosses we also get endurance charges from Enduring Cry. Since we are not a trickster this is not reliable mitigation though.
- While I do not run it personally there is an option to run [Aspect of the Crab](https://www.poewiki.net/wiki/Aspect_of_the_Crab), with a Black Morrigan scarab you can get an empowered version which allows for 12 Crab Barriers, which is additional 24% physical damage reduction.

#### Melee build for high health targets
- The way the skill works is that your Blade Blast explodes 10 times if you have 10 BV stacks, where each explosion gets a consecutively larger area. This also means that if you want all 10 explosions to reach the target you have to stand inside of it, otherwise the first explosions will miss.
- While there is no real solution other than adapting your gameplay being melee is not as bad when the enemy is chilled by 30%, since it allows you to dodge a lot of animations. Just don't stand still on the Dunes boss when he tries to hit you :)

# Gear Progression

The [Progression PoB](https://pobb.in/-5-vYRAItbcu) contains the necessary setup for getting the build from 1 to 90, as well as the basic gear pieces to look out for. As bandits we take Alira for this progression and switch to +2 in the endgame.
Note that we run Trinity. If you make any changes make sure that your cold damage and lightning damage are balanced in a way that you get full resonance.
## Leveling

We level as a basic caster build by going Rolling Magma into Firestorm+Cremation. You can also go Armageddon Brand instead of Firestorm, but Shadow has to run library for that, and there is not much difference between the skills to warrant that. Check out the different trees and skills in the PoB to see the progression. Do not forget to craft resists on your gear after killing Piety.

Once you reached act 6 make sure to level the following gems in the offhand:

- Blade Blast x3
- Arcanist Brand
- Automation
- Brand Recall

Make also sure you have the following socket setup ready before you leave Merc Lab Prison:

- a 4 link with GGGB colors
- a 4 link with BBGR colors


## Merc Lab Prison

We stay Firestorm / Cremation all the way until Merciless Labyrinth where we run lab until we get Bladeblast of Unloading. Make sure you have green gems in your inventory/stash to use `Transform a Skill Gem to be a random Transfigured Gem of the same colour` and use the targeted Divine Font option `Transform a Skill Gem to be a random Transfigured version` on the Bladeblast in your offhand. The target option is a 50/50 chance since there are two transfigured version of Blade Blast.

## Blade Blast of Unloading - Switch

Once you get your gem it's time to respec. The first respec requires 17 points, which you get from the campaign if you do Fetid Pool + Golden Hand quest.

### Gem Setup

Here is the gem setup that we want to end up with. Gems/Supports with the **optional** tag can be added/removed based on your personal preference and socket options.

Main Skill (in order of importance):
- Blade Blast of Unloading
- Phys to Lightning
- Trinity
- Inc. Critical Strikes
- Inc. Critical Damage
- Hypothermia

BV Generator:
- Arcanist Brand
- Blade Vortex - **keep at level 1** 
- Power Charge on Crit
- **optional**: Inc. Duration - this makes mapping smoother because you have to recast Arcanist Brand less often

Brand Recall:
- Brand Recall
- Automation
- **optional**: Steelskin - I did not do run during my own run, but after having a look at it I really suggest to try to fit this in

Enduring Cry:
- Enduring Cry
- Call to Arms

Auras:
- Grace
- Haste
- Tempest Shield - alternatively you can run Arctic Armour until you get your Pantheon unlocked
- Dread Banner

Mobility:
- Shield Charge - if you should die to phys reflect keep this at a low level
- **Optional** Faster Attacks - smoother mapping, more socket pressure
- Frost Blink

Curse:
- Assassin's Mark
- **alternative**: Enfeeble is a strong curse early on when your defenses are still weak because the reduced accuracy rating scales well with our high evasion setup. Particularly recommended for day 1 Betrayal in T16s. On day 1 I used Enfeeble for mapping and only swapped to Assassins Mark when I ran Catarina

Hatred:

- Hatred
- Divine Blessing
- Inspiration - required when your ES is still low
- **optional** : Inc. Duration - more QOL, more socket pressure

### Skill Gem Quality

By far the most important gems to get quality early on are in order of importance:

- Get ASAP:
	- Enduring Cry - getting this to 20% quality to increase recovery, which is one of the weak spots of the build. Honestly, before league start I did not value this highly, but after getting this to 20% quality the number of times where I died due to insufficient recovery went down to close to 0. This single upgrade fixes a lot on issues early on, so go for it asap.
	- Brand Recall - QoL and damage in one
- Good to have:
	- Shield Charge - faster mapping
	- Automation - 5% Brand Recall cdr
	- Dread Banner - higher chance to evade
	- Blade Blast - increases coverage
	- Assassin's Mark - we already get power charges due to running pcoc on BV, but this is another option
	- Call to Arms - 5% Enduring Cry cdr
	- Frostblink - faster mapping


### Gear

The Progression PoB has the basic gear that we want to get during our progression to level 90. It covers the following aspects:

#### Spell Suppression
We get 37% suppression from our tree, and the option to go for lucky spelll supression. The remaining suppression has to be obtained from our gear. Since we do not run Determination we can go for pure evasion pieces on Helm/Gloves/Boots which makes spell suppression rolls easier to obtain.
I recommend to focus on Rog to get gloves/boots/helm with suppression.

#### Reduced Mana Cost
Even with a level 1 blade vortex and the 30% mana to life cost conversion mastery we require some form of cost reduction. I ran two bench crafts to achieve this. Another possible option is to use Energy Leech support as a 5th/6th link. I've seen Qualia doing this, but I did not try this personally.

#### Reduced Chill Effect

I recommend to get this ASAP by any of the following sources:

- Pantheon with 50% reduced effect
- Bench craft on ring for 60% 
- Bench craft on gloves/boots for 40%
- Bench craft on boots for 100% chance to avoid being chilled / 20%ms
- Jewel with 30-35%

#### Fire Damage to Spells
We require at least one gear piece that allows our spells to deal fire damage to enable our Explosives Expert Ascendancy 40% crit multi. Any fire damage (global/to spells) is sufficient. Here are options to achieve this:
- Weapon: Adds # to # fire damage to spells
- Abyss Jewel: Adds # to # fire damage to spells (while holding a shield)
- Ring Bench Craft: Adds # to # fire damage / Adds # to # lightning damage
	- note that this is global damage and therefore works on spells

#### Cold Leech

Since we do not have any recovery outside from Enduring Cry we want to get Cold Leech as early as possible. Here are the options to get this early:
- Alva Temple Amulet
- Delve Ring from cold delve nodes
- Eater of Worlds implicit on gloves
- Shaper/Redeemer amulet
- Doryani's Lesson cluster jewel
- Normal Atziri belt (cold version, quite rare, not recommended)

From all these I recommend the Alva temple. You can swap resists with Harvest if you get Fire/Lightning leech, and it's easier to obtain than running Delve, and early on you don't have much eater currency to use them on probably sub-par gloves. On league start I planned to Delve for this and I regret it because I only got a small amount of cold nodes, and you don't want to spend much time in Delve when you can progress your atlas instead.

> It should be noted that the most powerful one here is Doryani's Lesson on a 3-notable Large Cluster jewel. However, the chance to get this on a decent 3-notable cluster is insanely low, which is why I don't recommend this in SSF. I got one by using the Betrayal Guff crafts on a cluster jewel, but I can't really recommend this as a target strategy. But it's a good option if you are lucky.


#### Phys Damage taken As
There are not many early sources for this stat, but you should use it if you have the option:
- Bench craft / unveil on helm
- Exarch implicit on helm
- Bench craft / unveil on chest

#### Critical Strike Chance
Good gear pieces to get spell crit are wand/sceptre/rune daggers, a dex/int shield, and the amulet slot. Use Harvest reforge caster and Rog for a decent spell crit shield, optimally with suppression


#### Energy Shield
We require some decent amount of Energy Shield to be able to use Hatred with Divine Blessing. We run a Sadist Garb together with a dex/int shield to achieve this. Depending on your chest you might have to run inspiration in your 

#### Resistances
The remaining suffixes will be used for resistances. If you run a lot of Jun/Catarina I recommend to be close to maximum chaos resistance, otherwise you will have a bad time with the degen in the fight.
