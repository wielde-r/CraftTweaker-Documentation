# MCItemCraftedEvent

Questa classe è stata aggiunta da una mod con ID `crafttweaker`. Perciò, è necessario avere questa mod installata per poter utilizzare questa funzione.

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.api.event.player.MCItemCraftedEvent;
```


## Extending MCPlayerEvent

MCItemCraftedEvent extends [MCPlayerEvent](/vanilla/api/event/entity/player/MCPlayerEvent). That means all methods available in [MCPlayerEvent](/vanilla/api/event/entity/player/MCPlayerEvent) are also available in MCItemCraftedEvent

## Methods

### getCrafting

Return Type: [IItemStack](/vanilla/api/items/IItemStack)

```zenscript
MCItemCraftedEvent.getCrafting() as IItemStack
myMCItemCraftedEvent.getCrafting();
```

## Properties

| Name     | Type                                        | Ha Getter | Ha Setter |
| -------- | ------------------------------------------- | --------- | --------- |
| crafting | [IItemStack](/vanilla/api/items/IItemStack) | true      | false     |
