# Randomizer Map

This mod is made for the [Randomizer v3.0 mod](https://github.com/homothetyhk/HollowKnight.RandomizerMod). Simply put, it adds a pin on the map for each randomized location. The pins will also show up differently if it's possible to get to that location with your current rando settings.

My hopes for this is to make learning the randomizer more accessible to newer players who don't know the base map very well, and to help more experienced players really learn the logic deeply and improve routing decisions.

Let me know if you find any bugs, have any feature requests, or just have questions.

## How it works

There are five different types of pins for randomized item checks: Small Dark (?) Pins, Big (?) Pins, Yellow (!) Pins, Small Dark ($) Pins, and Big Green ($) Pins.

The Small (?) indicate item locations that are currently out-of-logic. It's possible they are still obtainable through sequence breaks. 

The Big (?) indicate item locations that are currently in logic. One of these will contain the progression you are looking for. Big grey (?) pins indicate geo rocks. Big purple (?) pins indicate soul totems. Big blue (?) pins indicate lifeblood. Big red (?) pins indicate all other checks.

The Yellow (!) indicate item locations that are currently in logic but still require some form of prerequisite to obtain; I.E. Grubs for Grubfather or Essence for Seer.

The Small ($) indicate shop locations that are currently out-of-logic. It's possible they are still reachable through sequence breaks.

The Green ($) indicate shop locations that are currently in logic, as a reminder to the player that the shop may still have items for sale they may need.

In addition, non-randomized Grub and Essence sources have pins to indicate whether or not they are currently accessible in logic.

## Dependencies

Modding API, ModCommon, RandomizerMod3.0

## How to install

Ensure you have the above dependencies installed, then place the .dll file in the Hollow Knight/Managed/Mods directory.

## Thanks!

Huge thanks to everyone who's worked on the amazing randomizer and map mod.

And shout outs to the [Hollow Knight Racing Discord](https://discord.gg/F3upRRu). They've been really helpful and supportive as I've worked on this.

## Version History

### v0.3.2

First "official" release. Fixed the map boundaries so the map ACTUALLY scrolls to the edges without having to purchase every map first.

### v0.3.5

Compatibility for Rando 3

### v0.3.10

Compatibility for Rando 3.10

### v0.3.11

Non-randomized Grub and Essence pins
Settings update to handle different randomizer branches