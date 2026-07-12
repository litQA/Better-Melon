# 27.7.3
## Fixes
- Melon blocks fail to place in versions 1.19.4 and below due to the lack of the native `#replaceable` tag.
- Axes do not increase the mining speed of watermelon blocks.
- Some Ender Melon blocks incorrectly have their blast resistance set to 1 instead of 3.

## 修复
- 1.19.4及以下版本由于原生无`#replaceable`标签导致西瓜方块放置失败。
- 斧头不能加快破坏西瓜方块的速度。
- 部分末地西瓜方块的抗性被错误地设置为1，而不是3。

---

# 26.7.2-beta
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
### Localization
- Added Russian (Russia, ru-RU) localization support.
- Added Korean (Democratic People's Republic of Korea, ko-KP) localization support.
- Added Traditional Chinese (Taiwan region, ***China***, zh-TW) localization support.
## Changes
### Removal
- Removed all functional effects from the wearable melon rind; it now serves only as a decorative item.

## 新内容
### 南瓜
### 通用
- 华强瓜刀新增功能，现在可以切割南瓜。
- 添加了南瓜台阶，南瓜楼梯以及对应的切块南瓜。

### 披萨
- 新增生南瓜披萨，由小麦和南瓜块合成获得。
- 新增南瓜披萨基底，将生南瓜披萨放入熔炉烧制即可得到。
- 新增可放置的披萨，每份披萨可食用四次，每次消耗四分之一，即使在饥饿值满时也能食用，每次食用恢复4点饥饿值和8点饱和度。
- 披萨的合成材料包括南瓜披萨基底、牛奶、鸡蛋、任意绿皮西瓜以及闪烁的西瓜。
- 新增萨披，其合成配方恰好是披萨配方的上下颠倒。
- 萨披与披萨功能完全一致，仅外观存在差异。

### 本地化
- 新增俄语（俄罗斯，ru-RU）本地化支持。
- 新增朝鲜语（朝鲜民主主义共和国，ko-KP）本地化支持。
- 新增繁体中文（中国台湾地区，zh-TW）本地化支持。
## 更改
### 移除
- 头戴西瓜皮的所有原有功能已被移除，现在仅作为装饰品使用
--- 

# 26.7.1-alpha
## Changes
### Melon Blocks
- Optimized the drop logic for Melon Blocks when destroyed.

### Enchanted Melon
- Doubled the chance for Enchanted Melon Slices to appear in Ruined Portal loot chests.
- Changed the registry name of Enchanted Melon Slice from `qa_better_melon:qa_golden_melon` to `qa_better_melon:enchanted_melon_slice` (Note Old Enchanted Melon Slices will disappear after upgrading. It is recommended to craft them into Enchanted Melons before updating the mod).
- Entities falling onto an Enchanted Melon now also trigger the melon shimmer effect.
- Enchanted Melons and Waxed Enchanted Melons now also trigger the shimmer effect when destroyed by explosions.
- The light level of all Enchanted Melon blocks is uniformly set to 6.

### Ender Melon
- The icon for the post-teleport cooldown state in Ender Resonance has been changed.
- The trigger condition for automatic random teleport in Ender Resonance has been changed from being in water or rain to taking any damage.
- After teleporting upon taking damage in Ender Resonance, the cooldown before it can trigger again is reduced to 40 game ticks.

### Achievements
- Removed all annual limited achievements.
- Removed the achievement for collecting all Carved Melons.
- Kept 3 achievements related to total melons eaten, granted when the player has eaten a total of 100, 1000, and 5686 melons respectively.
- The command to check melon count has been changed from `/meloncount` to `/better_melon show_melon_count`.

## Fixes
- Enchanted Melon Slabs do not emit light.

## 更改
### 常规
- 西瓜方块破坏后的掉落物逻辑优化

### 附魔西瓜
- 附魔西瓜片在废弃传送门战利品宝箱中的出现概率翻倍。
- 附魔西瓜片注册名由 `qa_better_melon:qa_golden_melon` 改为 `qa_better_melon:enchanted_melon_slice`（注意 旧版附魔西瓜片升级后会直接消失，建议先合成为附魔西瓜再升级模组）。
- 实体摔落到附魔西瓜上时现在也会触发西瓜闪烁效果。
- 附魔西瓜和涂蜡的附魔西瓜被爆炸破坏时现在也会触发西瓜闪烁效果。
- 附魔西瓜所有方块的亮度统一调为6。

### 末地西瓜
- 末影共生状态传送后冷却状态的图标已修改。
- 末影共生自动随机传送的触发条件由处在水或雨水中改为受到任意伤害。
- 末影共生受伤传送后，可再次触发传送的冷却时间缩短为40游戏刻。

### 成就
- 移除了所有年度限定成就。
- 移除了收集所有雕刻西瓜的成就。
- 保留3项与吃西瓜总数相关的成就，分别在累计吃掉100、1000、5686个西瓜时授予。
- 查询吃西瓜总数的指令由 `/meloncount` 改为 `/better_melon show_melon_count`。

## 修复
- 附魔西瓜台阶不发光。


---
# 26.7.0-alpha
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

