# New Version(26.7.0-alpha) Progress
███████████████░░░░░░░░ 65.22%

# Changelog For New Version

## New Content
- Added support for Fabric 26.2, and marked as compatible with Fabric 26.1.x.



## Changes
### Normal

- Refactored the underlying logic for right-click eating watermelon. The event no longer listens via the player right-click bus, with significant performance improvements expected.

### Melon Blocks
- Melon items no longer display a remaining portion in the inventory.
- Using shears to carve a melon block now only drops one melon seed or ender melon seed.
- Carving an unripe melon block with shears no longer drops seeds.
- Carving a glistering melon block or enchanted melon block with shears no longer drops gold nuggets.
- Carving a melon block with shears now shows particle effects.
- Slicing a watermelon block piece by piece with the Huaqiang Melon Knife now uses breaking the block instead of left-clicking.
- The Huaqiang Melon Knife's efficiency when breaking watermelon has been increased to 12, matching golden tools.
- Using the Huaqiang Melon Knife to right-click or break a watermelon block now shows particle effects.
- Right-clicking to eat a watermelon block now shows particle effects.

### Melon Lanterns
- Carved Melon With Redstone Lamp Can now only be obtained via crafting. When broken after being crafted, it will always drop itself.
- Carved melon lanterns containing torches, soul torches, lanterns, soul lanterns, shroomlights, sea lanterns, and three types of froglights are now combined into a single block, with internal models switched through block states.
- When broken, the combined block always drops a carved melon and the contained light source.
- Carved melon lanterns containing soul torches or soul lanterns now consistently emit a light level of 15.
- Carved melon lanterns with the four copper bulb variants now always drop themselves when broken, and can be crafted directly using a carved melon lantern, redstone dust, and the copper bulb ingredients in versions prior to 1.21.
- Optimized the state switching logic for carved melon lanterns with the four copper bulb variants.
- Redstone torches can no longer be placed into carved wmelon lanterns.

### Ender Melon
- The Ender Potion effect applied by Ender Melons can now be cleared by drinking milk.

### Removal
- Removed the two melon variants added in version 26.0.0-alpha: Sculk Melon and Jala Melon.

### Technical
- Removed some tags.
- Added tag `qa_better_melon:melon_blocks`, `qa_better_melon:melon_lights`, `qa_better_melon:melon_lights_copperbulb`, `qa_better_melon:melon_parts`, `qa_better_melon:melon_stairs`.

## Fixes
- Hunger and saturation values granted when eating unripe melons and regular melons were incorrect.
- Blocks cannot be placed on melon lanterns while sneaking.
