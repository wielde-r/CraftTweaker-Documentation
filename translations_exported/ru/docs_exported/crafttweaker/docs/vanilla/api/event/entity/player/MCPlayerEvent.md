# MCPlayerEvent

Этот класс был добавлен модом с mod-id `crafttweaker`. Так что если вы хотите использовать эту функцию, вам нужно установить этот мод.

## Импорт класса

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.api.event.entity.player.MCPlayerEvent;
```


## Extending MCLivingEvent

MCPlayerEvent extends [MCLivingEvent](/vanilla/api/event/entity/MCLivingEvent). That means all methods available in [MCLivingEvent](/vanilla/api/event/entity/MCLivingEvent) are also available in MCPlayerEvent

## Methods

### getPlayer

Return Type: [MCPlayerEntity](/vanilla/api/entity/MCPlayerEntity)

```zenscript
MCPlayerEvent.getPlayer() as MCPlayerEntity
myMCPlayerEvent.getPlayer();
```

## Свойства

| Название | Тип                                                  | Имеет Getter | Имеет Setter |
| -------- | ---------------------------------------------------- | ------------ | ------------ |
| player   | [MCPlayerEntity](/vanilla/api/entity/MCPlayerEntity) | true         | false        |
