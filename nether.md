## Introduction

Hello and welcome. I just wanted to create a quick video about the Dream nether challenge. I hope to give an overview tutorial of the major steps you need to take in completing a run as well as some tips that might help you. I also wanted to share what I have discovered through looking at the plugin's code and how you can use this knowledge to your advantage.

## Tutorial Steps

There are four main stages to a run:

- Getting wood and tools.
- Getting gold and bartering with piglins.
- Finding a fortress and killing blazes.
- Finding a stronghold and killing the dragon.

The middle two steps could be swapped but, unless you spawn right by a fortress, I wouldn't recommend it and I will explain why later.

There are also two additional things that you should keep in mind and those are:

- Food so you can heal.
- Equipment to make fights easier.

## Tutorial Wood

Okay so you can get wood from two main places, those are crimson forests and warped forests. If you can't find one of these in the first few minutes of a run then you should probably reset.

The three main tools you want to craft are:

- An axe for chopping wood.
- A pickaxe for mining gold.
- A sword for killing mobs.

To make traversing the Nether a bit easier you should get some blocks at this stage as well. Crafting planks from logs is probably the most efficient way.

I would argue that the warped forest is quite a bit better than the crimson one as hoglins don't spawn. You can also collect warped fungi and nylium as well as twisted vines. I will explain the importance of these later.

If there is blackstone nearby then you should use it to craft stone tools.

Blackstone can be found in basalt deltas, bastion remnants and veins.

## Tutorial Gold

The next step is getting gold and bartering.

You can get gold from veins, bastion remnants and chests.

A small amount is also dropped by zombified piglins, more commonly known as zombie pigmen.

Your first priority should be getting gold boots so that piglins don't attack you.

You should barter with piglins until you get twelve ender pearls at the very least. This takes twenty pieces of gold on average.

Other useful drops include leather, string, fire resistance potions and iron boots. I will cover the uses for these in the equipment section.

## Tutorial Fortress

After that you need to find a fortress and kill blazes.

Unfortunately finding one is very luck dependant.

You probably don't want to venture too far from spawn so I would suggest trying to circle around zero zero whilst searching.

Looting the fortress is one of the only opportunities to get iron and diamonds so you should defiantly consider it.

You should kill blazes to get at least six rods which is equivalent to twelve powder.

You can increase the spawn rate of blazes by mining blocks below the spawner.

## Tutorial Stronghold

Next you need to find the stronghold.

You should only craft a few eyes of ender initially since there may already be some in the portal.

Try and throw eyes selectively as they can break or fall in lava.

You should consider looting the stronghold when you find it.

Unfortunately respawn anchors don't work so don't waste your time crafting them.

The end acts exactly the same as the nether so there is no point in trying to place water.

Twisting vines can serve as a replacement for preventing fall damage.

## Tutorial Food

You should constantly be considering your hunger.

There are only a few ways of getting food in the nether.

Rotten flesh can be obtained from zombified piglins. Since they also drop a small amount of gold it may be worth building a two block high tower and killing some near the start of a run.

Hoglins provide pork however they can be dangerous to fight. Since warped fungus repels hoglins it can be used to help kill them more safely.

I would say that the best food source is mushroom stew. You should try and collect brown and red mushrooms whenever you see them.

Other foods can be found in chests.

## Tutorial Equipment

Equipment should also constantly be on your mind.

Bartering gives many useful items such as:

- Leather for armour.
- String for bows and beds.
- Soul speed iron boots for improved movement and armour.
- Fire resistance potions to help with fights and movement.

This is why I recommend bartering before looking for a fortress.

Libraries in strongholds also act as a good source of string.

Skeletons can be found in soul sand valleys and drop arrows that are essential for the dragon fight.

All other equipment must be obtained from chests you find.

## Generation Overview

Okay, now we can go in to how the plugin generates the worlds.

First of all a random seed is generated. This is used to create:

- An overworld world.
- One nether world.
- Another nether world.
- An end world.

Notice that the two nether worlds are identical at this stage since they share the same seed.

The overworld and one of the nethers are combined to make the nether overworld where you spawn in.

The other nether is combined with the end to make the nether end where the dragon fight takes place.

## Generation Overworld

After the overworld and one of the nethers are created, the closest stronghold to spawn in the overworld is copied to the nether. It keeps the exact same X and Z coordinates as in the overworld. The reason I suggest not venturing too far from spawn is because only this one stronghold is copied.

Only cosmetic details of the stronghold are changed to give it a nether appearance. All chest loot remains the same. Also, structures nearby to the stronghold sharing the same materials may also be copied.

Since the stronghold's position is the same as in the overworld, all normal theories about locating it can be used.

## Generation End

After the second nether and end are generated, the obsidian pillars are taken from the end and placed in the exact same positions in the nether.

The portal is always placed at exactly zero sixty-one zero.

And the platform is always placed at exactly one-hundred forty-eight zero.

Since both nethers use the same seed this means that you can look at these positions right at the beginning of a run and reset if it is not a good dragon fight location.

## Thank You

Thank for watching. I hope you found this useful. If you have any tips that I have missed or if you need help with the plugin then please feel free to leave a comment.

My next video will be solving the unsolved mystery of the longest possible jump in Minecraft. I have looked into the game's code and made a mod, it's gaining to be good.