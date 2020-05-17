# Decider

## Methods

### `FindBestMatch`
```
handle FindBestMatch(handle)
Binding_FindBestMatch(query) : Query the database and return the best result found. If multiple of equal score found, an arbitrary one returns. 
```
------

### `AddRule`
```
bool AddRule(handle)
AddRule(CRule) : Add a CRule object (defined in rulescript_base.nut) 
```
------

### `FindAllMatches`
```
handle FindAllMatches(handle, float)
Binding_FindAllMatches(query,leeway) : Returns an array of all matching responses. If leeway is nonzero, all results scoring within 'leeway' of the best score return. 
```
------
