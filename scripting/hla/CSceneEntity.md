# CSceneEntity

## Methods

### `IsPaused`
```
bool IsPaused()
If this scene is currently paused.
```
------

### `EstimateLength`
```
float EstimateLength()
Returns length of this scene in seconds.
```
------

### `LoadSceneFromString`
```
bool LoadSceneFromString(string, string)
given a dummy scene name and a vcd string, load the scene
```
------

### `Start`
```
void Start(handle)
Start scene playback, takes activatorEntity as param
```
------

### `FindCamera`
```
handle FindCamera()
Get the camera
```
------

### `Cancel`
```
void Cancel()
Cancel scene playback
```
------

### `IsPlayingBack`
```
bool IsPlayingBack()
If this scene is currently playing.
```
------

### `AddBroadcastTeamTarget`
```
void AddBroadcastTeamTarget(int)
Adds a team (by index) to the broadcast list
```
------

### `RemoveBroadcastTeamTarget`
```
void RemoveBroadcastTeamTarget(int)
Removes a team (by index) from the broadcast list
```
------

### `FindNamedEntity`
```
handle FindNamedEntity(string)
given an entity reference, such as !target, get actual entity from scene object
```
------
