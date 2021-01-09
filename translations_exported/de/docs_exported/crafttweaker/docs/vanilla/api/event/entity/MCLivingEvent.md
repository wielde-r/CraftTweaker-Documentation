# MCLivingEvent

This class was added by a mod with mod-id `crafttweaker`. So you need to have this mod installed if you want to use this feature.

## Diese Klasse importieren

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.api.event.entity.MCLivingEvent;
```


## Extending MCEntityEvent

MCLivingEvent extends [MCEntityEvent](/vanilla/api/event/entity/MCEntityEvent). That means all methods available in [MCEntityEvent](/vanilla/api/event/entity/MCEntityEvent) are also available in MCLivingEvent

## Methoden

### getEntityLiving

Return Type: [MCLivingEntity](/vanilla/api/entity/MCLivingEntity)

```zenscript
MCLivingEvent.getEntityLiving() as MCLivingEntity
myMCLivingEvent.getEntityLiving();
```

## Properties

| Name         | Type                                                 | Has Getter | Has Setter |
| ------------ | ---------------------------------------------------- | ---------- | ---------- |
| entityLiving | [MCLivingEntity](/vanilla/api/entity/MCLivingEntity) | true       | false      |
