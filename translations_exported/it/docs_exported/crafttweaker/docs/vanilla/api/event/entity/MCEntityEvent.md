# MCEntityEvent

Questa classe è stata aggiunta da una mod con ID `crafttweaker`. Perciò, è necessario avere questa mod installata per poter utilizzare questa funzione.

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.api.event.entity.MCEntityEvent;
```


## Extending MCEvent

MCEntityEvent extends [MCEvent](/vanilla/api/event/MCEvent). That means all methods available in [MCEvent](/vanilla/api/event/MCEvent) are also available in MCEntityEvent

## Methods

### getEntity

Return Type: [MCEntity](/vanilla/api/entity/MCEntity)

```zenscript
MCEntityEvent.getEntity() as MCEntity
myMCEntityEvent.getEntity();
```

## Properties

| Name   | Type                                     | Ha Getter | Ha Setter |
| ------ | ---------------------------------------- | --------- | --------- |
| entity | [MCEntity](/vanilla/api/entity/MCEntity) | true      | false     |
