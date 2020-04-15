# CPointTemplate

## Methods

### `ForceSpawn`
```
void ForceSpawn()
ForceSpawn() : Spawns all of the entities the point_template is pointing at.
```
------

### `GetSpawnedEntities`
```
handle GetSpawnedEntities()
GetSpawnedEntities() : Get the list of the most recent spawned entities
```
------

### `SetSpawnCallback`
```
void SetSpawnCallback(handle hCallbackFunc, handle hCallbackScope)
SetSpawnCallback( hCallbackFunc, hCallbackScope, hCallbackData ) : Set a callback for when the template spawns entities. The spawned entities will be passed in as an array.
```
------

### `DeleteCreatedSpawnGroups`
```
void DeleteCreatedSpawnGroups()
DeleteCreatedSpawnGroups() : Deletes any spawn groups that this point_template has spawned. Note: The point_template will not be deleted by this.
```
------
