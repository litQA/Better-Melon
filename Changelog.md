---
# 26.7-alpha.0
## New Content
- Added support for Fabric 26.1.x.



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

## 更改
### 常规
- 优化了右键西瓜方块吃西瓜的逻辑，现在由右键方块绑定事件，而不再监听全局事件。


### 西瓜方块

- 西瓜物品在物品栏中不再显示剩余比例。

- 使用剪刀雕刻西瓜方块后只会掉落一个西瓜种子或末地西瓜种子。

- 使用剪刀雕刻未熟西瓜方块时不再掉落种子。

- 使用剪刀雕刻闪烁的西瓜方块或附魔西瓜方块后不再掉落金粒。

- 使用剪刀雕刻西瓜方块后会呈现粒子效果。

- 使用华强瓜刀逐块切西瓜的方式由左键点击调整为破坏西瓜方块。

- 华强瓜刀破坏西瓜的效率提升至12，与金质工具相当。

- 使用华强瓜刀右键或破坏西瓜方块切西瓜时会呈现粒子效果。

- 右键食用西瓜方块时会呈现粒子效果。



### 西瓜灯

- 雷石东西瓜灯现在只能通过合成获得。合成后，破坏始终掉落自身。

- 重构了西瓜右键食用的底层逻辑，事件不再通过玩家右键总线监听，性能预期大幅提升。

- 将内嵌火把、灵魂火把、灯笼、灵魂灯笼、菌光体、海晶灯以及三种蛙明灯的雕刻西瓜灯合并为一种方块，通过方块状态切换内部模型。

- 上述合并方块被破坏后，始终掉落雕刻的西瓜及其内含的光源。

- 内含灵魂火把或灵魂灯笼的雕刻西瓜灯，现在亮度统一为15。

- 四种铜灯变种的雕刻西瓜灯被破坏后均掉落自身，且在1.21之前的版本中可直接用西瓜灯、红石粉与铜灯原材料合成。

- 优化了四种铜灯变种雕刻西瓜灯的状态切换逻辑。

- 红石火把现在不能再被放入雕刻西瓜灯。

### 末影西瓜
- 由末地西瓜施加的末影药水效果现在可以被牛奶移除。


### 移除
- 移除了26.0.0-alpha版本中添加的两个西瓜变种：幽匿西瓜和火爆西瓜。

### 技术性
- 移除了一些标签
- 添加标签 `qa_better_melon:melon_blocks`, `qa_better_melon:melon_lights`, `qa_better_melon:melon_lights_copperbulb`, `qa_better_melon:melon_parts`, `qa_better_melon:melon_stairs`。


## 修复
- 食用未成熟的西瓜和普通西瓜提供的饥饿值和饱和度加成异常。

- 右键西瓜方块食用时，可能会意外放置某些方块。

- 潜行时无法在西瓜灯上放置方块。

