# Changelog

## Unreleased (2026-11-14)

### Added
- Custom sound effects for 10 abilities (Stable Audio, built from Noise Alchemy / Dark Fantasy Studio reference sounds; credit in the mod description). Mod combat sounds are new to Soulash 2, so please report any ability that plays no sound.
- Rare encounter Starwatch Circle (desert) with a recruitable Celestial Cartographer.
- Optional Soulash Extender support (needs the ExtraEffects plugin): the amplifier bonuses the plain game ignores now work. Unleash Charge and Charge Spark get their 5% repeat chance, Thunderstrike Meteors its 25% chance to cast Overload, Gravitational Shear lowers physical resistance by 5%, and Gravity Collapse, Event Tide and Gravity Tick trigger the new Gravity Drag on the target (slower movement for 2 turns, also when the amplified ability has no duration). Not yet tested in game.
- With the extender, Falling Star and Astral Step now give their Cosmic Charge to you, as their descriptions say (the plain game only gives a stacker to the creatures an ability hits). Not yet tested in game.

### Changed
- Gravity Pin, Falling Star and Meteorite Slam use the mod's own effects (Gravity Pin, Cosmic Shrapnel, Meteor Fall) instead of vanilla Firebolt / Freeze / Fireball.
- Stellar Ward now also speeds up the caster (0.1 turn quicker per step) for its duration.
- Mod description now states that the mod was implemented with the aid of AI tools.

### Fixed
- Stellar Ward had a resistance with no damage type, which can crash the game when a character under it takes damage; it now grants holy resistance.
- Collapse of Reality, Gravity Pin and Event Horizon sped their targets up instead of slowing them (a negative movement_speed is haste in Soulash 2); they now slow.
- Astral Step slowed you down instead of giving the astral swiftness its description promises; it is now a 5-turn haste.
- Falling Star's Cosmic Charge entry sat under effects, where the game ignores it; it is moved to effects_keys. Not yet tested in game.
- The Celestial Collegium did not show up in the build list: it had no building group or minimum area, which every buildable vanilla building has. It is now listed under Military, with a minimum area of 30. Not yet tested in game.

## Earlier history

- 2026-10-23: Register Cosmic Magic content IDs
- 2026-10-17: New art and icons generated via my local sd pipeline and new animations that are more fitting then just reusing the game animations
- 2026-10-12: Finally should be free of building issues
- 2026-10-08: Fixed issues
- 2026-10-07: Better mod description and fixed array error
- 2026-10-07: Trainer working
- 2026-10-04: Update still needs trainers wired
- 2026-09-27: The real mod
