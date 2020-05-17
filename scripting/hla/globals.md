# globals

## Methods

### `SpawnEntityGroupFromTable`
```
bool SpawnEntityGroupFromTable(handle, bool, handle)
Hierarchically spawn an entity group from a set of spawn tables.
```
------

### `LoadKeyValuesFromString`
```
table LoadKeyValuesFromString(string)
Creates a table from the specified keyvalues string
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

### `StopEffect`
```
void StopEffect(handle, string)
Pass entity and effect name
```
------

### `Say`
```
void Say(handle, string, bool)
Have Entity say string, and teamOnly or not
```
------

### `DebugDrawBoxDirection`
```
void DebugDrawBoxDirection(Vector, Vector, Vector, Vector, Vector, float, float)
Draw a debug forward box (cent, min, max, forward, vRgb, a, duration)
```
------

### `StartSoundEventUnreliable`
```
void StartSoundEventUnreliable(string, handle)
Start a sound event with optional delivery
```
------

### `RandomInt`
```
int RandomInt(int, int)
Get a random int within a range
```
------

### `SendToConsole`
```
void SendToConsole(string)
Send a string to the console as a client command
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

### `Msg`
```
void Msg(string)
Print a message
```
------

### `AnglesToVector`
```
Vector AnglesToVector(QAngle)
Generate a vector given a QAngles
```
------

### `rr_AddDecisionRule`
```
bool rr_AddDecisionRule(handle)
Add a rule to the decision database.
```
------

### `LoadKeyValues`
```
table LoadKeyValues(string)
Creates a table from the specified keyvalues text file
```
------

### `TraceLine`
```
bool TraceLine(handle)
Pass table - Inputs: startpos, endpos, mask, ignore  -- outputs: pos, fraction, hit, enthit, startsolid
```
------

### `ShowMessage`
```
void ShowMessage(string)
Print a hud message on all clients
```
------

### `UnloadSpawnGroup`
```
void UnloadSpawnGroup(string)
Unload a spawn group by name
```
------

### `GetListenServerHost`
```
handle GetListenServerHost()
Get the local player on a listen server.
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

### `UnloadSpawnGroupByHandle`
```
void UnloadSpawnGroupByHandle(int)
Unload a spawn group by handle
```
------

### `PrintLinkedConsoleMessage`
```
void PrintLinkedConsoleMessage(string, string)
Print a console message with a linked console command
```
------

### `MakeStringToken`
```
int MakeStringToken(string)
Checks to see if the given hScript is a valid entity
```
------

### `RotateQuaternionByAxisAngle`
```
Quaternion RotateQuaternionByAxisAngle(Quaternion, Vector, float)
(quaternion,vector,float) rotates a quaternion by the specified angle around the specified vector axis
```
------

### `UTIL_MessageTextAll_WithContext`
```
void UTIL_MessageTextAll_WithContext(string, int, int, int, int, handle)
Sends colored text to all clients. (Valid context keys: player_id, value, team_id)
```
------

### `StopSoundOn`
```
void StopSoundOn(string, handle)
Stop named sound on Entity
```
------

### `ReloadMOTD`
```
void ReloadMOTD()
Reloads the MotD file
```
------

### `TraceCollideable`
```
bool TraceCollideable(handle)
Pass table - Inputs: start, end, ent, (optional mins, maxs) -- outputs: pos, fraction, hit, startsolid, normal
```
------

### `IsInToolsMode`
```
bool IsInToolsMode()
Returns true if this is lua running within tools mode.
```
------

### `SetOpvarFloatPlayer`
```
void SetOpvarFloatPlayer(string, string, string, float, handle)
Sets an opvar value for a single player
```
------

### `UTIL_RemoveImmediate`
```
void UTIL_RemoveImmediate(handle)
Immediately removes the specified entity
```
------

### `SetQuestPhase`
```
void SetQuestPhase(int)
Set the current quest phase.
```
------

### `DebugDrawBox`
```
void DebugDrawBox(Vector, Vector, Vector, int, int, int, int, float)
Draw a debug overlay box (origin, mins, maxs, forward, r, g, b, a, duration )
```
------

### `FireEntityIOInputString`
```
void FireEntityIOInputString(ehandle, string, string)
Fire Entity's Action Input with passed String - you own the memory
```
------

### `CalcClosestPointOnEntityOBB`
```
Vector CalcClosestPointOnEntityOBB(handle, Vector)
Compute the closest point on the OBB of an entity.
```
------

### `UTIL_MessageTextAll`
```
void UTIL_MessageTextAll(string, int, int, int, int)
Sends colored text to all clients.
```
------

### `IsClient`
```
bool IsClient()
Returns true if this is lua running from the client.dll.
```
------

### `CreateTriggerRadiusApproximate`
```
handle CreateTriggerRadiusApproximate(Vector, float)
CreateTriggerRadiusApproximate( vecOrigin, flRadius ) : Creates and returns an AABB trigger thats bigger than the radius provided
```
------

### `GetPhysVelocity`
```
Vector GetPhysVelocity(handle)
Get Velocity for VPHYS or normal object
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

### `CalcDistanceToLineSegment2D`
```
float CalcDistanceToLineSegment2D(Vector, Vector, Vector)

```
------

### `RotationDelta`
```
QAngle RotationDelta(QAngle, QAngle)
Find the delta between two QAngles.
```
------

### `InitLogFile`
```
void InitLogFile(string, string)
InitLogFile is deprecated. Print to the console for logging instead.
```
------

### `IsValidEntity`
```
bool IsValidEntity(handle)
Checks to see if the given hScript is a valid entity
```
------

### `TraceHull`
```
bool TraceHull(handle)
Pass table - Inputs: start, end, min, max, mask, ignore  -- outputs: pos, fraction, hit, enthit, startsolid
```
------

### `SetOpvarFloatAll`
```
void SetOpvarFloatAll(string, string, string, float)
Sets an opvar value for all players
```
------

### `AxisAngleToQuaternion`
```
Quaternion AxisAngleToQuaternion(Vector, float)
(vector,float) constructs a quaternion representing a rotation by angle around the specified vector axis
```
------

### `UTIL_ResetMessageTextAll`
```
void UTIL_ResetMessageTextAll()
Clear all message text from all clients.
```
------

### `DebugDrawSphere`
```
void DebugDrawSphere(Vector, Vector, float, float, bool, float)
Draw a debug sphere (center, vRgb, a, rad, ztest, duration)
```
------

### `Warning`
```
void Warning(string)
Print a warning
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

### `cvar_setf`
```
bool cvar_setf(string, float)
Sets the value of the given cvar, as a float.
```
------

### `EmitSoundOn`
```
void EmitSoundOn(string, handle)
Play named sound on Entity
```
------

### `SpawnEntityListFromTableAsynchronous`
```
int SpawnEntityListFromTableAsynchronous(handle, handle)
Asynchronously spawn an entity group from a list of spawn tables. A callback will be triggered when the spawning is complete
```
------

### `AngleDiff`
```
float AngleDiff(float, float)
Returns the number of degrees difference between two yaw angles
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

### `UTIL_ResetMessageText`
```
void UTIL_ResetMessageText(int)
Clear all message text on one client.
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

### `UTIL_MessageText_WithContext`
```
void UTIL_MessageText_WithContext(int, string, int, int, int, int, handle)
Sends colored text to one client. (Valid context keys: player_id, value, team_id)
```
------

### `SetQuestName`
```
void SetQuestName(string)
Set the current quest name.
```
------

### `UTIL_MessageText`
```
void UTIL_MessageText(int, string, int, int, int, int)
Sends colored text to one client.
```
------

### `PrecacheEntityListFromTable`
```
void PrecacheEntityListFromTable(handle, handle)
Precache a list of entity KeyValues tables
```
------

### `CreateTrigger`
```
handle CreateTrigger(Vector, Vector, Vector)
CreateTrigger( vecMin, vecMax ) : Creates and returns an AABB trigger
```
------

### `GetFrameCount`
```
int GetFrameCount()
Returns the engines current frame count
```
------

### `DoEntFireByInstanceHandle`
```
void DoEntFireByInstanceHandle(handle, string, string, float, handle, handle)
#EntFireByHandle:Generate and entity i/o event
```
------

### `DoUniqueString`
```
string DoUniqueString(string)
#UniqueString:Generate a string guaranteed to be unique across the life of the script VM, with an optional root string. Useful for adding data to tables when not sure what keys are already in use in that table.
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

### `StartSoundEvent`
```
void StartSoundEvent(string, handle)
Start a sound event
```
------

### `DebugScreenTextPretty`
```
void DebugScreenTextPretty(float, float, int, string, int, int, int, int, float, string, int, bool)
Draw pretty debug text (x, y, lineOffset, text, r, g, b, a, duration, font, size, bBold)
```
------

### `CrossVectors`
```
Vector CrossVectors(Vector, Vector)
(vector,vector) cross product between two vectors
```
------

### `RotateOrientation`
```
QAngle RotateOrientation(QAngle, QAngle)
Rotate a QAngle by another QAngle.
```
------

### `CalcDistanceBetweenEntityOBB`
```
float CalcDistanceBetweenEntityOBB(handle, handle)
Compute the distance between two entity OBB. A negative return value indicates an input error. A return value of zero indicates that the OBBs are overlapping.
```
------

### `StopListeningToAllGameEvents`
```
void StopListeningToAllGameEvents(handle)
Stop listening to all game events within a specific context.
```
------

### `DebugDrawLine`
```
void DebugDrawLine(Vector, Vector, int, int, int, bool, float)
Draw a debug overlay line (origin, target, r, g, b, ztest, duration)
```
------

### `PrecacheResource`
```
void PrecacheResource(string, string, handle)
( resourceType, resourcePath, context ) - Manually precache a single resource. Types: "model|model_folder|sound|soundfile|particle|particle_folder"
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

### `FireEntityIOInputNameOnly`
```
void FireEntityIOInputNameOnly(ehandle, string)
Fire Entity's Action Input w/no data
```
------

### `AppendToLogFile`
```
void AppendToLogFile(string, string)
AppendToLogFile is deprecated. Print to the console for logging instead.
```
------

### `RandomFloat`
```
float RandomFloat(float, float)
Get a random float within a range
```
------

### `ScreenShake`
```
void ScreenShake(Vector, float, float, float, float, int, bool)
Start a screenshake with the following parameters. vecCenter, flAmplitude, flFrequency, flDuration, flRadius, eCommand( SHAKE_START = 0, SHAKE_STOP = 1 ), bAirShake
```
------

### `ListenToGameEvent`
```
int ListenToGameEvent(string, handle, handle)
Register as a listener for a game event from script.
```
------

### `SpawnEntityFromTableAsynchronous`
```
void SpawnEntityFromTableAsynchronous(string, handle, handle, handle)
Asynchronously spawns a single entity from a table
```
------

### `FrameTime`
```
float FrameTime()
Get the time spent on the server in the last frame
```
------

### `FireGameEvent`
```
void FireGameEvent(string, handle)
Fire a game event.
```
------

### `SplineQuaternions`
```
Quaternion SplineQuaternions(Quaternion, Quaternion, float)
(quaternion,quaternion,float) very basic interpolation of v0 to v1 over t on [0,1]
```
------

### `EmitSoundOnClient`
```
void EmitSoundOnClient(string, handle)
Play named sound only on the client for the passed in player
```
------

### `SpawnEntityListFromTableSynchronous`
```
handle SpawnEntityListFromTableSynchronous(handle)
Synchronously spawn an entity group from a list of spawn tables.
```
------

### `Time`
```
float Time()
Get the current server time
```
------

### `PrecacheModel`
```
void PrecacheModel(string, handle)
( modelName, context ) - Manually precache a single model
```
------

### `CreateDamageInfo`
```
handle CreateDamageInfo(handle, handle, Vector, Vector, float, int)
(hInflictor, hAttacker, flDamage) - Allocate a damageinfo object, used as an argument to TakeDamage(). Call DestroyDamageInfo( hInfo ) to free the object.
```
------

### `GetActiveSpawnGroupHandle`
```
int GetActiveSpawnGroupHandle()
Returns the currently active spawn group handle
```
------

### `PrecacheEntityFromTable`
```
void PrecacheEntityFromTable(string, handle, handle)
Precache an entity from KeyValues in table
```
------

### `StopSoundEvent`
```
void StopSoundEvent(string, handle)
Stops a sound event with optional delivery
```
------

### `StartSoundEventFromPositionUnreliable`
```
void StartSoundEventFromPositionUnreliable(string, Vector)
Start a sound event from position with optional delivery
```
------

### `RemoveSpawnGroupFilterProxy`
```
void RemoveSpawnGroupFilterProxy(string)
Remove the C proxy for a script-based spawn group filter
```
------

### `DestroyDamageInfo`
```
void DestroyDamageInfo(handle)
Free a damageinfo object that was created with CreateDamageInfo().
```
------

### `DoScriptAssert`
```
void DoScriptAssert(bool, string)
#ScriptAssert:Asserts the passed in value. Prints out a message and brings up the assert dialog.
```
------

### `StartSoundEventFromPosition`
```
void StartSoundEventFromPosition(string, Vector)
Start a sound event from position
```
------

### `SetPhysAngularVelocity`
```
void SetPhysAngularVelocity(handle, Vector)
Set Angular Velocity for VPHYS or normal object, from a vector of the axis of rotation, multiplied by the degrees of rotation per second.
```
------

### `DebugDrawScreenTextLine`
```
void DebugDrawScreenTextLine(float, float, int, string, int, int, int, int, float)
Draw text with a line offset (x, y, lineOffset, text, r, g, b, a, duration)
```
------

### `DebugDrawText`
```
void DebugDrawText(Vector, string, bool, float)
Draw text in 3d (origin, text, bViewCheck, duration)
```
------

### `RegisterSpawnGroupFilterProxy`
```
void RegisterSpawnGroupFilterProxy(string)
Create a C proxy for a script-based spawn group filter
```
------

### `GetPhysAngularVelocity`
```
Vector GetPhysAngularVelocity(handle)
Get Angular Velocity for VPHYS or normal object. Returns a vector of the axis of rotation, multiplied by the degrees of rotation per second.
```
------

### `DebugDrawLine_vCol`
```
void DebugDrawLine_vCol(Vector, Vector, Vector, bool, float)
Draw a debug line using color vec (start, end, vRgb, a, ztest, duration)
```
------

### `GetMaxOutputDelay`
```
float GetMaxOutputDelay(ehandle, string)
Get the longest delay for all events attached to an output
```
------

### `DebugDrawCircle`
```
void DebugDrawCircle(Vector, Vector, float, float, bool, float)
Draw a debug circle (center, vRgb, a, rad, ztest, duration)
```
------

### `rr_CommitAIResponse`
```
bool rr_CommitAIResponse(handle, handle)
Commit the result of QueryBestResponse back to the given entity to play. Call with params (entity, airesponse)
```
------

### `UTIL_Remove`
```
void UTIL_Remove(handle)
Removes the specified entity
```
------

### `rr_QueryBestResponse`
```
bool rr_QueryBestResponse(handle, handle, handle)
Params: (entity, query) : tests 'query' against entity's response system and returns the best response found (or null if none found).
```
------

### `CancelEntityIOEvents`
```
void CancelEntityIOEvents(ehandle)
Create all I/O events for a particular entity
```
------

### `GetMapName`
```
string GetMapName()
Get the name of the map.
```
------

### `ExponentialDecay`
```
float ExponentialDecay(float, float, float)
Smooth curve decreasing slower as it approaches zero
```
------

### `StartSoundEventFromPositionReliable`
```
void StartSoundEventFromPositionReliable(string, Vector)
Start a sound event from position with reliable delivery
```
------

### `IsServer`
```
bool IsServer()
Returns true if this is lua running from the server.dll.
```
------
