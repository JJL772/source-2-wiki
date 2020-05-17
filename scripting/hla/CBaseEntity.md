# CBaseEntity

## Methods

### `GetTeamNumber`
```
int GetTeamNumber()
Get the team number of this entity.
```
------

### `GetChildren`
```
handle GetChildren()
Get the entities parented to this entity.
```
------

### `IsNPC`
```
bool IsNPC()
Is this entity an CAI_BaseNPC?
```
------

### `SetAngularVelocity`
```
void SetAngularVelocity(float pitchVel, float yawVel, float rollVel)
Set the local angular velocity - takes float pitch,yaw,roll velocities
```
------

### `SetMaxHealth`
```
void SetMaxHealth(int amt)
Set the maximum health of this entity.
```
------

### `Kill`
```
void Kill()

```
------

### `SetLocalScale`
```
void SetLocalScale(float flScale)

```
------

### `DeleteAttribute`
```
void DeleteAttribute(string pName)
Delete an entity attribute.
```
------

### `GetLocalScale`
```
float GetLocalScale()

```
------

### `GetSpawnGroupHandle`
```
int GetSpawnGroupHandle()
Returns the spawn group handle of this entity
```
------

### `SetLocalOrigin`
```
void SetLocalOrigin(Vector origin)
Set entity local origin from a Vector
```
------

### `TransformPointWorldToEntity`
```
Vector TransformPointWorldToEntity(Vector vPoint)
Returns the input Vector transformed from world to entity space
```
------

### `SetContextThink`
```
void SetContextThink(string pszContextName, handle hThinkFunc, float flInterval)
Set a think function on this entity.
```
------

### `Attribute_SetIntValue`
```
void Attribute_SetIntValue(string pName, int nValue)
Set int value for an entity attribute.
```
------

### `HasAttribute`
```
bool HasAttribute(string pName)
See if an entity has a particular attribute.
```
------

### `Attribute_GetIntValue`
```
int Attribute_GetIntValue(string pName, int nDefault)
Get int value for an entity attribute.
```
------

### `GetBoundingMaxs`
```
Vector GetBoundingMaxs()
Get a vector containing max bounds, centered on object.
```
------

### `GetCenter`
```
Vector GetCenter()
Get vector to center of object - absolute coords
```
------

### `GetOwner`
```
handle GetOwner()
Gets this entity's owner
```
------

### `SetConstraint`
```
void SetConstraint(Vector vPos)
Set the position of the constraint.
```
------

### `GetContext`
```
table GetContext(string name)
GetContext( name ): looks up a context and returns it if available. May return string, float, or null (if the context isn't found).
```
------

### `SetMass`
```
void SetMass(float flMass)
Set the mass of an entity. (does nothing if it doesn't have a physics object)
```
------

### `SetAbsScale`
```
void SetAbsScale(float flScale)

```
------

### `OverrideFriction`
```
void OverrideFriction(float duration, float friction)
Takes duration, value for a temporary override.
```
------

### `SetEntityName`
```
void SetEntityName(string pName)
Set the name of an entity.
```
------

### `GetUpVector`
```
Vector GetUpVector()
Get the up vector of the entity.
```
------

### `GetVelocity`
```
Vector GetVelocity()

```
------

### `RemoveEffects`
```
void RemoveEffects(int nFlags)
RemoveEffects( int ): Removes the render effect flag.
```
------

### `SetLocalAngles`
```
void SetLocalAngles(float fPitch, float fYaw, float fRoll)
Set entity local pitch, yaw, roll by component
```
------

### `Attribute_SetFloatValue`
```
void Attribute_SetFloatValue(string pName, float flValue)
Set float value for an entity attribute.
```
------

### `GetBaseVelocity`
```
Vector GetBaseVelocity()
Get Base? velocity.
```
------

### `GatherCriteria`
```
void GatherCriteria(handle hResult)
Returns a table containing the criteria that would be used for response queries on this entity. This is the same as the table that is passed to response rule script function callbacks.
```
------

### `Trigger`
```
void Trigger()
Fires off this entity's OnTrigger responses.
```
------

### `GetLocalAngles`
```
QAngle GetLocalAngles()
Get entity local pitch, yaw, roll as a QAngle
```
------

### `SetHealth`
```
void SetHealth(int nHealth)
Set the health of this entity.
```
------

### `GetOrigin`
```
Vector GetOrigin()

```
------

### `EmitSound`
```
void EmitSound(string soundname)
Plays a sound from this entity.
```
------

### `Attribute_GetFloatValue`
```
float Attribute_GetFloatValue(string pName, float flDefault)
Get float value for an entity attribute.
```
------

### `GetAngularVelocity`
```
Vector GetAngularVelocity()
Get the local angular velocity - returns a vector of pitch,yaw,roll
```
------

### `TakeDamage`
```
int TakeDamage(handle hInfo)
Apply damage to this entity. Use CreateDamageInfo() to create a damageinfo object.
```
------

### `TransformPointEntityToWorld`
```
Vector TransformPointEntityToWorld(Vector vPoint)
Returns the input Vector transformed from entity to world space
```
------

### `GetAbsScale`
```
float GetAbsScale()

```
------

### `SetForwardVector`
```
void SetForwardVector(Vector v)
Set the orientation of the entity to have this forward vector.
```
------

### `SetContextNum`
```
void SetContextNum(string pName, float fValue, float duration)
SetContextNum( name , value, duration ): store any key/value pair in this entity's dialog contexts. Value must be a number (int or float). Will last for duration (set 0 to mean 'forever').
```
------

### `GetAbsOrigin`
```
Vector GetAbsOrigin()

```
------

### `EmitSoundParams`
```
void EmitSoundParams(string soundname, int nPitch, float flVolume, float flDelay)
Plays/modifies a sound from this entity. changes sound if nPitch and/or flVol or flSoundTime is > 0.
```
------

### `NextMovePeer`
```
handle NextMovePeer()

```
------

### `ApplyLocalAngularVelocityImpulse`
```
void ApplyLocalAngularVelocityImpulse(Vector angImpulse)
Apply an Ang Velocity Impulse
```
------

### `GetMaxHealth`
```
int GetMaxHealth()
Get the maximum health of this entity.
```
------

### `PrecacheScriptSound`
```
void PrecacheScriptSound(string soundname)
Precache a sound for later playing.
```
------

### `GetLocalAngularVelocity`
```
QAngle GetLocalAngularVelocity()
Maybe local angvel
```
------

### `ApplyAbsVelocityImpulse`
```
void ApplyAbsVelocityImpulse(Vector vecImpulse)
Apply a Velocity Impulse
```
------

### `GetLocalVelocity`
```
Vector GetLocalVelocity()
Get Entity relative velocity.
```
------

### `GetHealth`
```
int GetHealth()
Get the health of this entity.
```
------

### `EyeAngles`
```
QAngle EyeAngles()
Get the qangles that this entity is looking at.
```
------

### `SetVelocity`
```
void SetVelocity(Vector vecVelocity)

```
------

### `GetModelName`
```
string GetModelName()
Returns the name of the model.
```
------

### `SetContext`
```
void SetContext(string pName, string pValue, float duration)
SetContext( name , value, duration ): store any key/value pair in this entity's dialog contexts. Value must be a string. Will last for duration (set 0 to mean 'forever').
```
------

### `GetRightVector`
```
Vector GetRightVector()
Get the right vector of the entity.
```
------

### `GetAnglesAsVector`
```
Vector GetAnglesAsVector()
Get entity pitch, yaw, roll as a vector.
```
------

### `GetForwardVector`
```
Vector GetForwardVector()
Get the forward vector of the entity.
```
------

### `SetAbsAngles`
```
void SetAbsAngles(float fPitch, float fYaw, float fRoll)
Set entity pitch, yaw, roll by component.
```
------

### `GetAngles`
```
QAngle GetAngles()

```
------

### `IsPlayer`
```
bool IsPlayer()
Is this entity a player?
```
------

### `IsAlive`
```
bool IsAlive()
Is this entity alive?
```
------

### `SetParent`
```
void SetParent(handle hParent, string pAttachmentname)
Set the parent for this entity.
```
------

### `GetBounds`
```
table GetBounds()
Get a table containing the 'Mins' & 'Maxs' vector bounds, centered on object.
```
------

### `AddEffects`
```
void AddEffects(int nFlags)
AddEffects( int ): Adds the render effect flag.
```
------

### `GetBoundingMins`
```
Vector GetBoundingMins()
Get a vector containing min bounds, centered on object.
```
------

### `EyePosition`
```
Vector EyePosition()
Get vector to eye position - absolute coords.
```
------

### `SetAngles`
```
void SetAngles(float fPitch, float fYaw, float fRoll)
Set entity pitch, yaw, roll by component.
```
------

### `SetGravity`
```
void SetGravity(float flGravity)
Set PLAYER gravity, ignored for objects.
```
------

### `GetOwnerEntity`
```
handle GetOwnerEntity()
Get the owner entity, if there is one
```
------

### `FirstMoveChild`
```
handle FirstMoveChild()

```
------

### `SetFriction`
```
void SetFriction(float flFriction)
Set PLAYER friction, ignored for objects.
```
------

### `GetLocalOrigin`
```
Vector GetLocalOrigin()
Get entity local origin as a Vector
```
------

### `SetOrigin`
```
void SetOrigin(Vector v)

```
------

### `GetMoveParent`
```
handle GetMoveParent()
If in hierarchy, retrieves the entity's parent.
```
------

### `GetRootMoveParent`
```
handle GetRootMoveParent()
If in hierarchy, walks up the hierarchy to find the root parent.
```
------

### `StopSound`
```
void StopSound(string soundname)
Stops a named sound playing from this entity.
```
------

### `SetOwner`
```
void SetOwner(handle pOwner)
Sets this entity's owner
```
------

### `GetMass`
```
float GetMass()
Get the mass of an entity. (returns 0 if it doesn't have a physics object)
```
------

### `ValidatePrivateScriptScope`
```
void ValidatePrivateScriptScope()
Validates the private script scope and creates it if one doesn't exist.
```
------

### `GetSoundDuration`
```
float GetSoundDuration(string soundname, string actormodel)
Returns float duration of the sound. Takes soundname and optional actormodelname.
```
------

### `SetAbsOrigin`
```
void SetAbsOrigin(Vector origin)

```
------

### `GetTeam`
```
int GetTeam()
Get the team number of this entity.
```
------

### `SetTeam`
```
void SetTeam(int iTeamNum)

```
------

### `FollowEntity`
```
void FollowEntity(handle hEnt, bool bBoneMerge)
hEntity to follow, bool bBoneMerge
```
------
