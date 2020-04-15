# globals

## Methods

### `UnloadSpawnGroup`
```
void UnloadSpawnGroup(string)
Unload a spawn group by name
```
------

### `MakeStringToken`
```
int MakeStringToken(string)
Checks to see if the given hScript is a valid entity
```
------

### `InitLogFile`
```
void InitLogFile(string, string)
InitLogFile is deprecated. Print to the console for logging instead.
```
------

### `GetFrameCount`
```
int GetFrameCount()
Returns the engines current frame count
```
------

### `IsValidEntity`
```
bool IsValidEntity(handle)
Checks to see if the given hScript is a valid entity
```
------

### `LoadKeyValuesFromString`
```
table LoadKeyValuesFromString(string)
Creates a table from the specified keyvalues string
```
------

### `ListenToGameEvent`
```
int ListenToGameEvent(string, handle, handle)
Register as a listener for a game event from script.
```
------

### `CalcDistanceBetweenEntityOBB`
```
float CalcDistanceBetweenEntityOBB(handle, handle)
Compute the distance between two entity OBB. A negative return value indicates an input error. A return value of zero indicates that the OBBs are overlapping.
```
------

### `TraceHull`
```
bool TraceHull(handle)
Pass table - Inputs: start, end, min, max, mask, ignore  -- outputs: pos, fraction, hit, enthit, startsolid
```
------

### `StartSoundEvent`
```
void StartSoundEvent(string, handle)
Start a sound event
```
------

### `EntIndexToHScript`
```
handle EntIndexToHScript(int)
Turn an entity index integer to an HScript representing that entity's script instance.
```
------

### `StartSoundEventReliable`
```
void StartSoundEventReliable(string, handle)
Start a sound event with reliable delivery
```
------

### `IsInToolsMode`
```
bool IsInToolsMode()
Returns true if this is lua running within tools mode.
```
------

### `IsClient`
```
bool IsClient()
Returns true if this is lua running from the client.dll.
```
------

### `StopEffect`
```
void StopEffect(handle, string)
Pass entity and effect name
```
------

### `AxisAngleToQuaternion`
```
Quaternion AxisAngleToQuaternion(Vector, float)
(vector,float) constructs a quaternion representing a rotation by angle around the specified vector axis
```
------

### `Say`
```
void Say(handle, string, bool)
Have Entity say string, and teamOnly or not
```
------

### `UTIL_ResetMessageTextAll`
```
void UTIL_ResetMessageTextAll()
Clear all message text from all clients.
```
------

### `DebugDrawBoxDirection`
```
void DebugDrawBoxDirection(Vector, Vector, Vector, Vector, Vector, float, float)
Draw a debug forward box (cent, min, max, forward, vRgb, a, duration)
```
------

### `DebugDrawSphere`
```
void DebugDrawSphere(Vector, Vector, float, float, bool, float)
Draw a debug sphere (center, vRgb, a, rad, ztest, duration)
```
------

### `IsServer`
```
bool IsServer()
Returns true if this is lua running from the server.dll.
```
------

### `CreateTriggerRadiusApproximate`
```
handle CreateTriggerRadiusApproximate(Vector, float)
CreateTriggerRadiusApproximate( vecOrigin, flRadius ) : Creates and returns an AABB trigger thats bigger than the radius provided
```
------

### `UTIL_ResetMessageText`
```
void UTIL_ResetMessageText(int)
Clear all message text on one client.
```
------

### `UTIL_MessageText_WithContext`
```
void UTIL_MessageText_WithContext(int, string, int, int, int, int, handle)
Sends colored text to one client. (Valid context keys: player_id, value, team_id)
```
------

### `Warning`
```
void Warning(string)
Print a warning
```
------

### `StartSoundEventUnreliable`
```
void StartSoundEventUnreliable(string, handle)
Start a sound event with optional delivery
```
------

### `DebugDrawClear`
```
void DebugDrawClear()
Try to clear all the debug overlay info
```
------

### `cvar_getf`
```
float cvar_getf(string)
Gets the value of the given cvar, as a float.
```
------

### `RandomInt`
```
int RandomInt(int, int)
Get a random int within a range
```
------

### `UTIL_MessageTextAll_WithContext`
```
void UTIL_MessageTextAll_WithContext(string, int, int, int, int, handle)
Sends colored text to all clients. (Valid context keys: player_id, value, team_id)
```
------

### `cvar_setf`
```
bool cvar_setf(string, float)
Sets the value of the given cvar, as a float.
```
------

### `SendToConsole`
```
void SendToConsole(string)
Send a string to the console as a client command
```
------

### `UTIL_MessageText`
```
void UTIL_MessageText(int, string, int, int, int, int)
Sends colored text to one client.
```
------

### `EmitSoundOn`
```
void EmitSoundOn(string, handle)
Play named sound on Entity
```
------

### `UTIL_MessageTextAll`
```
void UTIL_MessageTextAll(string, int, int, int, int)
Sends colored text to all clients.
```
------

### `SpawnEntityListFromTableAsynchronous`
```
int SpawnEntityListFromTableAsynchronous(handle, handle)
Asynchronously spawn an entity group from a list of spawn tables. A callback will be triggered when the spawning is complete
```
------

### `VectorToAngles`
```
QAngle VectorToAngles(Vector)
Get Qangles (with no roll) for a Vector.
```
------

### `IsDedicatedServer`
```
bool IsDedicatedServer()
Returns true if this server is a dedicated server.
```
------

### `SplineVectors`
```
Vector SplineVectors(Vector, Vector, float)
(vector,vector,float) very basic interpolation of v0 to v1 over t on [0,1]
```
------

### `CreateTrigger`
```
handle CreateTrigger(Vector, Vector, Vector)
CreateTrigger( vecMin, vecMax ) : Creates and returns an AABB trigger
```
------

### `ShowMessage`
```
void ShowMessage(string)
Print a hud message on all clients
```
------

### `Msg`
```
void Msg(string)
Print a message
```
------

### `GetActiveSpawnGroupHandle`
```
int GetActiveSpawnGroupHandle()
Returns the currently active spawn group handle
```
------

### `AngleDiff`
```
float AngleDiff(float, float)
Returns the number of degrees difference between two yaw angles
```
------

### `UnloadSpawnGroupByHandle`
```
void UnloadSpawnGroupByHandle(int)
Unload a spawn group by handle
```
------

### `rr_AddDecisionRule`
```
bool rr_AddDecisionRule(handle)
Add a rule to the decision database.
```
------

### `DebugBreak`
```
void DebugBreak()
Breaks in the debugger
```
------

### `CreateSceneEntity`
```
handle CreateSceneEntity(string)
Create a scene entity to play the specified scene.
```
------

### `RemoveSpawnGroupFilterProxy`
```
void RemoveSpawnGroupFilterProxy(string)
Remove the C proxy for a script-based spawn group filter
```
------

### `LoadKeyValues`
```
table LoadKeyValues(string)
Creates a table from the specified keyvalues text file
```
------

### `RegisterSpawnGroupFilterProxy`
```
void RegisterSpawnGroupFilterProxy(string)
Create a C proxy for a script-based spawn group filter
```
------

### `TraceLine`
```
bool TraceLine(handle)
Pass table - Inputs: startpos, endpos, mask, ignore  -- outputs: pos, fraction, hit, enthit, startsolid
```
------

### `SpawnEntityFromTableSynchronous`
```
handle SpawnEntityFromTableSynchronous(string, handle)
Synchronously spawns a single entity from a table
```
------

### `DoIncludeScript`
```
bool DoIncludeScript(string, handle)
Execute a script (internal)
```
------

### `SendToServerConsole`
```
void SendToServerConsole(string)
Send a string to the console as a server command
```
------

### `ExponentialDecay`
```
float ExponentialDecay(float, float, float)
Smooth curve decreasing slower as it approaches zero
```
------

### `GetListenServerHost`
```
handle GetListenServerHost()
Get the local player on a listen server.
```
------

### `SetQuestName`
```
void SetQuestName(string)
Set the current quest name.
```
------

### `StopListeningToGameEvent`
```
bool StopListeningToGameEvent(int)
Stop listening to a particular game event.
```
------

### `RotationDeltaAsAngularVelocity`
```
Vector RotationDeltaAsAngularVelocity(QAngle, QAngle)
converts delta QAngle to an angular velocity Vector
```
------

### `FireEntityIOInputVec`
```
void FireEntityIOInputVec(ehandle, string, Vector)
Fire Entity's Action Input with passed Vector - you own the memory
```
------

### `DoEntFire`
```
void DoEntFire(string, string, string, float, handle, handle)
#EntFire:Generate and entity i/o event
```
------

### `IsMarkedForDeletion`
```
bool IsMarkedForDeletion(handle)
Returns true if the entity is valid and marked for deletion.
```
------

### `TraceCollideable`
```
bool TraceCollideable(handle)
Pass table - Inputs: start, end, ent, (optional mins, maxs) -- outputs: pos, fraction, hit, startsolid, normal
```
------

### `DoEntFireByInstanceHandle`
```
void DoEntFireByInstanceHandle(handle, string, string, float, handle, handle)
#EntFireByHandle:Generate and entity i/o event
```
------

### `SetOpvarFloatAll`
```
void SetOpvarFloatAll(string, string, string, float)
Sets an opvar value for all players
```
------

### `PrecacheEntityListFromTable`
```
void PrecacheEntityListFromTable(handle, handle)
Precache a list of entity KeyValues tables
```
------

### `LocalTime`
```
table LocalTime()
Get the current local time
```
------

### `RotatePosition`
```
Vector RotatePosition(Vector, QAngle, Vector)
Rotate a Vector around a point.
```
------

### `GetMapName`
```
string GetMapName()
Get the name of the map.
```
------

### `PrintLinkedConsoleMessage`
```
void PrintLinkedConsoleMessage(string, string)
Print a console message with a linked console command
```
------

### `DoUniqueString`
```
string DoUniqueString(string)
#UniqueString:Generate a string guaranteed to be unique across the life of the script VM, with an optional root string. Useful for adding data to tables when not sure what keys are already in use in that table.
```
------

### `CancelEntityIOEvents`
```
void CancelEntityIOEvents(ehandle)
Create all I/O events for a particular entity
```
------

### `SetRenderingEnabled`
```
void SetRenderingEnabled(ehandle, bool)
Set rendering on/off for an ehandle
```
------

### `PlayerInstanceFromIndex`
```
handle PlayerInstanceFromIndex(int)
Get a script instance of a player by index.
```
------

### `SetOpvarFloatPlayer`
```
void SetOpvarFloatPlayer(string, string, string, float, handle)
Sets an opvar value for a single player
```
------

### `DebugDrawLine_vCol`
```
void DebugDrawLine_vCol(Vector, Vector, Vector, bool, float)
Draw a debug line using color vec (start, end, vRgb, a, ztest, duration)
```
------

### `UTIL_Remove`
```
void UTIL_Remove(handle)
Removes the specified entity
```
------

### `DebugDrawText`
```
void DebugDrawText(Vector, string, bool, float)
Draw text in 3d (origin, text, bViewCheck, duration)
```
------

### `StopSoundOn`
```
void StopSoundOn(string, handle)
Stop named sound on Entity
```
------

### `rr_CommitAIResponse`
```
bool rr_CommitAIResponse(handle, handle)
Commit the result of QueryBestResponse back to the given entity to play. Call with params (entity, airesponse)
```
------

### `GetMaxOutputDelay`
```
float GetMaxOutputDelay(ehandle, string)
Get the longest delay for all events attached to an output
```
------

### `CrossVectors`
```
Vector CrossVectors(Vector, Vector)
(vector,vector) cross product between two vectors
```
------

### `rr_QueryBestResponse`
```
bool rr_QueryBestResponse(handle, handle, handle)
Params: (entity, query) : tests 'query' against entity's response system and returns the best response found (or null if none found).
```
------

### `ReloadMOTD`
```
void ReloadMOTD()
Reloads the MotD file
```
------

### `DebugDrawCircle`
```
void DebugDrawCircle(Vector, Vector, float, float, bool, float)
Draw a debug circle (center, vRgb, a, rad, ztest, duration)
```
------

### `DebugDrawLine`
```
void DebugDrawLine(Vector, Vector, int, int, int, bool, float)
Draw a debug overlay line (origin, target, r, g, b, ztest, duration)
```
------

### `GetPhysAngularVelocity`
```
Vector GetPhysAngularVelocity(handle)
Get Angular Velocity for VPHYS or normal object. Returns a vector of the axis of rotation, multiplied by the degrees of rotation per second.
```
------

### `FireGameEventLocal`
```
void FireGameEventLocal(string, handle)
Fire a game event without broadcasting to the client.
```
------

### `rr_GetResponseTargets`
```
handle rr_GetResponseTargets()
Retrieve a table of all available expresser targets, in the form { name : handle, name: handle }.
```
------

### `DebugScreenTextPretty`
```
void DebugScreenTextPretty(float, float, int, string, int, int, int, int, float, string, int, bool)
Draw pretty debug text (x, y, lineOffset, text, r, g, b, a, duration, font, size, bBold)
```
------

### `DebugDrawScreenTextLine`
```
void DebugDrawScreenTextLine(float, float, int, string, int, int, int, int, float)
Draw text with a line offset (x, y, lineOffset, text, r, g, b, a, duration)
```
------

### `PrecacheEntityFromTable`
```
void PrecacheEntityFromTable(string, handle, handle)
Precache an entity from KeyValues in table
```
------

### `ScreenShake`
```
void ScreenShake(Vector, float, float, float, float, int, bool)
Start a screenshake with the following parameters. vecCenter, flAmplitude, flFrequency, flDuration, flRadius, eCommand( SHAKE_START = 0, SHAKE_STOP = 1 ), bAirShake
```
------

### `UTIL_RemoveImmediate`
```
void UTIL_RemoveImmediate(handle)
Immediately removes the specified entity
```
------

### `SetPhysAngularVelocity`
```
void SetPhysAngularVelocity(handle, Vector)
Set Angular Velocity for VPHYS or normal object, from a vector of the axis of rotation, multiplied by the degrees of rotation per second.
```
------

### `SetQuestPhase`
```
void SetQuestPhase(int)
Set the current quest phase.
```
------

### `FireGameEvent`
```
void FireGameEvent(string, handle)
Fire a game event.
```
------

### `DebugDrawBox`
```
void DebugDrawBox(Vector, Vector, Vector, int, int, int, int, float)
Draw a debug overlay box (origin, mins, maxs, forward, r, g, b, a, duration )
```
------

### `FrameTime`
```
float FrameTime()
Get the time spent on the server in the last frame
```
------

### `FireEntityIOInputString`
```
void FireEntityIOInputString(ehandle, string, string)
Fire Entity's Action Input with passed String - you own the memory
```
------

### `SpawnEntityListFromTableSynchronous`
```
handle SpawnEntityListFromTableSynchronous(handle)
Synchronously spawn an entity group from a list of spawn tables.
```
------

### `PrecacheModel`
```
void PrecacheModel(string, handle)
( modelName, context ) - Manually precache a single model
```
------

### `StartSoundEventFromPositionUnreliable`
```
void StartSoundEventFromPositionUnreliable(string, Vector)
Start a sound event from position with optional delivery
```
------

### `StartSoundEventFromPositionReliable`
```
void StartSoundEventFromPositionReliable(string, Vector)
Start a sound event from position with reliable delivery
```
------

### `StartSoundEventFromPosition`
```
void StartSoundEventFromPosition(string, Vector)
Start a sound event from position
```
------

### `StopSoundEvent`
```
void StopSoundEvent(string, handle)
Stops a sound event with optional delivery
```
------

### `CalcClosestPointOnEntityOBB`
```
Vector CalcClosestPointOnEntityOBB(handle, Vector)
Compute the closest point on the OBB of an entity.
```
------

### `CreateDamageInfo`
```
handle CreateDamageInfo(handle, handle, Vector, Vector, float, int)
(hInflictor, hAttacker, flDamage) - Allocate a damageinfo object, used as an argument to TakeDamage(). Call DestroyDamageInfo( hInfo ) to free the object.
```
------

### `DestroyDamageInfo`
```
void DestroyDamageInfo(handle)
Free a damageinfo object that was created with CreateDamageInfo().
```
------

### `EmitSoundOnClient`
```
void EmitSoundOnClient(string, handle)
Play named sound only on the client for the passed in player
```
------

### `SplineQuaternions`
```
Quaternion SplineQuaternions(Quaternion, Quaternion, float)
(quaternion,quaternion,float) very basic interpolation of v0 to v1 over t on [0,1]
```
------

### `DoScriptAssert`
```
void DoScriptAssert(bool, string)
#ScriptAssert:Asserts the passed in value. Prints out a message and brings up the assert dialog.
```
------

### `GetPhysVelocity`
```
Vector GetPhysVelocity(handle)
Get Velocity for VPHYS or normal object
```
------

### `FireEntityIOInputNameOnly`
```
void FireEntityIOInputNameOnly(ehandle, string)
Fire Entity's Action Input w/no data
```
------

### `CreateEffect`
```
bool CreateEffect(handle)
Pass table - Inputs: entity, effect
```
------

### `ManuallyTriggerSpawnGroupCompletion`
```
void ManuallyTriggerSpawnGroupCompletion(int)
Triggers the creation of entities in a manually-completed spawn group
```
------

### `LerpVectors`
```
Vector LerpVectors(Vector, Vector, float)
(vector,vector,float) lerp between two vectors by a float factor returning new vector
```
------

### `RotateQuaternionByAxisAngle`
```
Quaternion RotateQuaternionByAxisAngle(Quaternion, Vector, float)
(quaternion,vector,float) rotates a quaternion by the specified angle around the specified vector axis
```
------

### `CalcDistanceToLineSegment2D`
```
float CalcDistanceToLineSegment2D(Vector, Vector, Vector)

```
------

### `RandomFloat`
```
float RandomFloat(float, float)
Get a random float within a range
```
------

### `Time`
```
float Time()
Get the current server time
```
------

### `AppendToLogFile`
```
void AppendToLogFile(string, string)
AppendToLogFile is deprecated. Print to the console for logging instead.
```
------

### `SpawnEntityGroupFromTable`
```
bool SpawnEntityGroupFromTable(handle, bool, handle)
Hierarchically spawn an entity group from a set of spawn tables.
```
------

### `RotationDelta`
```
QAngle RotationDelta(QAngle, QAngle)
Find the delta between two QAngles.
```
------

### `PrecacheResource`
```
void PrecacheResource(string, string, handle)
( resourceType, resourcePath, context ) - Manually precache a single resource. Types: "model|model_folder|sound|soundfile|particle|particle_folder"
```
------

### `StopListeningToAllGameEvents`
```
void StopListeningToAllGameEvents(handle)
Stop listening to all game events within a specific context.
```
------

### `RotateOrientation`
```
QAngle RotateOrientation(QAngle, QAngle)
Rotate a QAngle by another QAngle.
```
------

## Enums
```
```
