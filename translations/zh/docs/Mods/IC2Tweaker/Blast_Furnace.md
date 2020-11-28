# Blast Furnace

## 所属包名

`import mods.ic2.BlastFurnace;`

## 方法

- **[IItemStack](/Vanilla/Items/IItemStack/)[] outputs**
- **[IIngredient](/Vanilla/Variable_Types/IIngredient/) input**
- **int totalFluidCost** Per-tick IC2 liquefied air cost, measured in mB/tick
- **int time** Total time cost, measured in ticks

## 添加配方

```zenscript
mods.ic2.BlastFurnace.addRecipe(IItemStack[] outputs, IIngredient input, int totalFluidCost, int time);

mods.ic2.BlastFurnace.addRecipe([<minecraft:diamond>, <minecraft:emerald>], <minecraft:dirt> * 64, 1, 1000);
```

## Removal

For now simply remove the corresponding line in `config/ic2/blast_furnace.ini`.