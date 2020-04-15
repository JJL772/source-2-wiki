# CEntities

## Methods

### `First`
```
handle First()
Begin an iteration over the list of entities
```
------

### `FindAllByModel`
```
table FindAllByModel(string)
Find entities by model name.
```
------

### `FindByName`
```
handle FindByName(handle, string)
Find entities by name. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
```
------

### `FindInSphere`
```
handle FindInSphere(handle, Vector, float)
Find entities within a radius. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
```
------

### `FindAllByTarget`
```
table FindAllByTarget(string)
Find entities by targetname.
```
------

### `FindByClassname`
```
handle FindByClassname(handle, string)
Find entities by class name. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
```
------

### `FindAllByName`
```
table FindAllByName(string)
Find all entities by name. Returns an array containing all the found entities in it.
```
------

### `FindAllByClassnameWithin`
```
table FindAllByClassnameWithin(string, Vector, float)
Find entities by class name within a radius.
```
------

### `FindByClassnameNearest`
```
handle FindByClassnameNearest(string, Vector, float)
Find entities by class name nearest to a point.
```
------

### `FindByModel`
```
handle FindByModel(handle, string)
Find entities by model name. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
```
------

### `FindAllByNameWithin`
```
table FindAllByNameWithin(string, Vector, float)
Find entities by name within a radius.
```
------

### `FindByClassnameWithin`
```
handle FindByClassnameWithin(handle, string, Vector, float)
Find entities by class name within a radius. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
```
------

### `FindByNameWithin`
```
handle FindByNameWithin(handle, string, Vector, float)
Find entities by name within a radius. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
```
------

### `FindAllByClassname`
```
table FindAllByClassname(string)
Finds all entities by class name. Returns an array containing all the found entities.
```
------

### `FindAllInSphere`
```
table FindAllInSphere(Vector, float)
Find entities within a radius.
```
------

### `FindByNameNearest`
```
handle FindByNameNearest(string, Vector, float)
Find entities by name nearest to a point.
```
------

### `CreateByClassname`
```
handle CreateByClassname(string)
Creates an entity by classname
```
------

### `GetLocalPlayer`
```
handle GetLocalPlayer()
Get the local player.
```
------

### `Next`
```
handle Next(handle)
Continue an iteration over the list of entities, providing reference to a previously found entity
```
------

### `FindByTarget`
```
handle FindByTarget(handle, string)
Find entities by targetname. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
```
------

### `FindByModelWithin`
```
handle FindByModelWithin(handle, string, Vector, float)
Find entities by model name within a radius. Pass 'null' to start an iteration, or reference to a previously found entity to continue a search
```
------
