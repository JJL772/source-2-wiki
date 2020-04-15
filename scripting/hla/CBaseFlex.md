# CBaseFlex

## Methods

### `GetFlexWeight`
```
float GetFlexWeight(int nFlexControllerIndex)
Gets the weight of a flex controller specified by index, use FindFlexController to get the index of a flex controller by name
```
------

### `FindFlexController`
```
int FindFlexController(string pszFlexControllerName)
Finds a flex controller by name, returns the index, -1 if not found
```
------

### `GetSceneByIndex`
```
handle GetSceneByIndex(int index)
Returns the instance of the scene entity at the specified index.
```
------

### `SetFlexWeight`
```
void SetFlexWeight(int nFlexControllerIndex, float flWeight)
Sets the weight of a flex controller specified by index, use FindFlexController to get the index of a flex controller by name
```
------

### `GetCurrentScene`
```
handle GetCurrentScene()
Returns the instance of the oldest active scene entity (if any).
```
------

### `ScriptPlayScene`
```
float ScriptPlayScene(string pszScene, float flDelay)
( vcd file, delay ) - play specified vcd file
```
------
