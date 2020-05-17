# CBaseAnimating

## Methods

### `GetModelScale`
```
float GetModelScale()
Get scale of entity's model.
```
------

### `SetGraphLookTarget`
```
void SetGraphLookTarget(Vector vValue)
Pass the desired look target in world space to the graph
```
------

### `SetGraphParameterEnum`
```
void SetGraphParameterEnum(string szName, int nValue)
Pass the enum (int) value to the specified param
```
------

### `SetGraphParameterInt`
```
void SetGraphParameterInt(string szName, int nValue)
Pass the int value to the specified param
```
------

### `IsSequenceFinished`
```
bool IsSequenceFinished()
Ask whether the main sequence is done playing.
```
------

### `ResetSequence`
```
void ResetSequence(string pSequenceName)
Sets the active sequence by name, resetting the current cycle.
```
------

### `SetSequence`
```
void SetSequence(string pSequenceName)
Sets the active sequence by name, keeping the current cycle.
```
------

### `SetGraphParameter`
```
void SetGraphParameter(string pszParam, table svArg)
Set the specific param value, type is inferred from the type in script
```
------

### `SetGraphParameterVector`
```
void SetGraphParameterVector(string szName, Vector vValue)
Pass the vector value to the specified param in the graph
```
------

### `GetSequence`
```
string GetSequence()
Returns the name of the active sequence.
```
------

### `UnregisterAnimTagListener`
```
void UnregisterAnimTagListener(table hScript)
Unregisters the current string AnimTag listener, if any
```
------

### `ScriptLookupAttachment`
```
int ScriptLookupAttachment(string pAttachmentName)
Get the named attachment id.
```
------

### `StopAnimation`
```
void StopAnimation()
Stop the current animation by setting playback rate to 0.0.
```
------

### `GetAttachmentForward`
```
Vector GetAttachmentForward(int iAttachment)
Get the attachment id's forward vector.
```
------

### `SetGraphParameterFloat`
```
void SetGraphParameterFloat(string szName, float flValue)
Pass the float value to the specified param
```
------

### `SequenceDuration`
```
float SequenceDuration(string pSequenceName)
Returns the duration in seconds of the given sequence name.
```
------

### `ActiveSequenceDuration`
```
float ActiveSequenceDuration()
Returns the duration in seconds of the active sequence.
```
------

### `SetGraphParameterBool`
```
void SetGraphParameterBool(string szName, bool bValue)
Set the specific param on or off
```
------

### `GetGraphParameter`
```
table GetGraphParameter(string pszParam)
Get the value of the given animGraph parameter
```
------

### `SetModelScale`
```
void SetModelScale(float flScale)
Set scale of entity's model.
```
------

### `GetAttachmentAngles`
```
Vector GetAttachmentAngles(int iAttachment)
Get the attachment id's angles as a p,y,r vector.
```
------

### `RegisterAnimTagListener`
```
void RegisterAnimTagListener(handle hAnimTagListenerFunc)
Registers a listener for string AnimTags, replaces existing script listener if any
```
------

### `SetPoseParameter`
```
float SetPoseParameter(string szName, float fValue)
Set the specified pose parameter to the specified value.
```
------

### `GetAttachmentOrigin`
```
Vector GetAttachmentOrigin(int iAttachment)
Get the attachment id's origin vector.
```
------

### `GetCycle`
```
float GetCycle()
Get the cycle of the animation.
```
------
