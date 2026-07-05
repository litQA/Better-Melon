# New Version(26.7.0-alpha) Progress
███████████░░░░░░░░░░░░ 47.83%

# Changelog For New Version

## Changes
### Normal

- Refactored the underlying logic for right-click eating watermelon. The event no longer listens via the player right-click bus, with significant performance improvements expected.


### Melon Lanterns
- Carved Melon With Redstone Lamp Can now only be obtained via crafting. When broken after being crafted, it will always drop itself.

- Carved melon lanterns containing torches, soul torches, lanterns, soul lanterns, shroomlights, sea lanterns, and three types of froglights are now combined into a single block, with internal models switched through block states.
- When broken, the combined block always drops a carved melon and the contained light source.
- Carved melon lanterns containing soul torches or soul lanterns now consistently emit a light level of 15.
- Carved melon lanterns with the four copper bulb variants now always drop themselves when broken, and can be crafted directly using a carved melon lantern, redstone dust, and the copper bulb ingredients in versions prior to 1.21.
- Optimized the state switching logic for carved melon lanterns with the four copper bulb variants.


### Ender Melon
- The Ender Potion effect applied by Ender Melons can now be cleared by drinking milk.

### Removal
- Removed the two melon variants added in version 26.0.0-alpha: Sculk Melon and Jala Melon.

### Technical
- Removed some tags.
- Added tag `qa_better_melon:melon_blocks`, `qa_better_melon:melon_lights`, `qa_better_melon:melon_lights_copperbulb`, `qa_better_melon:melon_parts`, `qa_better_melon:melon_stairs`.

## Fixes
- Hunger and saturation values granted when eating unripe melons and regular melons were incorrect.
