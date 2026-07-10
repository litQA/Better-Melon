# New Stable Version Progress
██████████████████████░ 95.65%

---
# Full Changelog For Next Stable Version

## New Content
### Pumpkin
#### Common
- The Huaqiang Melon Knife now gains the ability to cut pumpkins.
- Added Pumpkin Slab, Pumpkin Stairs and corresponding Cut-up Pumpkin Blocks.

#### Pumpkin Pizza
- Added raw pumpkin pizza, crafted from wheat and pumpkin blocks.
- Added pumpkin pizza base, obtained by smelting raw pumpkin pizza in a furnace.
- Added placeable pizza, which can be eaten four times, each bite consuming one quarter. It can be eaten even when hunger is full, restoring 4 hunger points and 8 saturation points per bite.
- Pizza is crafted using pumpkin pizza base, milk, eggs, any green‑skinned watermelon, and glistering watermelon.
- Added Azzip, whose crafting recipe is exactly the reverse of the pizza recipe.
- Azzip functions identically to pizza, differing only in appearance.

### Localization
- Added Russian (Russia, ru-RU) localization support.
- Added Korean (Democratic People's Republic of Korea, ko-KP) localization support.
- Added Traditional Chinese (Taiwan region, ***China***, zh-TW) localization support.

## Changes
### Normal

- Refactored the underlying logic for right-click eating watermelon. The event no longer listens via the player right-click bus, with significant performance improvements expected.
- Optimized the drop logic for Melon Blocks when destroyed.

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

### Enchanted Melon
- Doubled the chance for Enchanted Melon Slices to appear in Ruined Portal loot chests.
- Changed the registry name of Enchanted Melon Slice from `qa_better_melon:qa_golden_melon` to `qa_better_melon:enchanted_melon_slice` (Note Old Enchanted Melon Slices will disappear after upgrading. It is recommended to craft them into Enchanted Melons before updating the mod).
- Entities falling onto an Enchanted Melon now also trigger the melon shimmer effect.
- Enchanted Melons and Waxed Enchanted Melons now also trigger the shimmer effect when destroyed by explosions.
- The light level of all Enchanted Melon blocks is uniformly set to 6.

### Ender Melon
- The Ender Potion effect applied by Ender Melons can now be cleared by drinking milk.
- The icon for the post-teleport cooldown state in Ender Resonance has been changed.
- The trigger condition for automatic random teleport in Ender Resonance has been changed from being in water or rain to taking any damage.
- After teleporting upon taking damage in Ender Resonance, the cooldown before it can trigger again is reduced to 40 game ticks.

### Achievements
- Removed all annual limited achievements.
- Removed the achievement for collecting all Carved Melons.
- Kept 3 achievements related to total melons eaten, granted when the player has eaten a total of 100, 1000, and 5686 melons respectively.
- The command to check melon count has been changed from `/meloncount` to `/better_melon show_melon_count`.


### Removal
- Removed the two melon variants added in version 26.0.0-alpha: Sculk Melon and Jala Melon.
- Removed all functional effects from the wearable melon rind; it now serves only as a decorative item.

### Technical
- Removed some tags.
- Added tag `qa_better_melon:melon_blocks`, `qa_better_melon:melon_lights`, `qa_better_melon:melon_lights_copperbulb`, `qa_better_melon:melon_parts`, `qa_better_melon:melon_stairs`.

## Fixes
- Hunger and saturation values granted when eating unripe melons and regular melons were incorrect.
- Blocks cannot be placed on melon lanterns while sneaking.
- Enchanted Melon Slabs do not emit light.
