# CScriptParticleManager

## Methods

### `SetParticleAlwaysSimulate`
```
void SetParticleAlwaysSimulate(int)

```
------

### `SetParticleControl`
```
void SetParticleControl(int, int, Vector)
Set the control point data for a control on a particle effect
```
------

### `SetParticleControlOrientationFLU`
```
void SetParticleControlOrientationFLU(int, int, Vector, Vector, Vector)
(int iIndex, int iPoint, Vector vecForward, Vector vecLeft, Vector vecUp) - Set the orientation for a control on a particle effect
```
------

### `GetParticleReplacement`
```
string GetParticleReplacement(string, handle)

```
------

### `SetParticleControlForward`
```
void SetParticleControlForward(int, int, Vector)
(int iIndex, int iPoint, Vector vecForward ) - Set the forward direction for a control on a particle effect
```
------

### `DestroyParticle`
```
void DestroyParticle(int, bool)
(int index, bool bDestroyImmediately) - Destroy a particle, if bDestroyImmediately destroy it without playing end caps.
```
------

### `CreateParticle`
```
int CreateParticle(string, int, handle)
Creates a new particle effect
```
------

### `ReleaseParticleIndex`
```
void ReleaseParticleIndex(int)
Frees the specified particle index
```
------

### `SetParticleControlOffset`
```
void SetParticleControlOffset(int, int, Vector)
(int iIndex, int iPoint, Vector vecOffset ) - Set the linear offset for a control on a particle effect
```
------

### `SetParticleControlOrientation`
```
void SetParticleControlOrientation(int, int, Vector, Vector, Vector)
(int iIndex, int iPoint, Vector vecForward, Vector vecRight, Vector vecUp) - Set the orientation for a control on a particle effect (NOTE: This is left handed -- bad!!)
```
------

### `SetParticleControlEnt`
```
void SetParticleControlEnt(int, int, handle, int, string, Vector, bool)

```
------

### `CreateParticleForPlayer`
```
int CreateParticleForPlayer(string, int, handle, handle)
Creates a new particle effect that only plays for the specified player
```
------
