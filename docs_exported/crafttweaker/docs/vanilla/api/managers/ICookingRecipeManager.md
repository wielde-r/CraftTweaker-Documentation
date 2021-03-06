# ICookingRecipeManager

Default interface for Registry based handlers as they can all remove recipes by ResourceLocation.

This class was added by a mod with mod-id `crafttweaker`. So you need to have this mod installed if you want to use this feature.

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.api.registries.ICookingRecipeManager;
```


## Implemented Interfaces
ICookingRecipeManager implements the following interfaces. That means all methods defined in these interfaces are also available in ICookingRecipeManager

- [IRecipeManager](/vanilla/api/managers/IRecipeManager)
## Methods

### addRecipe

Adds a recipe based on given params.

Return Type: void

```zenscript
ICookingRecipeManager.addRecipe(name as string, output as IItemStack, input as IIngredient, xp as float, cookTime as int) as void
furnace.addRecipe("wool2diamond", <item:diamond>, <tag:minecraft:wool>, 1.0, 0);
```
| Parameter | Type | Description |
|-----------|------|-------------|
| name | string | Name of the new recipe |
| output | [IItemStack](/vanilla/api/items/IItemStack) | IItemStack output of the recipe |
| input | [IIngredient](/vanilla/api/items/IIngredient) | IIngredient input of the recipe |
| xp | float | how much xp the player gets |
| cookTime | int | how long it takes to cook |

### removeRecipe

Removes a recipe based on it's output and input.

Return Type: void

```zenscript
ICookingRecipeManager.removeRecipe(output as IItemStack, input as IIngredient) as void
furnace.removeRecipe(<item:minecraft:diamond>, <tag:minecraft:wool>);
```
| Parameter | Type | Description |
|-----------|------|-------------|
| output | [IItemStack](/vanilla/api/items/IItemStack) | IItemStack output of the recipe. |
| input | [IIngredient](/vanilla/api/items/IIngredient) | IIngredient of the recipe to remove. |


