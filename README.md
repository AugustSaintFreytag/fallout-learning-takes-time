# Saint's Functional Literacy

A mod for Fallout: New Vegas and Tale of Two Wastelands that makes time pass when reading skill books and imposes restrictions on when reading is possible. Intended for hardcore mode playthroughs. Written in xNVSE, ESPLess.

## About

In vanilla, reading skill books is an instant and effectively free action with no downsides, the only limiting factor is finding the book. This mod adds a counter-balance that makes reading pass time based on the player's intelligence and perception stats. 

In hardcore mode, this means reading now automatically comes with a hunger, thirst, and exhaustion cost, on top of potentially costing daylight hours. Use of skill books is also now only possible when safe and healthy.

- Reading a book brings down the Pip-Boy, briefly fades to black, and makes time pass. 
- The time spent is calculated from intelligence, perception, and a bit of random variation.
- Using a book for the first time, a one-time tutorial message pops up to explain the mechanic.
- A corner message informs the player how much time was spent reading after the fade.
- Perusing books now has a satisfying foley sound backing.
- Reading is disallowed in combat or when injured (less than half HP).
- Reading is also disallowed when starving, dehydrated, or exhausted (hardcore mode).

Compatible with both New Vegas and TTW. Safe to add or remove at any time.

## Requirements

Requires xNVSE and its typical extensions, JIP NVSE for the script, ShowOff for event handlers, and KEYWORDS to recognize skill book items.

## License

This mod was created by Saint for free use by the Fallout mod community under the MIT license. It may be shared, modified, or redistributed as part of mod packs with attribution.