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
ACT_MELEE_VM_RELOAD	836

ACT_VM_PICKUP_CHARGING_RIFLE	1725

ACT_RUN_SCARED	112

ACT_MP_PRIMARY_GRENADE1_IDLE	696

ACT_MP_RELOAD_SWIM	542

ACT_TURN_RIGHT	43

ACT_VM_FIDGET_SNIPER_LAYER	1793

ACT_SLAM_DETONATOR_STICKWALL_DRAW	260

ACT_CROUCHIDLE_SHOTGUN	1523

ACT_MP_ATTACK_CROUCH_PRIMARY	570

ACT_STARTDYING	429

AE_IK_SET_CHAIN_BLEND_AMOUNT	180

ACT_VM_PICKUP_CLIPIN	1651

ACT_CSGO_FIRE_SECONDARY_OPT_1	1000

ACT_METROPOLICE_DEPLOY_MANHACK	1929

ACT_SCRIPTED_SEQ_POST_IDLE_E	1869

ACT_MP_GESTURE_VC_THUMBSUP_BUILDING	796

ACT_VM_LOWERED_TO_IDLE	215

ACT_VM_PICKUP_CLIPIN_SMG	1749

ACT_SCRIPT_CUSTOM_24	935

ACT_MELEE_VM_PULLBACK	833

AE_CL_ADD_PARTICLE_EFFECT_CP	35

ACT_ALYX_PICKUP_RACK	2015

ACT_MP_RELOAD_CROUCH_LOOP	540

AE_ANTLIONGUARD_SHOVE_PHYSOBJECT	340

ACT_STRIDER_FLICKR	1912

ACT_PRIMARY_VM_PULLBACK	811

AE_STRIDER_STOMPHITL	266

ACT_PRIMARYATTACK_SHOTGUN	1526

ACT_MP_GESTURE_VC_NODYES_SECONDARY	773

ACT_VM_RELOAD_DUAL_PISTOL	1681

ACT_MP_RELOAD_STAND_PRIMARY_END	576

AE_ACTION_PREVENT_DODGE	145

ACT_RANGE_ATTACK_HMG1	277

ACT_DEPLOY	471

ACT_MP_AIRWALK_ITEM1	646

AE_CL_ENABLE_BODYGROUP	38

ACT_MP_ATTACK_STAND_PRIMARY	568

AE_ZOMBIE_ATTACK_RIGHT	197

ACT_WALK_INJURED_SNIPER	1576

AE_CROW_FLY	320

ACT_VM_DRYFIRE_SILENCED	479

ACT_DIE_STANDING	411

ACT_IDLE_ANGRY	77

ACT_MP_SECONDARY_GRENADE1_IDLE	702

ACT_ITEM2_VM_IDLE	865

ACT_BUSY_SIT_CHAIR_EXIT	392

ACT_DIE_CROUCH_HEADSHOT	991

ACT_VM_RELEASE	220

AE_SCANNER_CLOSED	272

BURST	5

DMG_DIRECT	268435456

AE_NPC_WEAPON_SET_SEQUENCE_NAME	9

ACT_STRIDER_DEPLOYRA1	1904

ACT_SCRIPT_CUSTOM_16	927

ACT_PRIMARYATTACK_SMG	1606

ACT_RUN_CROUCH_AIM	13

AE_MANHACK_PACKED	287

ACT_MP_RELOAD_CROUCH_SECONDARY_END	610

ACT_VM_UNUSABLE_TO_USABLE	806

ACT_STRIDER_FLICKL	1911

ACT_RANGE_ATTACK_TRIPWIRE	287

ACT_ARM	71

ACT_OBJ_DETERIORATING	469

AE_CHARGER_POUND_IMPACT	74

ACT_MP_GESTURE_VC_HANDMOUTH_PDA	799

ACT_DIE_BACKSIDE	404

ACT_PDA_VM_LOWERED_TO_IDLE	851

ACT_FLINCH_RIGHTLEG	124

ACT_VM_RECOIL3	218

ACT_MP_ATTACK_STAND_SECONDARYFIRE	524

ACT_SLAM_STICKWALL_DETONATOR_HOLSTER	231

ACT_MP_GESTURE_VC_NODNO_ITEM1	786

AE_FASTZOMBIE_CLIMB_RIGHT	314

ACT_IDLE_SNIPER_ZOOMED	1578

ACT_DROP_WEAPON	73

ACT_MP_STAND_SECONDARY	590

ACT_VM_SWINGMISS	211

ACT_RANGE_ATTACK_AUTOGUN	882

ACT_IDLE_SNIPER	1567

ACT_ITEM2_VM_LOWERED_TO_IDLE	873

ACT_MP_AIRWALK_SECONDARY	594

ACT_CSGO_DEPLOY	1007

ACT_FLINCH_HEAD	118

ACT_WALK_AIM	7

ACT_MP_RUN_MELEE	623

ACT_CLIMB_DOWN	34

ACT_OVERLAY_SHIELD_ATTACK	448

ACT_HUNTER_FLINCH_W	1960

ACT_PRIMARY_VM_DRYFIRE	815

ACT_SCRIPTED_SEQ_ENTRY_A	1851

AE_POISONHEADCRAB_FLINCH_HOP	306

ACT_LEANWALL_RIGHT_ENTER	1849

ACT_HUNTER_FOUND_ENEMY_ACK	1949

ACT_RELOAD_PUMPSHOTGUN_END	1544

AE_MARINE_RELOAD_SOUND_C	52

ACT_CROUCHIDLE_FIRSTAIDKIT	1609

ACT_CSGO_RELOAD	1002

ACT_MP_WALK_PRIMARY	558

RELOAD_NPC	7

ACT_STEP_FORE	144

ACT_SLAM_TRIPMINE_DRAW	251

ACT_MP_JUMP_MELEE	627

ACT_MP_ATTACK_STAND_POSTFIRE	549

ACT_OVERLAY_SHIELD_UP_IDLE	447

ACT_VICTORY_DANCE	113

ACT_FLINCH_STOMACH	120

ACT_RUN	10

AE_STRIDER_SHOOTCANNON	260

MELEE_HIT_WORLD	10

ACT_HUNTER_CHARGE_RUN	1951

ACT_GESTURE_RANGE_ATTACK_SNIPER_RIFLE	312

ACT_BUSY_LEAN_LEFT	381

ACT_GRABBITYGLOVES_RELEASE	956

ACT_MP_CROUCHWALK	511

ACT_SCRIPT_CUSTOM_4	915

AE_REVIVER_FINISH_SUBMERGE	215

AE_ANTLIONGUARD_VOICE_PAIN	347

AE_HEADCRAB_SMOKE_BOMB	376

ACT_JUMP_AUTOGUN	883

ACT_RUN_INJURED_GREN	1554

ACT_VM_DRYFIRE	196

ACT_SLAM_STICKWALL_ND_DRAW	233

ACT_WALK_GREN	1550

ACT_SCRIPTED_SEQ_POST_IDLE_B	1857

ACT_RUN_CALM_SNIPER	1575

ACT_VM_RELOAD_EMPTY_CLIPIN_PISTOL_LAYER	1717

AE_CL_CLOTH_ATTR	183

ACT_MP_CROUCHWALK_ITEM2	664

AE_ANTLIONGUARD_VOICE_SCRATCH	349

ACT_SPRAY	908

ACT_IDLE_INJURED_SNIPER_MILITARYZOOMED	1587

ACT_VM_SECONDARYATTACK	194

ACT_VM_PICKUP_RIFLE_LAYER	1722

AE_WEAPON_MISSILE_FIRE	118

ACT_RUN_CROUCH_GREN	1551

ACT_RUN_AIM_PISTOL	367

DMG_PREVENT_PHYSICS_FORCE	2048

ACT_VM_RELOAD_EMPTY_SMG	1761

AE_ZOMBIE_ALERTSOUND	209

ACT_IDLE	1

ACT_DROP_WEAPON_SHOTGUN	74

ACT_RUN_CROUCH	12

ACT_PDA_VM_RELOAD	847

AE_ANTLION_CLOSE_WINGS	364

ACT_SECONDARY_VM_PRIMARYATTACK	823

ACT_ITEM1_VM_SECONDARYATTACK	857

ACT_ITEM2_VM_SECONDARYATTACK	868

ACT_VM_SHOOT_SMG_LAYER	1756

ACT_FIRE_START	436

ACT_TURN	462

ACT_MP_SECONDARY_GRENADE2_DRAW	704

ACT_RANGE_ATTACK_PISTOL	284

ACT_STRIDER_LOOKR	1903

AE_STRIDER_FLICKL	268

ACT_VM_SPRINT_IDLE	434

ACT_ITEM2_VM_RELOAD	869

ACT_CROUCHING_SHIELD_UP_IDLE	457

ACT_MP_STAND_ITEM2	659

ACT_HEADCRAB_BURROW_OUT	1809

ACT_SLAM_STICKWALL_ATTACH2	227

ACT_MP_CROUCH_DEPLOYED	506

ACT_MP_GESTURE_VC_FISTPUMP_BUILDING	795

ACT_HUNTER_MELEE_ATTACK1_VS_PLAYER	1945

ACT_ANTLIONGUARD_PEEK_ENTER	1988

ACT_VM_PICKUP_SMG_LAYER	1748

AE_HEADCRAB_JUMPATTACK_BECOME_RAGDOLL	300

ACT_VM_PICKUP_DUAL_PISTOL_LAYER	1696

ACT_CSGO_SILENCER_DETACH	1009

SPECIAL1	11

ACT_READINESS_PISTOL_RELAXED_TO_STIMULATED	423

ACT_FLICK_LEFT	900

ACT_VM_MELEE_LAYER	1649

ACT_RUN_INJURED_SNIPER_MILITARY	1594

ACT_MP_RELOAD_AIRWALK_PRIMARY_LOOP	584

ACT_ITEM2_VM_IDLE_LOWERED	872

ACT_WALK_INJURED_PISTOL	1620

ACT_MP_ATTACK_CROUCH_ITEM2	672

ACT_CROUCHIDLE_AGITATED	105

ACT_RELOAD_SHOTGUN_START	1527

ACT_STEP_BACK	143

ACT_MP_RELOAD_STAND	536

ACT_IDLE_ELITES	1627

ACT_WALK_MARCH	1803

AE_ANTLION_OPEN_WINGS	363

AE_COMBINE_GREN_DROP	328

ACT_RELOAD_M4	1642

ACT_HUNTER_GESTURE_SHOOT	1940

ACT_MP_SPRINT	512

ACT_MP_ATTACK_STAND_GRENADE_SECONDARY	617

ACT_WALK_AIM_RIFLE_STIMULATED	332

ACT_DI_ALYX_ZOMBIE_SHOTGUN26	418

ACT_MP_ATTACK_STAND_PDA	755

AE_RELOAD_EMPTY_CLIPOUT	67

FCVAR_DEMO	65536

ACT_VM_SECONDARYATTACK_DUAL_PISTOL_LAYER	1680

ACT_PDA_VM_SECONDARYATTACK	846

AE_SCRIPT_EVENT_NOT_DEAD	171

ACT_LEANWALL_IDLE	1839

AE_NPC_BODYDROP_HEAVY	4

ACT_MELEE_VM_IDLE_LOWERED	839

ACT_MP_GESTURE_VC_HANDMOUTH_BUILDING	793

ACT_MP_GESTURE_VC_HANDMOUTH_MELEE	775

ACT_VM_PRIMARYATTACK_RIFLE	1731

AE_NPC_SET_INTERACTION_CANTDIE	31

ACT_TERROR_PULLED_RUN_RIFLE	1516

ACT_RUN_AIM	11

ACT_VR_PISTOL_IDLE_SLIDE_BACK_CLIP_READY	950

ACT_IDLE_SMG1_RELAXED	325

AE_ACTION_ALLOW_DODGE	144

PRESENSING	1

ACT_MP_CROUCHWALK_ITEM1	647

ACT_MP_ATTACK_AIRWALK_PRIMARYFIRE	533

ACT_OVERLAY_SHIELD_DOWN	446

ACT_MP_ATTACK_SWIM_PRIMARY	572

ACT_VR_PISTOL_EMPTY_CLIP_IN_SLIDE_BACK	971

ACT_DYINGLOOP	430

ACT_HUNTER_DEPLOYRA2	1937

ACT_CROUCH_IDLE_SHOTGUN	894

PATTACH_ABSORIGIN_FOLLOW	1

ACT_ITEM2_VM_IDLE_TO_LOWERED	871

ACT_VR_SHOTGUN_RELOAD_1	974

AE_WEAPON_SLAM_GROUND	159

ACT_PLAYER_CROUCH_WALK_FIRE	490

ACT_BARNACLE_CHOMP	177

ACT_VM_DETACH_SILENCER	223

ACT_SCRIPT_CUSTOM_14	925

ACT_FLINCH_STOMACH_BACK	128

AE_ALYX_EMPTOOL_USE	372

ACT_VM_RELOAD_END	1796

AE_SCRIPT_EVENT_FIREEVENT	169

ACT_WALK_GREN_PULL_BACK	1563

ACT_VM_PICKUP_FASSIST	1655

ACT_RELOAD_GRENADE_LAUNCHER	1545

ACT_RANGE_ATTACK_RPG	290

ACT_SHOTGUN_PUMP	264

ACT_SLAM_STICKWALL_ND_ATTACH2	229

ACT_PRIMARY_VM_IDLE_TO_LOWERED	816

AE_STRIDER_FOOTSTEP_RIGHT	246

ACT_MP_GESTURE_VC_THUMBSUP_ITEM1	784

ACT_SCRIPT_CUSTOM_1	912

ACT_MP_GESTURE_VC_FISTPUMP_PDA	801

MELEE_MISS	8

ACT_MP_JUMP	513

ACT_LEANWALL_RIGHT_RETURN	1848

ACT_MP_GESTURE_VC_FISTPUMP_PRIMARY	765

ACT_IDLE_CALM_SNIPER	1569

ACT_ANTLIONGUARD_BARK	1991

ACT_SCRIPTED_SEQ_ENTRY_C	1859

ACT_GESTURE_TURN_RIGHT90	170

ACT_MP_ATTACK_STAND_PRIMARYFIRE	522

ACT_SCRIPTED_SEQ_ENTRY_B	1855

ACT_SLEEP	898

ACT_GESTURE_RANGE_ATTACK_SMG1	303

ACT_VM_RELOAD_EMPTY_DUAL_PISTOL_LAYER	1688

ACT_PDA_VM_PRIMARYATTACK	845

ACT_SCANNER_WALK_ALERT	1920

ACT_MP_GRENADE1_DRAW	689

ACT_90_RIGHT	140

ACT_COVER_LOW	5

ACT_GESTURE_FLINCH_LEFTLEG	163

ACT_MP_GESTURE_FLINCH_CHEST	683

AE_BARNACLE_PURGE_STOMACH	337

ACT_WALK_RIFLE_RELAXED	327

ACT_CROUCHING_SHIELD_ATTACK	458

ACT_VM_PICKUP_CHARGING	1653

ACT_HUNTER_ANGRY	1946

ACT_GESTURE_RANGE_ATTACK_HMG1	301

AE_STRIDER_CREAK_BACK	259

ACT_MP_ATTACK_STAND_MELEE	632

AE_WPN_PLAYWPNSOUND	47

ACT_DIE_BACKSHOT	117

ACT_MP_ATTACK_CROUCH_SECONDARY	602

ACT_MP_RELOAD_AIRWALK	545

AE_METROPOLICE_DRAW_PISTOL	282

ACT_GRABBITYGLOVES_PULL	961

ACT_VM_PICKUP_CHARGING_RIFLE_LAYER	1726

ACT_PLAYER_WALK_FIRE	491

ACT_GRABBITYGLOVES_ACTIVE	958

ACT_ZOMBINE_GRENADE_FLINCH_BACK	1889

ACT_DEPLOY_GREN	1552

ACT_RELOAD_PUMPSHOTGUN_START	1542

ACT_SHIELD_UP_IDLE	452

ACT_STRIDER_SLEEP	1913

ACT_RANGE_AIM_SMG1_LOW	293

AE_COMBINE_CAUGHT_ENEMY	327

AE_COMBINE_GREN_TOSS	325

ACT_CSGO_TWITCH_BUYZONE	1012

ACT_VM_PRIMARYATTACK_SILENCED	477

ACT_VM_IS_PRIMARYATTACK	487

ACT_VM_HOLSTER	184

ACT_PRIMARYATTACK_XM1014	1643

ACT_MELEE_STOMP_RIFLE_WALK	1518

NDEBUG_PERSIST_TILL_NEXT_SERVER	0.01023

ACT_IDLE_FIRSTAIDKIT	1608

ACT_VM_RELOAD_EMPTY_CLIPOUT_RIFLE	1739

ACT_MP_ATTACK_SWIM_BUILDING	738

ACT_RELOAD_SMG1	373

ACT_VM_RELOAD_CLIPOUT	1660

AE_HIT_FRONT	96

ACT_HUNTER_DODGEL	1939

DMG_BULLET	2

ACT_VM_HITLEFT2	198

ACT_FLINCH_CROUCH_FRONT	129

ACT_STRIDER_AIMRA1	1905

ACT_MP_GESTURE_VC_THUMBSUP_ITEM2	790

ACT_RUN_GREN	1549

ACT_VM_RELOAD_SNIPER	1781

ACT_RUN_CALM_PISTOL	1626

AE_REVIVER_TELEGRAPH_STORM	223

AE_SCRIPT_EVENT_CANINTERRUPT	168

ACT_VM_MELEE_SMG	1767

ACT_WALK_AIM_RIFLE	354

ACT_MP_JUMP_START_BUILDING	732

ACT_SMG2_FIRE2	266

ACT_SIGNAL_TAKECOVER	59

AE_HIT_LEG_RIGHT_SEVERED	94

ACT_HEADCRAB_CEILING_FALL	1814

AE_ANTLION_MELEE_POUNCE	356

ACT_BUSY_LEAN_BACK	384

ACT_MP_ATTACK_AIRWALK_GRENADE_BUILDING	743

AE_STRIDER_FLICKR	269

ACT_MP_GESTURE_VC_NODYES_PDA	803

AE_STRIDER_CANNONHIT	261

ACT_VM_MISSCENTER	207

ACT_MELEE_SWEEP_RIFLE_RUN	1513

ACT_VM_SPRINT_LEAVE	435

PATTACH_WORLDORIGIN	8

ACT_SCRIPT_CUSTOM_2	913

AE_NPC_RESTARTGESTURE	28

ACT_MP_AIRWALK_ITEM2	663

ACT_MP_ATTACK_AIRWALK_SECONDARY	604

AE_ZOMBIE_POISON_THROW_CRAB	276

ACT_MP_RELOAD_AIRWALK_LOOP	546

ACT_SCRIPT_CUSTOM_22	933

ACT_MP_ATTACK_CROUCH_SECONDARYFIRE	528

ACT_CROUCHING_SHIELD_KNOCKBACK	459

AE_ANTLIONGUARD_CHARGE_EARLYOUT	344

ACT_COVER	3

ACT_RUN_FIRSTAIDKIT	1611

ACT_VM_PICKUP_FASSIST_RIFLE	1727

ACT_MP_CROUCH_ITEM1	643

ACT_FLINCH_HEAD_BACK	126

ACT_MP_GESTURE_FLINCH_RIGHTARM	686

AE_HUNTER_FOOTSTEP_BACK	291

AE_WPN_PRIMARYATTACK	43

ACT_MP_GESTURE_FLINCH_LEFTLEG	687

ACT_VM_RELOAD_CLIPOUT_RIFLE_LAYER	1736

ACT_VM_RELOAD_EMPTY_CLIPIN_LAYER	1668

ACT_VR_SHOTGUN_GRENADE_TWIST	987

DMG_CLUB	128

AE_VORTIGAUNT_HEAL_PAUSE	237

AE_IK_SET_LOCK_ROTATION_ALPHA	177

ACT_DI_ALYX_HEADCRAB_MELEE	415

ACT_SCRIPTED_SEQ_ENTRY_D	1863

AE_SHOW_WEAPON	61

ACT_CROUCH_IDLE_DUAL	890

ACT_CIT_BLINDED	1879

ACT_MP_ATTACK_STAND_GRENADE_MELEE	638

ACT_MP_RELOAD_CROUCH	539

ACT_MANHACK_UNPACK	1821

ACT_VM_PICKUP_CHARGING_SMG	1751

ACT_RANGE_ATTACK_ML	278

ACT_SHIELD_KNOCKBACK	454

ACT_ANTLIONGUARD_CHARGE_HIT	1998

DMG_BLAST_SURFACE	134217728

AE_SHEATHE_WEAPONS	152

ACT_VM_DEPLOY_RIFLE	1729

ACT_VM_RELOAD_EMPTY_CLIPOUT_SMG	1763

ACT_RAGDOLL_RECOVERY_FRONT	951

AE_ANTLIONGUARD_VOICE_ROAR	352

AE_RELOAD_CLIPOUT	65

ACT_MP_CROUCH_BUILDING	726

AE_ACTION_ALLOW_MOVE_INTERRUPT	138

ACT_IDLE_MELEE	341

AE_FASTZOMBIE_GALLOP_LEFT	311

ACT_WALK_AIM_AUTOGUN	876

AE_ANTLION_BURROW_OUT	361

ACT_SHIPLADDER_UP	36

ACT_MP_JUMP_PRIMARY	561

ACT_WALK_RPG_RELAXED	351

ACT_HELICOPTER_CRASHING	1985

ACT_MP_GESTURE_FLINCH_MELEE	679

ACT_IDLE_AIM_RIFLE_STIMULATED	331

AE_FIRE_INPUT	100

ACT_GAUSS_SPINUP	475

ACT_VM_IS_DRAW	484

ACT_DIESIMPLE	20

ACT_MP_CROUCH_IDLE	504

ACT_HL2MP_RUN_MELEE	497

AE_ACTION_AVOID_DAMAGE	139

AE_HIT_LEG_LEFT_SEVERED	95

ACT_IDLE_PUMPSHOTGUN	1530

AE_LOCK_STATE_CHANGED	72

ACT_STRIDER_FINISHRA1	1906

AE_CL_MFOOTSTEP_LEFT_LOUD	107

ACT_VM_IDLE_SMG	1746

ACT_RANGE_ATTACK_SLAM	286

ACT_CROW_LAND	1974

ACT_VM_RELOAD_EMPTY_CLIPIN_PISTOL	1716

ACT_DI_ALYX_ZOMBIE_MELEE	413

AE_MANHACK_OPEN_BLADE	286

ACT_FLINCH_RIGHTARM	122

ACT_VM_THROW_LAYER	1672

ACT_MELEE_STRAIGHT_RIFLE_RUN	1515

ACT_GESTURE_FLINCH_HEAD	158

AE_WEAPON_MELEE_SWISH	111

ACT_VM_PICKUP_CLIPIN_LAYER	1652

ACT_ANTLIONGUARD_PEEK_SIGHTED	1992

ACT_RUN_CALM_SMG	1605

ACT_RELOAD_SUCCEED	874

ACT_VM_DEPLOY	181

ACT_MELEE_VM_PRIMARYATTACK	834

ACT_RUN_AIM_AGITATED	101

ACT_SCRIPTED_SEQ_POST_IDLE_D	1865

ACT_SLAM_DETONATOR_IDLE	256

AE_ANTLION_STOP_WING_LOOP	366

ACT_GESTURE_MELEE_ATTACK_SWING	313

ACT_DOG_PICKUP	1969

ACT_MP_ATTACK_CROUCH_PREFIRE	551

ACT_HL2MP_GESTURE_RANGE_ATTACK_MELEE	500

AE_STRIDER_STOMPHITR	267

ACT_FASTZOMBIE_LEAP_SOAR	1962

ACT_MP_WALK	509

ACT_GUNSHIP_CRASH	1977

ACT_VM_IDLE	185

AE_NPC_START_POWERED_RAGDOLL	187

ACT_RANGE_ATTACK_DUAL	891

AE_STRIDER_ENABLE_MINIGUN_SUPPRESSION	264

ACT_RUNTOIDLE	494

ACT_STRIDER_STOMPR	1910

ACT_VM_RELOAD_CLIPIN_DUAL_PISTOL	1685

ACT_SCRIPT_CUSTOM_21	932

ACT_MP_RELOAD_SWIM_LOOP	543

ACT_OBJ_ASSEMBLING	463

COMBINE_AE_ALTFIRE	374

DMG_PARALYZE	32768

ACT_SLAM_THROW_DETONATE	247

ACT_SIGNAL_HALT	56

ACT_SECONDARY_VM_IDLE_TO_LOWERED	827

ACT_IDLE_HURT	82

ACT_RUN_AIM_SHOTGUN	363

ACT_VM_PICKUP_CHARGING_DUAL_PISTOL	1699

ACT_VM_RELOAD	195

AE_WEAPON_RELOAD_SOUND	125

ACT_VM_THROW	190

AE_ACTION_START_TURN	149

AE_EMPTY	0

ACT_GESTURE_TURN_RIGHT90_FLAT	174

ACT_RANGE_AIM_PISTOL_LOW	294

ACT_DIERAGDOLL	24

ACT_IDLE_CALM_ELITES	1638

AE_MANTLE_LEAP	160

ACT_VR_SHOTGUN_RELOAD_3	976

AE_CLIENT_EFFECT_ATTACH	21

ACT_GESTURE_FLINCH_RIGHTLEG	164

ACT_RUN_AIM_STIMULATED	100

ACT_MP_ATTACK_STAND_GRENADE	525

ACT_SLAM_TRIPMINE_TO_STICKWALL_ND	254

ACT_STRAFE_RIGHT	39

ACT_MP_SWIM_DEPLOYED	520

ACT_GESTURE_RANGE_ATTACK_THROW	311

ACT_MP_CROUCH_MELEE	622

ACT_MP_ATTACK_CROUCH_PRIMARYFIRE	526

ACT_MP_ATTACK_STAND_ITEM1	653

ACT_MANHACK_PACKUP	1823

ACT_WALK_HURT	106

AE_PICKUP_CLIPIN	62

FCVAR_HIDDEN	16

ACT_RELOAD_LOW	70

ACT_MP_ATTACK_AIRWALK_MELEE	637

ACT_SCRIPT_CUSTOM_0	911

ACT_MP_RELOAD_AIRWALK_SECONDARY_LOOP	615

ACT_FLINCH_CROUCH_RIGHT	132

AE_ANTLIONGUARD_FOOTSTEP_LIGHT	342

ACT_VM_PULLPIN_LAYER	1673

ACT_IDLE_DUAL	887

ACT_STAND	46

ACT_IDLE_AIM_SHOTGUN	893

ACT_SIGNAL_GROUP	55

AE_ANTLIONGUARD_SHOVE	341

AE_BLIND_ZOMBIE_FIGHT_HEADCRAB	389

ACT_SCRIPTED_SEQ_POST_IDLE_A	1853

ACT_VM_RELOAD_EMPTY_CLIPIN_DUAL_PISTOL	1691

AE_ACTION_ENTERING_IDLE	136

ACT_WALK_ON_FIRE	134

ACT_DIE_CROUCH_BACKSIDE	408

ACT_ITEM1_VM_HOLSTER	853

ACT_MP_JUMP_START_ITEM1	649

ACT_SCANNER_RETRACT	1923

ACT_VM_MELEE_RIFLE	1743

DMG_VEHICLE	16

ACT_CSGO_FLINCH_MOLOTOV	1019

ACT_PRIMARY_VM_RELOAD	814

ACT_SCRIPTED_SEQ_ENTRY_E	1867

AE_CL_SPEECH	131

DMG_AIRBOAT	33554432

ACT_MP_JUMP_FLOAT_BUILDING	733

AE_HIT_RIGHT	99

ACT_CSGO_IDLE_TURN_BALANCEADJUST	1014

ACT_BARNACLE_HIT	175

ACT_WALK_AGITATED	85

AE_CL_MFOOTSTEP_RIGHT_LOUD	108

ACT_COVER_SMG1_LOW	297

ACT_RANGE_ATTACK1	16

ACT_WALK_SNIPER	1571

ACT_VM_MAUL_LOOP	221

ACT_MP_ATTACK_STAND_GRENADE_PRIMARY	586

ACT_ITEM2_VM_PRIMARYATTACK	867

ACT_PRIMARYATTACK_ELITES_L	1637

AE_FASTZOMBIE_GALLOP_RIGHT	312

ACT_RAGDOLL_RECOVERY_BACK	952

ACT_BUSY_SIT_GROUND_EXIT	389

AE_ACTION_OVERLAP_MOVE	137

AE_STOP_SCRIPTED_EFFECT	20

ACT_VM_RELOAD_CLIPOUT_SNIPER	1783

ACT_VM_SWINGHARD	210

AE_REVIVER_SET_DEST	220

AE_ZOMBIE_POISON_SPIT	277

AE_HIT_ARM_LEFT_SEVERED	93

AE_FOOTSTEP_RIGHT	55

ACT_WALK_INJURED_SMG	1601

AE_WEAPON_SEQUENCE_FINISHED	130

AE_ZOMBIE_ATTACK_LEFT	198

ACT_VM_RELOAD_CLIPOUT_SMG_LAYER	1760

ACT_RUN_CALM_ELITES	1640

ACT_VM_SECONDARYATTACK_DUAL_PISTOL	1679

ACT_VM_PICKUP_CLIPIN_RIFLE_LAYER	1724

ACT_RANGE_ATTACK_SMG1	279

DMG_ENERGYBEAM	1024

ACT_SCRIPTED_SEQ_PRE_IDLE_A	1850

ACT_SIGNAL_RIGHT	58

ACT_SCRIPT_CUSTOM_20	931

ACT_SLAM_STICKWALL_DETONATE	230

FCVAR_VCONSOLE_SET_FOCUS	1073741824

ACT_RELOAD	67

ACT_SMG2_DRAW2	267

ACT_IDLE_INJURED_ELITES	1632

ACT_MP_GESTURE_FLINCH_SECONDARY	678

ACT_GAUSS_SPINCYCLE	476

ACT_PUSH_PLAYER	1931

ACT_PHYSCANNON_ANIMATE_POST	401

AE_PICKUP_FASSIST	64

ACT_TURN_LEFT	42

ACT_PICKUP_RACK	76

ACT_RUN_CALM_RIFLE	1509

ACT_RUN_PROTECTED	14

ACT_VM_RELOAD_RIFLE_LAYER	1734

ACT_IDLE_ANGRY_PISTOL	318

AE_ANTLIONGUARD_BURROW_OUT	351

ACT_MP_ATTACK_STAND_ITEM2	670

ACT_MP_WALK_SECONDARY	593

AE_CITIZEN_HEAL	196

ACT_DISARM	72

ACT_RELOAD_SMG1_LOW	374

ACT_MP_MELEE_GRENADE2_IDLE	711

ACT_VR_PISTOL_CLIP_OUT_SLIDE_BACK	946

ACT_SLAM_THROW_ND_DRAW	244

AE_ZOMBIE_SCUFF_LEFT	204

AE_ATTACK_HIT	57

ACT_DI_ALYX_ANTLION	416

ACT_VM_MELEE	1645

ACT_VM_MELEE_SNIPER_LAYER	1792

AE_HIT_SHOULDER_RIGHT_BACK	85

ACT_VM_IDLE_LOWERED	214

ACT_MP_GESTURE_VC_NODYES_ITEM2	791

ACT_RAGDOLL_RECOVERY_RIGHT	954

ACT_FASTZOMBIE_LAND_LEFT	1965

ACT_TURNLEFT45	461

ACT_MP_ATTACK_SWIM_GRENADE_SECONDARY	619

ACT_DIEVIOLENT	23

DMG_RADIATION	262144

ACT_MP_ATTACK_SWIM_GRENADE_MELEE	640

ACT_OPEN_DOOR	412

AE_HIT_HEAD_FRONT	78

ACT_MP_JUMP_START_ITEM2	666

ACT_MP_GESTURE_VC_NODYES	761

ACT_VR_SHOTGUN_OPEN_CHAMBER	973

ACT_RUN_AIM_AUTOGUN	877

ACT_GESTURE_RANGE_ATTACK_AR2_GRENADE	300

AE_FASTZOMBIE_CLIMB_LEFT	313

AE_ANTLIONGUARD_CHARGE_HIT	339

AE_DRAW_WEAPONS	153

ACT_MP_STAND_ITEM1	642

ACT_RUN_STEALTH_PISTOL	361

ACT_SCRIPTED_SEQ_ENTRY_F	1871

AE_REVIVER_ZAP_TARGET	225

AE_VORTIGAUNT_ACCEL_DISPEL	239

ACT_GESTURE_RANGE_ATTACK_SHOTGUN	306

ACT_MP_RUN_PDA	746

ACT_CROUCHIDLE_PISTOL	1617

ACT_ITEM1_VM_PRIMARYATTACK	856

ACT_ZOMBIE_INTEREST_RIGHT	1834

AE_NPC_BODYDROP_LIGHT	3

ACT_WALK_AIM_RELAXED	95

ACT_MP_WALK_PDA	747

ACT_MP_WALK_BUILDING	728

ACT_DIE_CHESTSHOT	115

ACT_DOG_WAITING	1970

ACT_SHOTGUN_RELOAD_START	262

ACT_SPECIAL_ATTACK1	108

ACT_CSGO_EXIT_LADDER_BOTTOM	1026

ACT_IDLE_RELAXED	78

ACT_RUN_CROUCH_RIFLE	359

AE_WEAPON_AR2_ALTFIRE	129

ACT_MP_SWIM	518

ACT_VM_RELOAD_CLIPOUT_RIFLE	1735

ACT_RANGE_ATTACK1_LOW	18

ACT_SCRIPTED_SEQ_POST_IDLE_C	1861

ACT_RUN_AIM_RIFLE_STIMULATED	333

ACT_DROPSHIP_FLY_IDLE_CARGO	1983

ACT_OVERLAY_SHIELD_UP	445

ACT_WALK_INJURED_PUMPSHOTGUN	1539

ACT_RUN_CROUCH_PISTOL	1618

ACT_IDLE_INJURED_SNIPER_MILITARY	1586

ACT_ANTLIONGUARD_CHARGE_CANCEL	1994

ACT_WALK_INJURED_ELITES	1633

AE_ANTLION_FOOTSTEP_SOFT	357

ACT_HUNTER_IDLE_PLANTED	1956

AE_HIT_LEG_RIGHT_BACK	89

ACT_IDLE_ANGRY_SHOTGUN	319

AE_ABILITY_TICK	148

ACT_WALK_INJURED_SNIPER_MILITARY	1593

AE_METROPOLICE_BATON_ON	278

ACT_DROPSHIP_FLY_IDLE_EXAGG	1979

PATTACH_ABSORIGIN	0

ACT_WALK_AIM_STIMULATED	96

ACT_CSGO_RELOAD_LOOP	1004

ACT_WALK_RELAXED	83

ACT_MP_JUMP_LAND_ITEM1	651

ACT_VM_DEPLOY_DUAL_PISTOL	1675

ACT_ZOMBIE_REVIVE	1829

ACT_VM_PULLBACK_HIGH	188

ACT_CROW_SOAR	1973

ACT_CSGO_DEFUSE_WITH_KIT	994

ACT_GESTURE_RANGE_ATTACK_SLAM	309

DMG_PLASMA	16777216

AE_ZOMBIE_SCUFF_RIGHT	205

ACT_MELEE_ATTACK1	65

ACT_MP_GRENADE1_IDLE	690

ACT_DEPLOY_IDLE	472

ACT_SLAM_THROW_THROW_ND	241

ACT_PDA_VM_IDLE_TO_LOWERED	849

AE_METROPOLICE_BATON_OFF	279

ACT_RUN_AGITATED	89

ACT_RUN_AIM_STEALTH_PISTOL	370

ACT_DROPSHIP_DESCEND_IDLE	1980

ACT_HEADCRAB_CRAWL_FROM_CANISTER_LEFT	1811

ACT_VM_RELOAD_LOOP_LAYER	1795

ACT_OBJ_STARTUP	465

AE_NPC_ATTACK_BROADCAST	29

ACT_GESTURE_RELOAD_PISTOL	378

ACT_DEACTIVATE_BATON	1934

ACT_OVERLAY_PRIMARYATTACK	444

ACT_VR_SHOTGUN_RELOAD_2	975

ACT_MP_DEPLOYED_IDLE	507

ACT_CSGO_RELOAD_END	1005

ACT_VR_PISTOL_SLIDE_RELEASE	944

AE_ANTLIONGUARD_VOICE_BARK	346

ACT_MELEE_SHOVE_RIFLE_RUN	1514

ACT_IDLE_ANGRY_MELEE	342

ACT_ANTLIONGUARD_SHOVE_PHYSOBJECT	2000

ACT_FLY	25

ACT_VM_RELOAD_CLIPIN	1662

ACT_MP_GESTURE_VC_FINGERPOINT_PDA	800

ACT_180_LEFT	137

ACT_SCRIPTED_SEQ_ENTRY_G	1875

ACT_DIE_CROUCH_FRONTSIDE	406

ACT_GESTURE_BARNACLE_STRANGLE	397

ACT_ZOMBIE_SHOVE_LEFT	1826

AE_NPC_RAGDOLL	26

ACT_VM_RELOAD_CLIPOUT_DUAL_PISTOL_LAYER	1684

AE_VORTIGAUNT_ZAP_DONE	231

ACT_RUN_CROUCH_AIM_RIFLE	360

ACT_ITEM2_VM_DRAW	863

ACT_VM_RELOAD_CLIPOUT_PISTOL	1710

AE_MELEE_FORCE_STOP_WEAPON_TRAIL	135

ACT_VM_DRAW	183

ACT_ZOMBINE_GRENADE_RUN	1886

ACT_SHIPLADDER_DOWN	37

ACT_MP_WALK_ITEM2	662

AE_REVIVER_SUBMERGE_INSTANT	216

ACT_MP_RELOAD_STAND_PRIMARY_LOOP	575

ACT_SMG2_IDLE2	265

FCVAR_ARCHIVE	128

AE_REVIVER_LAUNCH_STORM	224

AE_COMBINE_SUPPRESSOR_WINDUP	332

ACT_VR_SHOTGUN_TRIGGER_SQUEEZE	978

ACT_HUNTER_CHARGE_HIT	1954

PATTACH_OVERHEAD_FOLLOW	7

ACT_BUSY_LEAN_LEFT_ENTRY	382

AE_STRIDER_DISABLE_MINIGUN	265

ACT_HEADCRAB_THREAT_DISPLAY	1804

ACT_ANTLIONGUARD_PHYSHIT_RL	2008

ACT_MP_ATTACK_STAND_PRIMARYFIRE_DEPLOYED	523

AE_HIT_LEG_LEFT_FRONT	90

ACT_CSGO_NULL	992

AE_NPC_GIB	185

SPECIAL3	13

AE_ANTLION_FOOTSTEP_HEAVY	358

ACT_DOG_THROW	1968

ACT_VR_PISTOL_LOW_KICK	985

AE_COMPANION_RELEASE_FLARE	194

ACT_SLAM_DETONATOR_DRAW	257

ACT_GESTURE_TURN_RIGHT	166

AE_NPC_WEAPON_DROP	8

AE_BLIND_ZOMBIE_FIGHT_HEADCRAB_HIDE	390

ACT_SLAM_THROW_TO_STICKWALL	245

ACT_COMBINE_AR2_ALTFIRE	1801

AE_WEAPON_SMG1_BURST1	127

ACT_SCRIPTED_SEQ_PRE_IDLE_C	1858

ACT_RUN_RPG	348

ACT_ROLL_RIGHT	41

AE_REVIVER_FINISH_EMERGE	218

ACT_VR_PISTOL_LAST_SHOT	943

AE_DOG_CATCH	317

ACT_MELEE_STRAIGHT_RIFLE_IDLE	1512

ACT_WALK_AIM_DUAL	885

ACT_IDLE_SMG	1595

AE_CL_PLAYSOUND_ATTACHMENT	16

ACT_ALYX_ZAP_TOOL	2013

AE_STRIDER_FOOTSTEP_BACKM	250

DMG_BUCKSHOT	536870912

ACT_ANTLION_SCUTTLE_BACK	968

AE_AMMOCRATE_PICKUP_AMMO	25

ACT_MELEE_ATTACK2	66

ACT_SWIM	28

ACT_ALYX_IDLE_TOOL	2012

ACT_MP_AIRWALK	510

ACT_SCRIPTED_SEQ_ACTION_G	1876

AE_ANTLIONGUARD_FOOTSTEP_HEAVY	343

ACT_SCANNER_SMALL_FLINCH_COMBAT	1918

AE_STRIDER_CREAK_LEFT	257

AE_CL_BODYGROUP_SET_VALUE_CMODEL_WPN	42

ACT_VM_MELEE_DUAL_PISTOL	1701

ACT_ANTLIONGUARD_PEEK_FLINCH	1987

AE_HIT_BACK_LOWER	83

AE_ZOMBIE_STEP_RIGHT	203

AE_HEADCRAB_CEILING_DETACH	305

ACT_IDLE_CALM_PISTOL	1624

AE_BARNACLE_LOWER_TONGUE	338

ACT_MP_STAND_PDA	744

AE_COMBINE_GREN_DETACH	330

ACT_SCRIPTED_SEQ_PRE_IDLE_D	1862

ACT_LEANWALL_LEFT_RETURN	1843

ACT_IDLE_ON_FIRE	133

ACT_VM_PRIMARYATTACK_SMG	1755

ACT_MP_ATTACK_CROUCH_GRENADE_PRIMARY	587

ACT_WAKE	899

ACT_MANHACK_UNPACK_RAPID	1822

AE_VORTIGAUNT_START_HEAL_GLOW	243

ACT_MP_ATTACK_CROUCH_GRENADE_SECONDARY	618

ACT_SLAM_THROW_ND_IDLE	238

ACT_MP_GESTURE_FLINCH_RIGHTLEG	688

AE_REVIVER_START_EMERGE	217

ACT_HL2MP_IDLE_MELEE	496

ACT_VM_HITCENTER	201

AE_NPC_END_POWERED_RAGDOLL	188

ACT_LAND	32

AE_STRIDER_WHOOSH_BACK	256

AE_WEAPON_RELOAD_FILL_CLIP	126

ACT_WALK_AIM_STEALTH	98

ACT_MP_GESTURE_FLINCH_LEFTARM	685

ACT_MP_ITEM1_GRENADE1_ATTACK	715

AE_CL_STOPSOUND	18

ACT_WALK_CROUCH_RPG	349

DOUBLE_SHOT	3

ACT_CROUCHIDLE_SNIPER	1568

DMG_POISON	131072

AE_REVIVER_DIVE_INTO_HOST	377

ACT_MP_WALK_ITEM1	645

AE_REVIVER_DROP_HEART	381

ACT_VM_IDLE_TO_LOWERED	213

PATTACH_ROOTBONE_FOLLOW	9

AE_SCRIPT_EVENT_CUSTOMINTERRUPT_START	173

AE_CITIZEN_GET_PACKAGE	195

ACT_CSGO_ALIVE_LOOP	1016

ACT_VM_IDLE_SNIPER	1770

ACT_MP_GESTURE_FLINCH_STOMACH	684

ACT_HL2MP_JUMP_MELEE	502

ScriptDebugTextTime	10

AE_DOG_PICKUP	316

ACT_VM_PICKUP_CLIPIN_SMG_LAYER	1750

ACT_VM_RELOAD_EMPTY_CLIPIN_DUAL_PISTOL_LAYER	1692

ACT_VM_MELEE_RIFLE_LAYER	1744

ACT_HOP	30

ACT_DIE_RIGHTSIDE	403

ACT_VM_RELOAD_EMPTY	182

PATTACH_EYES_FOLLOW	6

ACT_RUN_CROUCH_PUMPSHOTGUN	1535

ACT_SMG2_TOAUTO	270

AE_STRIDER_FOOTSTEP_BACKL	253

ACT_IDLE_INJURED_PUMPSHOTGUN	1533

AE_SV_BODYGROUP_SET_VALUE	41

AE_ANTLION_MELEE1_SOUND	367

ACT_GESTURE_RANGE_ATTACK_PISTOL_LOW	308

AE_BARNACLE_PUKEGIB	333

ACT_MP_VCD	521

ACT_SCRIPT_CUSTOM_31	942

MELEE_HIT	9

ACT_PDA_VM_DRAW	841

ACT_RUN_RIFLE_RELAXED	328

ACT_DI_HUNTER_MELEE	1943

AE_MARINE_RELOAD_SOUND_A	50

ACT_OBJ_IDLE	467

AE_ANTLION_WORKER_SPIT	369

ACT_MP_ATTACK_CROUCH_GRENADE	529

ACT_SLAM_TRIPMINE_TO_THROW_ND	255

ACT_GRABBITYGLOVES_GRAB	955

AE_CL_BODYGROUP_SET_VALUE	40

ACT_PDA_VM_PULLBACK	844

ACT_SLAM_TRIPMINE_IDLE	250

AE_NPC_MUZZLEFLASH	23

AE_HIT_SHOULDER_RIGHT_FRONT	84

AE_REVIVER_UPDATE_LOCATION	213

ACT_MP_ATTACK_AIRWALK_SECONDARYFIRE	534

ACT_MP_ITEM2_GRENADE1_IDLE	720

AE_MELEE_STOP_COLLISION_DAMAGE	133

ACT_CIT_STARTLED	1882

ACT_MP_ATTACK_CROUCH_GRENADE_MELEE	639

ACT_VM_DEPLOY_DUAL_PISTOL_LAYER	1676

ACT_RELOAD_PISTOL	371

ScriptDebugFirstLine	6

ACT_PRIMARYATTACK_PISTOL	1623

ACT_VORTIGAUNT_ANTLION_THROW	1901

ACT_RUN_INJURED_SNIPER	1577

ACT_SLAM_THROW_TO_TRIPMINE_ND	249

ACT_DO_NOT_DISTURB	179

ACT_HEADCRAB_CRAWL_FROM_CANISTER_CENTER	1812

ACT_CIT_HANDSUP	1878

ACT_DROPSHIP_DEPLOY_IDLE	1981

ACT_MP_ATTACK_SWIM_SECONDARYFIRE	531

AE_COMBINE_RELOAD	322

ACT_TURNRIGHT45	460

ACT_IDLE_RPG_RELAXED	343

AE_HEADCRAB_JUMPATTACK	299

AE_VORTIGAUNT_HEAL_STARTSOUND	234

ACT_SCRIPTED_SEQ_PRE_IDLE_E	1866

ACT_MP_JUMP_LAND_SECONDARY	599

DMG_NEVERGIB	4096

ACT_IDLE_AIM_AUTOGUN	879

ACT_SIGNAL2	51

ACT_MP_GESTURE_FLINCH	676

ACT_MP_JUMP_ITEM1	648

ACT_MP_ATTACK_SWIM_SECONDARY	603

ACT_DIE_HEADSHOT	114

DMG_DISSOLVE	67108864

ACT_VM_DEPLOY_SMG	1753

RELOAD	6

ACT_JUMP	29

ACT_WALK_CARRY	428

ACT_PDA_VM_IDLE_LOWERED	850

ACT_EXPLODE	910

ACT_GESTURE_FLINCH_LEFTARM	161

ACT_VORTIGAUNT_HEAL	1899

AE_SCRIPT_EVENT_DEAD	170

ACT_ZOMBIE_DISABLED	1828

ACT_HUNTER_WALK_ANGRY	1947

ACT_SCRIPT_CUSTOM_17	928

ACT_SCRIPTED_SEQ_ACTION_C	1860

AE_HUNTER_START_EXPRESSION	297

ACT_HEADCRAB_CEILING_DETACH	1816

ACT_VORTIGAUNT_START_HEAL	1894

ACT_ZOMBIE_BLIND_ALERT_IDLE	1838

ACT_IDLE_GREN	1546

ACT_RUN_AIM_DUAL	886

ACT_MP_RUN_PRIMARY	557

ACT_MP_RELOAD_SWIM_PRIMARY_END	582

ACT_WALK_RPG	347

ACT_ANTLIONGUARD_CHARGE_START	1993

ACT_VM_FIDGET_RIFLE_LAYER	1745

ACT_RAPPEL_LOOP	136

ACT_VM_PICKUP_CLIPIN_RIFLE	1723

ACT_SPECIAL_ATTACK2	109

ACT_SLAM_STICKWALL_ND_IDLE	225

ACT_IDLE_SHOTGUN	1519

ACT_SCANNER_FLARE	1922

AE_VORTIGAUNT_CLAW_LEFT	227

ACT_OBJ_PLACING	468

ACT_SECONDARY_VM_PULLBACK	822

ACT_GESTURE_RANGE_ATTACK_AR2	299

ACT_ANTLIONGUARD_CHARGE_STOP	1997

ACT_MP_JUMP_LAND_PDA	753

ACT_MELEE_VM_HOLSTER	831

SINGLE_SHOT	1

ACT_VORTIGAUNT_DISPEL	1900

AE_ACTION_STOP_AVOIDING_DAMAGE	140

AE_HEADCRAB_SPIT	375

ACT_IDLE_CALM_SHOTGUN	1522

ACT_IDLE_SHOTGUN_AGITATED	336

ACT_GESTURE_TURN_LEFT45	167

ACT_MP_RELOAD_SWIM_SECONDARY_END	613

ACT_GESTURE_FLINCH_CHEST	159

ACT_RUN_INJURED_PUMPSHOTGUN	1540

AE_BLIND_ZOMBIE_RATTLE	388

AE_HIT_BACK_UPPER	82

ACT_RUN_PUMPSHOTGUN	1536

ACT_ALYX_DRAW_TOOL	2011

AE_NPC_WEAPON_SET_SEQUENCE_NUMBER	10

ACT_ZOMBINE_GRENADE_PULL	1884

ACT_MP_RELOAD_CROUCH_PRIMARY	577

ACT_WALK_CALM_ELITES	1639

AE_SV_PLAYSOUND	17

ACT_VM_RELOAD_EMPTY_CLIPOUT_LAYER	1666

ACT_RELOAD_FAIL	875

AE_COMPANION_PRODUCE_FLARE	192

ACT_SCRIPT_CUSTOM_30	941

ACT_VM_SHOOT_SNIPER_LAYER	1780

ACT_MP_ATTACK_SWIM_GRENADE_BUILDING	742

ACT_MELEE_VM_IDLE	832

AE_HEADCRAB_BURROW_OUT	304

ACT_LEANWALL_RIGHT_EXIT	1846

AE_REVIVER_ABANDON_EXIT	380

ACT_ANTLIONGUARD_ROAR	2003

ACT_VR_PISTOL_LONG_CLIP_IN_SLIDE_BACK	983

ACT_CSGO_DEFUSE	993

TAUNT	14

ACT_VR_PISTOL_CLIP_IN_CHAMBERED	947

ACT_CROUCHIDLE_SMG	1598

ACT_GESTURE_RANGE_ATTACK1	145

ACT_MP_ITEM1_GRENADE1_DRAW	713

AE_ANTLIONGUARD_VOICE_GROWL	345

AE_CL_PLAYSOUND	15

ACT_MP_ATTACK_SWIM_PRIMARYFIRE	530

ACT_DIEFORWARD	22

ACT_VM_SHOOT_PISTOL_LAYER	1707

ACT_RANGE_ATTACK_AR2	274

ACT_SIGNAL1	50

ACT_VM_PICKUP_FASSIST_RIFLE_LAYER	1728

AE_WEAPON_AR2_GRENADE	120

AE_ANTLION_VANISH	362

ACT_MP_GESTURE_VC_FINGERPOINT_SECONDARY	770

ACT_STRIDER_DEPLOY	1915

ACT_FLINCH_CROUCH_BACK	130

ACT_CROUCH_IDLE_AUTOGUN	881

PATTACH_CUSTOMORIGIN	2

AE_CL_MFOOTSTEP_RIGHT	106

ACT_MP_SWIM_PRIMARY	565

ACT_VM_RELOAD_LOOP	1794

AE_VORTIGAUNT_STOP_HURT_GLOW	242

ACT_BUSY_SIT_CHAIR	390

AE_EF_DRAW	158

AE_EF_NODRAW	157

ACT_VM_RELOAD_SILENCED	478

ACT_VM_DRAW_SILENCED	481

ACT_VM_RELOAD_EMPTY_CLIPOUT	1665

ACT_DIE_FRONTSIDE	402

AE_WPN_INCREMENTAMMO	44

ACT_MELEE_ATTACK_SWING_GESTURE	151

ACT_VM_PICKUP_RIFLE	1721

ACT_HEADCRAB_CEILING_LAND	1817

ACT_STRIDER_GESTURE_DEATH	1916

ACT_VM_RELOAD_EMPTY_SNIPER	1785

ACT_GESTURE_BIG_FLINCH	153

AE_MANHACK_STOP_ENGINE	288

AE_CL_CREATE_PARTICLE_EFFECT_CFG	181

ACT_MP_DEPLOYED_PRIMARY	566

ACT_FASTZOMBIE_FRENZY	1966

ACT_SCRIPT_CUSTOM_9	920

DMG_ACID	1048576

AE_HIT_STOMACH	80

ACT_CSGO_FLASHBANG_REACTION	995

ScriptDebugTextLines	20

ACT_PRIMARY_VM_HOLSTER	809

ACT_WALK_AIM_SHOTGUN	362

ACT_RUN_RPG_RELAXED	352

ACT_WALK_CROUCH_AIM_RIFLE	356

ACT_ZOMBIE_INTEREST_LEFT	1833

ACT_PRIMARYATTACK_PUMPSHOTGUN	1541

ACT_SCRIPT_CUSTOM_23	934

ACT_WALK_CALM_SNIPER_MILITARY	1591

ACT_VM_RELOAD_CLIPOUT_DUAL_PISTOL	1683

AE_CL_CREATE_PARTICLE_EFFECT	33

ACT_ITEM1_VM_PULLBACK	855

ACT_MP_ATTACK_CROUCH_GRENADE_BUILDING	741

AE_COMBINE_GREN_LAUNCH	326

ACT_ZOMBIE_TRIP	964

ACT_SCRIPTED_SEQ_PRE_IDLE_F	1870

ACT_MP_AIRWALK_BUILDING	729

ACT_GESTURE_FLINCH_BLAST_DAMAGED_SHOTGUN	157

ACT_MP_ITEM2_GRENADE1_DRAW	719

ACT_ITEM2_VM_HOLSTER	864

ACT_ZOMBIE_BLIND_SNIFF_OBSTACLE	1836

ACT_DEPLOY_PISTOL	1622

ACT_MP_DOUBLEJUMP	517

ACT_ZOMBIE_SHOVE_RIGHT	1827

AE_MARINE_FOOTSTEP	49

ACT_IDLE_SHOTGUN_STIMULATED	335

AE_ALYX_EMPTOOL_ATTACHMENT	370

ACT_RUN_CROUCH_GREN_PULL_BACK	1564

ACT_MELEE_SHOVE_RIFLE_IDLE	1511

AE_STRIDER_FOOTSTEP_LEFTM	248

ACT_RANGE_ATTACK_SHOTGUN_LOW	283

ACT_GESTURE_FLINCH_RIGHTARM	162

ACT_RIDE_MANNED_GUN	432

ACT_SLAM_TRIPMINE_ATTACH2	253

AE_STRIDER_FOOTSTEP_LEFT	245

ACT_GESTURE_SMALL_FLINCH	152

ACT_GRABBITYGLOVES_ACTIVE_IDLE	959

ACT_HUNTER_FLINCH_N	1957

ACT_MP_RELOAD_SWIM_END	544

ACT_VM_PRIMARYATTACK	193

DMG_GENERIC	0

ACT_SECONDARY_VM_DRYFIRE	826

ACT_VM_RELOAD_DUAL_PISTOL_LAYER	1682

AE_HIT_HEAD_BACK	79

ACT_MP_RELOAD_AIRWALK_PRIMARY_END	585

ACT_MELEE_VM_IDLE_TO_LOWERED	838

ACT_RANGE_ATTACK_SMG1_LOW	280

AE_CL_CLOTH_STIFFEN	190

ACT_SMALL_FLINCH	63

ACT_MP_ATTACK_SWIM_ITEM1	657

ACT_VM_HITRIGHT2	200

AE_HIT_CHEST	81

ACT_MP_JUMP_LAND_BUILDING	734

AE_STRIDER_CREAK_RIGHT	258

ACT_MP_JUMP_FLOAT_SECONDARY	598

ACT_ANTLIONGUARD_FLINCH_LIGHT	2001

ACT_POLICE_HARASS1	338

ACT_GESTURE_RELOAD	377

ACT_MP_AIRWALK_PRIMARY	559

AE_NPC_SWISHSOUND	5

ACT_MP_GESTURE_VC_NODNO_MELEE	780

ACT_FLINCH_LEFTLEG	123

ACT_IDLETORUN	493

ACT_GESTURE_TURN_LEFT90	169

ACT_MP_JUMP_FLOAT_ITEM2	667

ACT_RANGE_ATTACK_AR1	273

AE_MUZZLEFLASH	22

DMG_SLASH	4

ACT_SCRIPTED_SEQ_PRE_IDLE_G	1874

AE_WEAPON_SMG2	117

ACT_IDLE_SNIPER_MILITARYZOOMED	1582

ACT_WALK_INJURED_GREN	1553

ACT_ANTLIONGUARD_CHARGE_CRASH	1996

ACT_VR_SHOTGUN_SLIDE_BACK	980

AE_VORTIGAUNT_HEAL_STARTGLOW	232

ACT_SLAM_THROW_THROW2	240

AE_POISONHEADCRAB_FOOTSTEP	307

AE_HIT_SHOULDER_LEFT_BACK	87

ACT_STRIDER_LOOKL	1902

ACT_MP_GESTURE_FLINCH_HEAD	682

ACT_LEANWALL_LEFT_EXIT	1841

ACT_DIE_INCAP	410

AE_BARNACLE_SPIT	335

ACT_PRIMARY_VM_PRIMARYATTACK	812

ACT_WALK_CALM_RIFLE	1508

ACT_SLAM_DETONATOR_DETONATE	258

ACT_MP_GESTURE_VC_THUMBSUP	760

ACT_ZOMBINE_ATTACK_FAST	1888

ACT_FLICK_RIGHT	903

ACT_MP_ATTACK_STAND_STARTFIRE	550

ACT_RELOAD_PUMPSHOTGUN_LOOP	1543

AE_CL_PLAYSOUND_LOOPING	176

ACT_READINESS_RELAXED_TO_STIMULATED	419

ACT_RUN_CROUCH_SHOTGUN	1524

ACT_BUSY_SIT_GROUND	387

ACT_CSGO_PLANT_BOMB	1013

ACT_OVERLAY_GRENADEIDLE	442

ACT_SLAM_STICKWALL_DRAW	232

ACT_SCRIPTED_SEQ_ACTION_B	1856

ACT_IDLE_CALM_PUMPSHOTGUN	1532

AE_NPC_HOLSTER	12

ACT_PDA_VM_DRYFIRE	848

ACT_CROUCHIDLE_ELITES	1630

AE_ACTION_DROP_ITEM	165

AE_SCRIPT_EVENT_FIRE_INPUT	172

ACT_MP_CROUCH_SECONDARY	591

AE_WEAPON_SHOTGUN_FIRE	112

ACT_WALK_CALM_PUMPSHOTGUN	1537

ACT_VM_IS_HOLSTER	485

ACT_SCANNER_FLARE_START	1926

ACT_CSGO_EXIT_LADDER_TOP	1025

AE_NPC_WEAPON_SET_ACTIVITY	11

ACT_WALK_CALM_SNIPER	1574

AE_WEAPON_AR2	115

ACT_IDLE_GREN_PULL_BACK	1559

AE_STRIDER_FOOTSTEP_BACK	247

ACT_MP_ATTACK_CROUCH_BUILDING	737

ACT_RELOAD_START	68

AE_ACTION_ALLOW_COMBO	142

ACT_STEP_LEFT	141

FCVAR_NEVER_AS_STRING	4096

ACT_STRIDER_CARRIED	1914

AE_VORTIGAUNT_DISPEL	240

ACT_MP_ATTACK_CROUCH_ITEM1	655

ACT_VM_PICKUP_CHARGING_SNIPER	1775

ACT_HUNTER_DODGER	1938

ACT_VM_PICKUP_CLIPIN_DUAL_PISTOL_LAYER	1698

ACT_CROUCHING_GRENADEIDLE	439

ACT_MP_ATTACK_SWIM_PREFIRE	553

AE_STRIDER_FOOTSTEP_LEFTL	251

ACT_WALK_ANGRY	337

ACT_VM_PICKUP_CLIPIN_SNIPER	1773

ACT_VM_RECOIL2	217

AE_CL_MFOOTSTEP_LEFT	105

ACT_VR_SHOTGUN_SLIDE_FORWARD	981

AE_HUNTER_FOOTSTEP_RIGHT	290

ACT_SLAM_STICKWALL_ATTACH	226

ACT_RUN_PISTOL	365

AE_HIT_LEFT	98

ACT_SECONDARY_VM_DRAW	819

ACT_VM_PICKUP_CLIPIN_SNIPER_LAYER	1774

ACT_90_LEFT	139

ACT_ZOMBINE_GRENADE_IDLE	1887

ACT_MP_RUN_ITEM1	644

ACT_MP_GESTURE_VC_FINGERPOINT_ITEM1	782

AE_ANTLION_MELEE_HIT1	354

ACT_MP_ATTACK_SWIM_ITEM2	674

ACT_SCANNER_RETRACT_PRONGS	1925

DMG_DROWN	16384

AE_WEAPON_SMG1	110

ACT_PRIMARYATTACK_M3S90	1644

ACT_RELOAD_FINISH	69

PATTACH_POINT_FOLLOW	5

ACT_MP_RELOAD_AIRWALK_END	547

AE_ANTLION_BURROW_IN	360

AE_RELOAD_EMPTY_CLIPIN2	69

ACT_ITEM1_VM_DRYFIRE	859

ACT_VM_DRYFIRE_LEFT	483

ACT_ANTLION_SCUTTLE_FORWARD	967

AE_OPTIONAL_END	59

FCVAR_PROTECTED	32

ACT_BUSY_LEAN_LEFT_EXIT	383

AE_VORTIGAUNT_SHOOT_SOUNDSTART	236

ACT_STRIDER_DODGER	1907

ACT_HOVER	26

ACT_ZOMBINE_GRENADE_FLINCH_EAST	1892

DMG_REMOVENORAGDOLL	4194304

AE_SOUND_EMITTED	166

ACT_OBJ_UPGRADING	470

ACT_VR_PISTOL_CLIP_OUT_CHAMBERED	945

AE_BARNACLE_BITE	334

ACT_VM_RELOAD_PISTOL	1708

ACT_GESTURE_TURN_RIGHT45	168

ACT_VR_PISTOL_CLIP_IN_SLIDE_BACK	948

ACT_VM_PICKUP_SMG	1747

ACT_MP_RELOAD_SWIM_SECONDARY_LOOP	612

ACT_COMBAT_IDLE	110

ACT_MP_RELOAD_AIRWALK_SECONDARY_END	616

ACT_SLAM_DETONATOR_HOLSTER	259

ACT_IDLE_PISTOL	317

ACT_GESTURE_RANGE_ATTACK_ML	302

ACT_VM_MELEE_PISTOL	1718

ACT_ZOMBIE_BLIND_SNIFF_STARTLE	1837

ACT_GRABBITYGLOVES_GRAB_IDLE	957

ACT_WALK_AIM_AGITATED	97

AE_NPC_180TURN	6

ACT_IDLE_ANGRY_BATON	1936

AE_ACTION_END_TURN	150

ACT_POLICE_HARASS2	339

ACT_OVERLAY_SHIELD_KNOCKBACK	449

AE_HUNTER_DIE	295

ACT_MELEE_VM_DRYFIRE	837

ACT_VM_MISSCENTER2	208

ACT_MP_GESTURE_FLINCH_ITEM2	681

ACT_IDLE_SUITCASE	323

player_spawn_ev	117440535

AE_CL_STOP_PARTICLE_EFFECT	34

AE_FOOTSTEP_LEFT	54

ACT_SCRIPT_CUSTOM_7	918

ACT_CSGO_PARACHUTE	1027

ACT_VM_DRAW_DEPLOYED	495

ACT_ITEM1_VM_IDLE	854

ACT_VM_PRIMARYATTACK_SNIPER	1779

ACT_MP_MELEE_GRENADE1_IDLE	708

PRESIM	0

ACT_RELOAD_SHOTGUN	375

ACT_FLINCH_CHEST_BACK	127

ACT_MP_ATTACK_STAND_PREFIRE	548

AE_ZOMBIE_TOGGLE_HEAD	212

DMG_FALL	32

ACT_IDLE_INJURED_SMG	1600

AE_ATTACK_END	58

AE_NPC_WEAPON_FIRE	14

ACT_IDLE_CALM_SMG	1603

ACT_PDA_VM_HOLSTER	842

ACT_ZOMBIE_INTEREST_FORWARD	1831

ACT_VM_RELOAD_EMPTY_CLIPIN_SNIPER	1789

ACT_SCRIPT_CUSTOM_13	924

ACT_HUNTER_CHARGE_START	1950

ACT_SECONDARY_VM_SECONDARYATTACK	824

ACT_GESTURE_RANGE_ATTACK2	146

ACT_BLACKHEADCRAB_RUN_PANIC	1961

ACT_DIEBACKWARD	21

AE_WEAPON_AR1	114

DMG_SONIC	512

ACT_SLAM_STICKWALL_IDLE	224

ACT_VR_PISTOL_IDLE_SLIDE_BACK	949

AE_ALYX_EMPTOOL_SEQUENCE	371

ACT_GESTURE_RANGE_ATTACK_AR1	298

ACT_SCRIPTED_SEQ_ACTION_D	1864

AE_REVIVER_STORM_EFFECTS	222

EMPTY	0

SPECIAL2	12

AE_NPC_HURT_INTERACTION_PARTNER	30

ACT_CSGO_FIRE_SECONDARY	999

ACT_VM_SPRINT_ENTER	433

ACT_MP_GESTURE_VC_HANDMOUTH_ITEM1	781

AE_VORTIGAUNT_SWING_SOUND	235

ACT_MP_GESTURE_VC_FISTPUMP_MELEE	777

ACT_GESTURE_TURN_LEFT	165

ACT_VM_PICKUP_CLIPIN_DUAL_PISTOL	1697

ACT_WALK_PACKAGE	322

ACT_GESTURE_MELEE_ATTACK2	148

ACT_SIGNAL_LEFT	57

ACT_GESTURE_RANGE_ATTACK_SMG1_LOW	304

ACT_DIE_LEFTSIDE	405

FCVAR_DONTRECORD	131072

ACT_MP_RELOAD_SWIM_PRIMARY_LOOP	581

ACT_RANGE_ATTACK_SMG2	281

ACT_VM_HITRIGHT	199

AE_WEAPON_MELEE_HIT	109

AE_ZOMBIE_POUND	208

ACT_VM_DEPLOY_PISTOL	1704

FCVAR_SS	32768

ACT_ROLL_LEFT	40

ACT_MP_SWIM_ITEM1	652

ACT_ZOMBIE_LUNGE	965

DMG_DROWNRECOVER	524288

ACT_VM_UNUSABLE	805

ACT_VM_PICKUP_DUAL_PISTOL	1695

ACT_RUN_SNIPER_MILITARY	1590

ACT_WALK_AIM_STEALTH_PISTOL	369

SERVER_DLL	1

ACT_CROUCHING_SHIELD_UP	455

PATTACH_RENDERORIGIN_FOLLOW	10

COMBINE_AE_BEGIN_ALTFIRE	373

ACT_DEPLOY_SHOTGUN	1525

PATTACH_CUSTOMORIGIN_FOLLOW	3

ACT_OVERLAY_GRENADEREADY	443

ACT_LEANWALL_RIGHT_IDLE	1845

ACT_SCRIPT_CUSTOM_28	939

AE_CL_PLAYSOUND_POSITION	163

ACT_ZOMBINE_GRENADE_FLINCH_FRONT	1890

ACTIVATE_TYPE_ONRESTORE	2

ACT_MP_SWIM_SECONDARY	600

ACT_FIRE_RECOVER	907

ACT_MP_GESTURE_VC_NODNO_ITEM2	792

ACTIVATE_TYPE_DATAUPDATE_CREATION	1

ACT_MP_ATTACK_SWIM_MELEE	636

ACT_BIG_FLINCH	64

ACTIVATE_TYPE_INITIAL_CREATION	0

ACT_DIE_GUTSHOT	116

AE_FASTZOMBIE_LEAP	310

ACT_SHIELD_ATTACK	453

FCVAR_NOT_CONNECTED	4194304

FCVAR_CHEAT	16384

FCVAR_REPLICATED	8192

FCVAR_UNLOGGED	2048

AE_ACTION_SET_TURN_RATE_SCALE	141

FCVAR_PRINTABLEONLY	1024

FCVAR_USERINFO	512

AE_ZOMBIE_STEP_LEFT	202

FCVAR_NOTIFY	256

ACT_VM_HITLEFT	197

AE_SCRIPT_EVENT_NOINTERRUPT	167

FCVAR_DEVELOPMENTONLY	2

ACT_WALK_CALM_PISTOL	1625

FCVAR_UNREGISTERED	1

AE_SV_DUSTTRAIL	32

ACT_COVER_PISTOL_LOW	296

ACT_MELEE_ATTACK_THRUST	1932

ACT_DROPSHIP_FLY_IDLE	1978

ACT_GESTURE_RELOAD_SMG1	379

ACT_GUNSHIP_PATROL	1975

AE_HEADCRAB_BURROW_IN	302

ACT_MP_SWIM_PDA	754

ACT_PRIMARYATTACK_RIFLE	1505

ACT_CROUCHIDLE_AIM_STIMULATED	104

ACT_IDLE_INJURED_PISTOL	1619

ACT_VM_IDLE_DUAL_PISTOL	1674

ACT_SECONDARY_VM_HOLSTER	820

ACT_WALK_CALM_SMG	1604

AE_REVIVER_START_SUBMERGE	214

ACT_RUN_INJURED_PISTOL	1621

ACT_IDLE_STIMULATED	79

AE_HIT_BACK	97

ACT_VM_IDLE_PISTOL	1703

AE_HUNTER_MELEE_ATTACK_RIGHT	294

AE_MELEE_START_COLLISION_DAMAGE	132

AE_ZOMBIE_STARTSWAT	201

ACT_OBJ_DISMANTLING	464

ACT_SLAM_THROW_DETONATOR_HOLSTER	248

ACT_SCANNER_SMALL_FLINCH_ALERT	1917

AE_CROW_TAKEOFF	321

ACT_RUN_CROUCH_ELITES	1631

ACT_VM_SWINGHIT	212

AE_ATTACK_START	56

AE_WPN_HIDE	45

ACT_VM_RELOAD_EMPTY_CLIPIN_SNIPER_LAYER	1790

ACT_MP_GESTURE_VC_FINGERPOINT	758

ACT_READINESS_STIMULATED_TO_RELAXED	422

ACT_WALK_CROUCH_RIFLE	355

AE_BLIND_ZOMBIE_SNIFF	384

ACT_VM_RELOAD_EMPTY_CLIPIN_RIFLE	1741

ACT_ANTLION_SCUTTLE_RIGHT	970

AE_IK_SET_MASTER_BLEND_AMOUNT	179

ACT_LEANWALL_LEFT_ENTER	1844

ACT_VM_RELOAD_CLIPIN_LAYER	1663

ACT_GESTURE_MELEE_ATTACK1	147

ACT_ZOMBIE_POISON_THREAT	1927

ACT_ITEM2_VM_DRYFIRE	870

ACT_CSGO_FIRE_PRIMARY_OPT_2	998

ACT_ANTLIONGUARD_PEEK_EXIT	1989

ACT_SLAM_THROW_DRAW	243

ACT_VM_SECONDARYATTACK_LAYER	1648

ACT_COVER_LOW_RPG	346

ACT_IDLE_AIM_STEALTH	94

ACT_MP_ATTACK_AIRWALK_BUILDING	739

ACT_CROUCHIDLE_GREN	1547

ACT_VM_SHOOT_LAYER	1646

ACT_PRIMARY_VM_IDLE_LOWERED	817

ACT_ANTLION_SCUTTLE_LEFT	969

ACT_MP_ITEM2_GRENADE1_ATTACK	721

DMG_BURN	8

ACT_MP_JUMP_BUILDING	731

ACT_VM_FIDGET	186

AE_NPC_DRAW	13

AE_BLIND_ZOMBIE_START_SPRAY	385

AE_VORTIGAUNT_HEAL_STARTBEAMS	233

ACT_UNDEPLOY	473

ACT_RUN_RIFLE	357

AE_HUNTER_MELEE_ATTACK_LEFT	293

ACT_MELEE_VM_LOWERED_TO_IDLE	840

ACT_MP_GRENADE2_IDLE	693

AE_WPN_UNHIDE	46

ACT_RUN_RELAXED	87

ACT_MP_SWIM_MELEE	631

ACT_SLAM_THROW_THROW	239

ACT_ITEM1_VM_RELOAD	858

ACT_VM_SHOOT_RIFLE_LAYER	1732

AE_ZOMBIE_POISON_PICKUP_CRAB	274

ACT_BARNACLE_PULL	176

ACT_SCRIPTED_SEQ_ACTION_E	1868

ACT_WALK_AIM_PISTOL	366

ACT_RAGDOLL_RECOVERY_LEFT	953

ACT_MELEE_VM_SECONDARYATTACK	835

AE_METROPOLICE_SHOVE	280

ACT_RELOAD_SMG	1607

ACT_MP_JUMP_FLOAT_MELEE	629

ACT_HUNTER_RANGE_ATTACK2_UNPLANTED	1955

ACT_MP_SECONDARY_GRENADE1_DRAW	701

ACT_HEADCRAB_IDLE_INJURED	1819

ACT_VM_DEPLOY_SNIPER	1777

ACT_IDLE_CARRY	427

ACT_HUNTER_FLINCH_S	1958

ACT_CROW_TAKEOFF	1972

AE_ZOMBIE_POISON_THROW_WARN_SOUND	273

ACT_MP_GESTURE_VC_NODNO_PDA	804

ACT_READINESS_AGITATED_TO_STIMULATED	421

AE_ZOMBINE_PULLPIN	226

AE_VORTIGAUNT_START_HURT_GLOW	241

ACT_VM_IDLE_SILENCED	480

ACT_RUN_AIM_STEALTH	102

ACT_RELOAD_DUAL	889

ACT_MP_GESTURE_VC_NODYES_BUILDING	797

ACT_SIGNAL3	52

ACT_MP_GESTURE_VC_HANDMOUTH_ITEM2	787

ACT_ANTLIONGUARD_CHARGE_RUN	1995

ACT_MP_STAND_PRIMARY	555

ACT_MP_STAND_IDLE	503

ACT_MP_GESTURE_VC_FINGERPOINT_ITEM2	788

DOUBLE_SHOT_NPC	4

ACT_FLICK_LEFT_MIDDLE	901

ACT_MP_GESTURE_VC_FISTPUMP_ITEM1	783

ACT_WALK_SUITCASE	324

AE_REVIVER_RELEASE_REVIVER	221

ACT_GESTURE_RANGE_ATTACK_TRIPWIRE	310

ACT_VM_IDLE_EMPTY_LEFT	482

ACT_MP_GESTURE_VC_FINGERPOINT_MELEE	776

ACT_MP_GESTURE_VC_HANDMOUTH_PRIMARY	763

ACT_VR_PISTOL_BURST_ATTACK	986

ACT_READINESS_PISTOL_STIMULATED_TO_RELAXED	426

AE_ZOMBIE_POISON_THROW_SOUND	275

ACT_DEPLOY_ELITES	1635

ACT_HUNTER_FOUND_ENEMY	1948

ACT_MP_GESTURE_VC_NODYES_PRIMARY	767

ACT_MP_GESTURE_VC_THUMBSUP_PRIMARY	766

ACT_VM_RELOAD_PUMP	1657

ACT_VM_SHOOT_DUAL_PISTOL_LAYER	1678

ACT_MP_GESTURE_VC_FISTPUMP	759

ACT_OBJ_RUNNING	466

ACT_RANGE_AIM_AR2_LOW	295

AE_NPC_ADDGESTURE	27

ACT_ITEM1_VM_IDLE_TO_LOWERED	860

AE_HIT_LEG_RIGHT_FRONT	88

ACT_CROUCHING_SHIELD_DOWN	456

ACT_SCRIPT_CUSTOM_19	930

ACT_MP_SWIM_BUILDING	735

ACT_MP_CROUCH_PDA	745

ACT_VM_RELOAD_EMPTY_SMG_LAYER	1762

ACT_CROUCHING_GRENADEREADY	440

ACT_SECONDARY_VM_IDLE	821

ACT_VR_SHOTGUN_SHOOT	979

ACT_MP_JUMP_LAND_PRIMARY	564

ACT_RELOAD_AUTOGUN	880

ACT_RANGE_ATTACK_SHOTGUN	282

ACT_MP_ITEM2_GRENADE2_ATTACK	724

ACT_MP_ITEM2_GRENADE2_IDLE	723

ACT_MP_ITEM1_GRENADE2_ATTACK	718

ACT_PICKUP_GROUND	75

ACT_DIE_BARNACLE_SWALLOW	396

AE_MELEE_FORCE_START_WEAPON_TRAIL	134

AE_REVIVER_SUBMERGE	378

ACT_MP_ITEM1_GRENADE2_DRAW	716

ACT_PLAYER_CROUCH_FIRE	489

ACT_RELOAD_RIFLE	1506

ACT_SLAM_STICKWALL_TO_TRIPMINE_ND	236

AE_WEAPON_HMG1	116

ACT_VM_DEPLOY_SNIPER_LAYER	1778

AE_WEAPON_THROW	113

ACT_MP_ATTACK_AIRWALK_PRIMARY	573

ACT_MP_SECONDARY_GRENADE2_ATTACK	706

ACT_MP_RELOAD_CROUCH_PRIMARY_END	579

ACT_HL2MP_WALK_CROUCH_MELEE	499

ACT_COMBINE_THROW_GRENADE	1798

ACT_MP_PRIMARY_GRENADE2_IDLE	699

ACT_SCRIPT_CUSTOM_8	919

ACT_MP_JUMP_START_MELEE	628

AE_RELOAD_CLIPIN	66

ACT_TRANSITION	2

ACT_HEADCRAB_BURROW_IN	1808

ACT_CROUCHIDLE_SNIPER_MILITARYZOOMED	1584

ACT_VM_MISSLEFT2	204

ACT_SLAM_THROW_TO_STICKWALL_ND	246

ACT_MP_GRENADE2_ATTACK	694

ACT_VM_USABLE_TO_UNUSABLE	807

ACT_MP_ATTACK_SWIM_GRENADE_PRIMARY	588

ACT_RELOAD_PISTOL_LOW	372

ACT_MP_GESTURE_FLINCH_ITEM1	680

AE_CHARGER_POUND_SOUND	76

ACT_ITEM2_VM_PULLBACK	866

AE_ACTION_PREVENT_COMBO	143

AE_TUG_INCAP	73

ACT_RUN_AIM_RIFLE	358

ACT_IDLE_ANGRY_SMG1	316

ACT_MP_ATTACK_CROUCH_ITEM2_SECONDARY	673

ACT_RUN_STIMULATED	88

AE_HUNTER_MELEE_ANNOUNCE	292

ACT_MELEE_SWEEP_FIRSTAIDKIT	1616

ACT_CROSSBOW_DRAW_UNLOADED	474

ACT_HEADCRAB_FACE_HUG_PLAYER	1820

AE_METROPOLICE_DEPLOY_MANHACK	283

ACT_IDLE_AIM_DUAL	888

ACT_ANTLIONGUARD_SEARCH	1986

ACT_SHIELD_DOWN	451

ACT_MP_ATTACK_SWIM_GRENADE	532

AE_THUMPER_THUMP	24

ACT_PREP_TO_FIRE	905

ACT_DI_HUNTER_THROW	1944

ACT_MP_PRIMARY_GRENADE1_DRAW	695

ACT_MP_JUMP_LAND_MELEE	630

ACT_MP_RELOAD_CROUCH_END	541

ACT_ANTLION_LAND	2010

ACT_MP_AIRWALK_MELEE	625

ACT_MP_GESTURE_VC_THUMBSUP_PDA	802

ACT_ANTLIONGUARD_PHYSHIT_RR	2007

ACT_MP_RELOAD_CROUCH_SECONDARY_LOOP	609

ACT_MP_CROUCH_ITEM2	660

ACT_GRABBITYGLOVES_DEACTIVATE	960

ACT_ANTLIONGUARD_PHYSHIT_FL	2006

ACT_MP_RELOAD_STAND_SECONDARY_LOOP	606

ACT_RELOAD_SHOTGUN_LOW	376

ACT_MP_ATTACK_STAND_SECONDARY	601

ACT_MP_ATTACK_CROUCH_MELEE_SECONDARY	635

ACT_VM_RELOAD_EMPTY_DUAL_PISTOL	1687

ACT_MP_ATTACK_AIRWALK_GRENADE_PRIMARY	589

ACT_ALIEN_BURROW_OUT	49

ACT_SCRIPT_CUSTOM_MOVE	15

ACT_IDLE_RPG	344

AE_STRIDER_WINDUPCANNON	270

ACT_MP_CROUCHWALK_MELEE	626

AE_STRIDER_ENABLE_MINIGUN	263

ACT_FASTZOMBIE_BIG_SLASH	1967

ACT_MP_ATTACK_CROUCH_PRIMARY_DEPLOYED	571

ACT_HEADCRAB_DROWN	1807

ACT_DYINGTODEAD	431

ACT_HL2MP_GESTURE_RELOAD_MELEE	501

ACT_MP_JUMP_LAND_ITEM2	668

ACT_MP_MELEE_GRENADE1_ATTACK	709

ACT_MP_ATTACK_AIRWALK_GRENADE_MELEE	641

AE_HUNTER_FOOTSTEP_LEFT	289

ACT_MP_ATTACK_SWIM_PDA	756

ACT_MP_MELEE_GRENADE2_DRAW	710

ACT_VM_RELOAD_EMPTY_RIFLE	1737

ACT_MP_ATTACK_STAND_ITEM2_SECONDARY	671

ACT_MELEE_VM_DRAW	830

AE_STRIDER_DIE	271

ACT_FIRE_END	438

ACT_VM_PULLPIN	192

DMG_SHOCK	256

ACT_IDLE_MANNEDGUN	340

ACT_MP_RELOAD_STAND_END	538

ACT_SCANNER_INSPECT	1919

ACT_VR_SHOTGUN_IDLE	972

ACT_STRIDER_STOMPL	1909

ACT_VM_IS_IDLE	486

ACT_VORTIGAUNT_HEAL_LOOP	1895

ACT_MP_RUN	508

ACT_MP_CROUCH_PRIMARY	556

ACT_MP_MELEE_GRENADE2_ATTACK	712

ACT_180_RIGHT	138

ACT_VM_RECOIL1	216

ACT_CSGO_IDLE_ADJUST_STOPPEDMOVING	1015

ACT_CIT_HEAL	1881

ACT_CIT_SHOWARMBAND	1880

ACT_SCRIPTED_SEQ_POST_IDLE_G	1877

ACT_VM_RELOAD_EMPTY_CLIPIN	1667

ACT_MP_GESTURE_VC_NODNO_PRIMARY	768

AE_ZOMBIE_POPHEADCRAB	210

ACT_MP_GESTURE_FLINCH_PRIMARY	677

AE_ZOMBIE_SWATITEM	200

ACT_MP_JUMP_FLOAT_PDA	752

ACT_RUN_ON_FIRE	135

ACT_IDLE_AIM_AGITATED	93

ACT_VM_FIDGET_SMG_LAYER	1769

ACT_IDLE_INJURED_GREN	1548

ACT_IDLE_AIM_RIFLE	895

ACT_PHYSCANNON_UPGRADE	272

ACT_SCRIPT_CUSTOM_10	921

ACT_MP_PRIMARY_GRENADE2_ATTACK	700

ACT_ANTLIONGUARD_UNBURROW	2002

ACT_CSGO_CLIMB_LADDER	1022

ACT_ANTLIONGUARD_RUN_HURT	2004

AE_BLIND_ZOMBIE_END_SPRAY	386

ACT_GESTURE_TURN_RIGHT45_FLAT	172

ACT_FLINCH_LEFTARM	121

ACT_MP_JUMP_FLOAT	515

ACT_MP_ATTACK_CROUCH_ITEM1_SECONDARY	656

ACT_HEADCRAB_WALK_INJURED	1818

ACT_VM_RELOAD_EMPTY_PISTOL	1712

ACT_HEADCRAB_CRAWL_FROM_CANISTER_RIGHT	1813

ACT_METROPOLICE_DRAW_PISTOL	1928

ACT_WALK_SCARED	111

AE_REVIVER_DISSOLVE_EFFECT	383

ACT_CROUCH	44

ACT_VM_DEPLOY_PISTOL_LAYER	1705

ACT_MP_ATTACK_CROUCH_POSTFIRE	552

ACT_MP_ATTACK_SWIM_POSTFIRE	554

ACT_WALK_SNIPER_MILITARY	1589

ACT_VM_HAULBACK	209

ACT_BUSY_LEAN_BACK_ENTRY	385

ACT_FLINCH_CROUCH_LEFT	131

ACT_WALK_CROUCH_AIM	9

ACT_MP_GESTURE_VC_FISTPUMP_ITEM2	789

ACT_WALK_RIFLE	353

ACT_SECONDARY_VM_LOWERED_TO_IDLE	829

ACT_MP_RUN_SECONDARY	592

ACT_VM_PICKUP_CHARGING_SNIPER_LAYER	1776

AE_ZOMBIE_ATTACK_BOTH	199

ACT_MP_ITEM1_GRENADE2_IDLE	717

AE_WEAPON_THROW2	121

ACT_VM_RELOAD_SNIPER_LAYER	1782

ACT_WALK_SHOTGUN	1520

ACT_RANGE_ATTACK_RIFLE	897

SINGLE_SHOT_NPC	2

ACT_SPECIFIC_SEQUENCE	180

DMG_ALWAYSGIB	8192

ACT_GESTURE_FLINCH_STOMACH	160

AE_HIT_ARM_RIGHT_SEVERED	92

ACT_MP_ATTACK_AIRWALK_GRENADE_SECONDARY	620

ACT_VM_HITCENTER2	202

ACT_MP_JUMP_LAND	516

AE_VORTIGAUNT_CLAW_RIGHT	228

ACT_CROUCHIDLE	45

ACT_WALK_INJURED_FIRSTAIDKIT	1614

ACT_COWER	62

ACT_VM_RELOAD_SMG	1757

ACT_MP_JUMP_FLOAT_ITEM1	650

ACT_MP_ATTACK_AIRWALK_ITEM1	658

ACT_GESTURE_TURN_LEFT45_FLAT	171

AE_ANTLION_START_WING_LOOP	365

AE_DOG_THROW	315

ACT_VM_DEPLOY_RIFLE_LAYER	1730

ACT_HL2MP_IDLE_CROUCH_MELEE	498

ACT_VM_PICKUP_CHARGING_SMG_LAYER	1752

ACT_MP_RELOAD_STAND_SECONDARY	605

ACT_RUN_ELITES	1629

ACT_READINESS_PISTOL_RELAXED_TO_STIMULATED_WALK	424

ACT_RUN_CALM_PUMPSHOTGUN	1538

ACT_GESTURE_FLINCH_BLAST	154

ACT_SCRIPT_CUSTOM_27	938

AE_WEAPON_SNIPER_RIFLE_FIRE	119

ACT_MP_ATTACK_AIRWALK_GRENADE	535

AE_ZOMBIE_GET_UP	207

FASTRELOAD	15

ACT_MP_GESTURE_VC_FINGERPOINT_PRIMARY	764

ACT_LOOKBACK_LEFT	61

ACT_MP_RELOAD_CROUCH_SECONDARY	608

ACT_BUSY_LEAN_BACK_EXIT	386

ACT_WALK_RIFLE_STIMULATED	329

ACT_MP_RELOAD_STAND_LOOP	537

AE_RELOAD_SHELL_INSERT	70

ACT_VM_PICKUP_CHARGING_DUAL_PISTOL_LAYER	1700

ACT_VM_MISSRIGHT2	206

ACT_ZOMBIE_BLIND_OBSTACLE_STOP	1835

AE_TOSS_ITEM	156

ACT_CROUCHIDLE_STIMULATED	103

ACT_COMBINE_BUGBAIT	1800

ACT_MP_CROUCHWALK_SECONDARY	595

ACT_VM_RELOAD_EMPTY_CLIPIN2_DUAL_PISTOL	1693

ACT_SLAM_THROW_THROW_ND2	242

ACT_CSGO_FLINCH_HEAD	1018

ACT_MP_MELEE_GRENADE1_DRAW	707

ACT_MP_JUMP_START_PRIMARY	562

ACT_DI_ALYX_ZOMBIE_TORSO_MELEE	414

ACT_JUMP_DUAL	892

ACT_MP_STAND_MELEE	621

ACT_HEADCRAB_SMOKE_BOMB	962

ACT_VM_PICKUP_FASSIST_LAYER	1656

ACT_ZOM_RELEASECRAB	1883

ACT_VM_PRIMARYATTACK_PISTOL	1706

ACT_VM_RELOAD_EMPTY_CLIPIN2	1669

ACT_MP_JUMP_SECONDARY	596

ACT_SLAM_DETONATOR_THROW_DRAW	261

ACT_ANTLIONGUARD_CHARGE_ANTICIPATION	1999

ACT_PLAYER_IDLE_FIRE	488

ACT_GESTURE_RANGE_ATTACK_PISTOL	307

ACT_SMG2_RELOAD2	268

ACT_VM_RELOAD_CLIPIN_DUAL_PISTOL_LAYER	1686

AE_HIDE_WEAPON	60

ACT_DIE_CROUCH_RIGHTSIDE	407

ACT_NEUTRAL_REF_POSE	966

AE_KEYFIELD_SOUND	164

ACT_MP_CROUCHWALK_PDA	749

ACT_RUN_INJURED_SMG	1602

ACT_MP_RELOAD_STAND_SECONDARY_END	607

AE_COMBINE_RELOAD_DROP_CLIP	331

ACT_RUN_STEALTH	90

ACT_VM_MISSLEFT	203

ACT_MP_GESTURE_VC_THUMBSUP_SECONDARY	772

ScriptDebugTextIndent	0

ACT_SMG2_TOBURST	271

ACT_WALK_SMG	1596

ACT_FIRE_LOOP	437

ACT_MP_ATTACK_STAND_MELEE_SECONDARY	633

ACT_PHYSCANNON_ANIMATE_PRE	400

ACT_GESTURE_RANGE_ATTACK1_LOW	149

ACT_IDLE_SMG1	315

ACT_IDLE_PACKAGE	321

ACT_PRIMARY_VM_SECONDARYATTACK	813

ACT_LEANWALL_LEFT_IDLE	1840

ACT_VM_MELEE_SMG_LAYER	1768

ACT_STEP_RIGHT	142

ACT_RUN_INJURED_GREN_PULL_BACK	1566

ACT_USE	47

AE_POISONHEADCRAB_THREAT_SOUND	308

ACT_VM_DEPLOY_SMG_LAYER	1754

ACT_WALK_PISTOL	364

AE_HUNTER_SPRAY_BLOOD	296

ACT_MP_GESTURE_VC_NODYES_ITEM1	785

ACT_IDLE_ANGRY_RPG	345

ACT_GESTURE_RANGE_ATTACK2_LOW	150

ACT_VM_MISSRIGHT	205

ACT_IDLE_RIFLE	314

ACT_GESTURE_TURN_LEFT90_FLAT	173

ACT_WALK	6

ACT_SMG2_DRYFIRE2	269

ACT_ZOMBINE_GRENADE_FLINCH_WEST	1891

ACT_MP_GESTURE_VC_NODNO_SECONDARY	774

ACT_MP_CROUCHWALK_PRIMARY	560

ACT_MP_PRIMARY_GRENADE2_DRAW	698

AE_CL_FOOTSTEP_RIGHT	104

ACT_RUN_RIFLE_STIMULATED	330

ACT_PLAYER_RUN_FIRE	492

ACT_ITEM1_VM_LOWERED_TO_IDLE	862

ACT_PHYSCANNON_DETACH	398

ACT_BUSY_STAND	393

ACT_CROUCHIDLE_PUMPSHOTGUN	1531

ACT_MP_AIRWALK_PDA	748

ACT_BARNACLE_CHEW	178

ACT_RUN_CROUCH_SNIPER	1572

ACT_VM_RELOAD_PUMP_LAYER	1658

ACT_CSGO_TAUNT	1028

AE_ANTLION_START_JUMP	359

ACT_SHIELD_UP	450

ACT_MP_GESTURE_VC_NODNO_BUILDING	798

MAX_PATTACH_TYPES	15

ACT_SCRIPT_CUSTOM_18	929

ACT_SCRIPT_CUSTOM_3	914

ACT_CSGO_FIRE_SECONDARY_OPT_2	1001

ACT_VR_SHOTGUN_CLOSE_CHAMBER	977

ACT_SCRIPT_CUSTOM_26	937

ACT_MP_JUMP_START_SECONDARY	597

ACT_BUSY_QUEUE	394

ACT_VR_PISTOL_BURST_TOGGLE	984

ACT_VR_PISTOL_LONG_CLIP_IN_CHAMBERED	982

ACT_MP_RELOAD_SWIM_SECONDARY	611

ACT_CSGO_TWITCH	1011

ACT_COVER_MED	4

ACT_MP_GESTURE_VC_FISTPUMP_SECONDARY	771

ACT_DIE_CROUCH	990

ACT_RUN_INJURED_RIFLE	1503

ACT_CSGO_FIRE_PRIMARY	996

ACT_CSGO_FIRE_PRIMARY_OPT_1	997

DMG_SLOWBURN	2097152

ACT_CSGO_RELOAD_START	1003

ACT_CSGO_OPERATE	1006

ACT_SLAM_STICKWALL_ND_ATTACH	228

ACT_DUCK_DODGE	395

ACT_CSGO_LAND_LIGHT	1023

ACT_CSGO_SILENCER_ATTACH	1010

DMG_NERVEGAS	65536

ACT_LEAP	31

ACT_DIE_STAND	988

ACT_WALK_PUMPSHOTGUN	1534

ACT_MP_GESTURE_VC_NODNO	762

ACT_CROUCHIDLE_RIFLE	1500

ACT_MP_ATTACK_STAND_PRIMARY_DEPLOYED	569

ACT_MP_GESTURE_VC_HANDMOUTH	757

ACT_RUN_SMG	1597

ACT_MP_GRENADE2_DRAW	692

ACT_SCRIPTED_SEQ_PRE_IDLE_B	1854

ACT_MELEE_STOMP_RIFLE_IDLE	1517

ACT_MP_CROUCH_DEPLOYED_IDLE	505

AE_ANTLION_MELEE_HIT2	355

ACT_GESTURE_FLINCH_BLAST_DAMAGED	156

ACT_WALK_INJURED_GREN_PULL_BACK	1565

PATTACH_POINT	4

ACT_RELOAD_SHOTGUN_LOOP	1528

ACT_RELOAD_SHOTGUN_END	1529

ACT_IDLE_INJURED_SNIPER_ZOOMED	1580

ACT_PRIMARYATTACK_GREN2_IDLE	1556

ACT_GESTURE_RANGE_ATTACK_SMG2	305

AE_ABILITY_END_EVENT	147

ACT_PRIMARYATTACK_GREN1_RUN	1557

ACT_PRIMARYATTACK_GREN2_RUN	1558

ACT_CROUCHIDLE_GREN_PULL_BACK	1560

ACT_IDLE_INJURED_GREN_PULL_BACK	1561

ACT_VM_PICKUP	219

ACT_VM_RELOAD_EMPTY_CLIPOUT_DUAL_PISTOL	1689

ACT_RANGE_ATTACK2_LOW	19

AE_COMPANION_LIGHT_FLARE	193

ACT_GESTURE_FLINCH_BLAST_SHOTGUN	155

AE_CROW_HOP	319

ACT_IDLE_INJURED_SNIPER	1570

ACT_SCRIPT_CUSTOM_11	922

ACT_SCRIPT_CUSTOM_5	916

ACT_SCRIPTED_SEQ_ACTION_F	1872

ACT_CROUCHIDLE_SNIPER_ZOOMED	1579

ScriptDebugWatchFistLine	26

ACT_CROUCHIDLE_SNIPER_MILITARY	1583

ACT_HEADCRAB_HOP_LEFT	1805

ACT_RUN_CROUCH_SNIPER_MILITARY	1588

ACT_DOG_CATCH	1971

ACT_RUN_CALM_SNIPER_MILITARY	1592

ACT_MP_WALK_MELEE	624

ACT_SECONDARY_VM_RELOAD	825

ACT_IDLE_INJURED_FIRSTAIDKIT	1610

AE_SV_FOOTSTEP_RIGHT	102

ACT_VM_RELOAD_EMPTY_CLIPIN_RIFLE_LAYER	1742

ACT_IDLE_SNIPER_MILITARY	1581

ACT_MP_ITEM1_GRENADE1_IDLE	714

AE_METROPOLICE_START_DEPLOY	281

AE_HUNTER_END_EXPRESSION	298

ACT_VM_PICKUP_SNIPER	1771

ACT_MP_SWIM_DEPLOYED_PRIMARY	567

ACT_RUN_INJURED_FIRSTAIDKIT	1615

ACT_MP_RELOAD_SWIM_PRIMARY	580

ACT_RUN_SNIPER	1573

POSTSENSING	2

ACT_WALK_ELITES	1628

ACT_PDA_VM_IDLE	843

ACT_RUN_SHOTGUN	1521

AE_ABILITY_START_EVENT	146

ACT_PRIMARYATTACK_ELITES_R	1636

ACT_FASTZOMBIE_LEAP_STRIKE	1963

ACT_RELOAD_ELITES	1641

ACT_VM_RELOAD_CLIPOUT_SMG	1759

ACT_RUN_CROUCH_RPG	350

ACT_VM_PRIMARYATTACK_DUAL_PISTOL	1677

ACT_MP_RUN_ITEM2	661

ACT_IDLE_STEALTH_PISTOL	320

ACT_IDLE_AIM_PISTOL	884

AE_MANHACK_DONE_UNPACKING	285

ACT_VM_RELOAD_LAYER	1659

ACT_SLAM_THROW_IDLE	237

AE_REVIVER_SHOW_MOVEMENT_FX	219

ACT_CLIMB_DISMOUNT	35

ACT_VM_RELOAD_EMPTY_LAYER	1664

ACT_MP_ATTACK_STAND_ITEM1_SECONDARY	654

ACT_MP_RELOAD_STAND_PRIMARY	574

ACT_VORTIGAUNT_TO_ACTION	1897

ACT_FLICK_RIGHT_MIDDLE	902

AE_MANTLE_GRAB	161

ACT_CSGO_CATCH	1008

AE_WEAPON_THROW3	124

ACT_VM_RELOAD_EMPTY_CLIPIN2_DUAL_PISTOL_LAYER	1694

ACT_MP_JUMP_FLOAT_PRIMARY	563

ACT_VM_MELEE_DUAL_PISTOL_LAYER	1702

ACT_RUN_GREN_PULL_BACK	1562

ACT_MP_SWIM_ITEM2	669

ACT_PRIMARY_VM_DRAW	808

ACT_VORTIGAUNT_TO_IDLE	1898

ACT_PRIMARYATTACK_GREN1_IDLE	1555

AE_ZOMBIE_FLINCH_RESET	211

ACT_VM_RELOAD_EMPTY_CLIPIN_SMG	1765

ACT_VM_RELOAD_CLIPOUT_PISTOL_LAYER	1711

ACT_VM_RELOAD_EMPTY_PISTOL_LAYER	1713

ACT_VM_RELOAD_EMPTY_CLIPOUT_PISTOL	1714

ACT_VM_RELOAD_EMPTY_CLIPOUT_PISTOL_LAYER	1715

AE_SCRIPT_EVENT_CUSTOMINTERRUPT_END	174

ACT_VM_MELEE_PISTOL_LAYER	1719

ACT_MP_JUMP_START	514

ACT_SCANNER_FLARE_PRONGS	1924

ACT_WALK_EASY	1802

ACT_IDLE_CALM_RIFLE	1507

DMG_BLAST	64

ACT_READINESS_RELAXED_TO_STIMULATED_WALK	420

ACT_VM_ATTACH_SILENCER	222

ACT_MP_ATTACK_CROUCH_PRIMARYFIRE_DEPLOYED	527

ACT_VM_RELOAD_EMPTY_CLIPOUT_RIFLE_LAYER	1740

ACT_HEADCRAB_SPIT	963

ACT_MP_GESTURE_VC_FINGERPOINT_BUILDING	794

AE_HEADCRAB_BURROW_IN_FINISH	303

ACT_VM_PRIMARYATTACK_LAYER	1647

ACT_IDLE_STEALTH	81

ACT_MP_RELOAD_AIRWALK_PRIMARY	583

ACT_VM_RELOAD_EMPTY_CLIPOUT_SMG_LAYER	1764

AE_CL_CLOTH_GROUND_OFFSET	189

ACT_WALK_INJURED_RIFLE	1502

ACT_PHYSCANNON_ANIMATE	399

ACT_VM_PICKUP_SNIPER_LAYER	1772

ACT_SCRIPT_CUSTOM_6	917

ACT_MP_GESTURE_VC_NODYES_MELEE	779

ACT_SCRIPT_CUSTOM_12	923

ACT_VM_RELOAD_CLIPOUT_SNIPER_LAYER	1784

ACT_VM_RELOAD_EMPTY_SNIPER_LAYER	1786

ACT_HUNTER_FLINCH_E	1959

ACT_VM_PULLBACK_LOW	189

ACT_VM_RELOAD_END_LAYER	1797

AE_RAGDOLL	37

ACT_RESET	0

ACT_RANGE_ATTACK_AR2_LOW	275

AE_COMBINE_KICK	323

ACT_HEADCRAB_HOP_RIGHT	1806

ACT_ALIEN_BURROW_IDLE	48

ACT_HEADCRAB_BURROW_IDLE	1810

ACT_MP_GESTURE_VC_HANDMOUTH_SECONDARY	769

ACT_HEADCRAB_CEILING_IDLE	1815

ACT_MP_SECONDARY_GRENADE1_ATTACK	703

AE_WEAPON_RELOAD	123

ACT_RUN_CROUCH_FIRSTAIDKIT	1613

ACT_ZOMBIE_END_SPRINT	1824

ACT_ZOMBIE_SHOVE_BACK	1825

ACT_WALK_STIMULATED	84

ACT_ZOMBIE_POUND_SHOULDER	1830

ACT_CROUCH_IDLE_RIFLE	896

ACT_MP_PRIMARY_GRENADE1_ATTACK	697

ACT_LEANWALL_LEFT_SHOOT	1842

ACT_DIE_CROUCH_LEFTSIDE	409

ACT_FLINCH_PHYSICS	125

ACT_SCRIPTED_SEQ_ACTION_A	1852

ACT_RANGE_ATTACK_AR2_GRENADE	276

ACT_CLIMB_UP	33

AE_START_SCRIPTED_EFFECT	19

ACT_MP_JUMP_START_PDA	751

ACT_SCANNER_WALK_COMBAT	1921

ACT_SCRIPTED_SEQ_POST_IDLE_F	1873

ACT_MP_STAND_BUILDING	725

ACT_DEPLOY_RIFLE	1504

ACT_VM_RELOAD_CLIPOUT_LAYER	1661

ACT_ZOMBINE_GRENADE_WALK	1885

ACT_ZOMBIE_INTEREST_BACK	1832

ACT_CSGO_JUMP	1020

ACT_RANGE_AIM_LOW	292

ACT_VORTIGAUNT_AIM	1893

ACT_VM_DEPLOY_LAYER	1671

ACT_IDLE_INJURED_RIFLE	1501

ACT_VORTIGAUNT_END_HEAL	1896

ACT_STRIDER_DODGEL	1908

ACT_CROUCHING_PRIMARYATTACK	441

ACT_GESTURE_RELOAD_SHOTGUN	380

AE_HAPTIC_PULSE	186

ACT_SHOTGUN_RELOAD_FINISH	263

AE_VORTIGAUNT_START_DISPEL	238

ACT_VM_PICKUP_CHARGING_LAYER	1654

ACT_METROPOLICE_FLINCH_BEHIND	1930

ACT_WALK_BATON	1935

AE_NPC_ITEM_PICKUP	7

ACT_IDLE_AIM_STIMULATED	92

ACT_HUNTER_STAGGER	1942

AE_NPC_RIGHTFOOT	2

ACT_VM_RELOAD_EMPTY_CLIPIN_SMG_LAYER	1766

ACT_MP_GRENADE1_ATTACK	691

ACT_HUNTER_CHARGE_STOP	1952

ACT_HUNTER_CHARGE_CRASH	1953

ACT_WALK_CROUCH	8

ACT_VM_RELOAD_EMPTY_CLIPOUT_SNIPER_LAYER	1788

AE_BARNACLE_SPIT_PREBITE	336

AE_PICKUP_CHARGING	63

ACT_VM_RELOAD_EMPTY_RIFLE_LAYER	1738

ACT_FASTZOMBIE_LAND_RIGHT	1964

AE_DROP_PRIMARY_WEAPON	162

ACT_IDLE_CALM_SNIPER_MILITARY	1585

AE_SV_FOOTSTEP_LEFT	101

ACT_WALK_STEALTH	86

ACT_GUNSHIP_HOVER	1976

ACT_RUN_INJURED_ELITES	1634

ACT_DROPSHIP_LIFTOFF	1982

ACT_STRAFE_LEFT	38

ACT_HELICOPTER_DROP_BOMB	1984

ACT_READINESS_PISTOL_AGITATED_TO_STIMULATED	425

ACT_MP_RUN_BUILDING	727

ACT_ANTLIONGUARD_PHYSHIT_FR	2005

ACT_SLAM_STICKWALL_TO_THROW	234

ACT_SPINAROUND	904

ACT_RUN_HURT	107

ACT_MP_DEPLOYED	519

ACT_ANTLION_DROWN	2009

ACT_VM_IDLE_RIFLE	1720

ACT_ALYX_HOLSTER_TOOL	2014

AE_NPC_LEFTFOOT	1

AE_HEADCRAB_JUMP_TELEGRAPH	301

ACT_MP_GESTURE_VC_THUMBSUP_MELEE	778

ACT_MP_ATTACK_STAND_GRENADE_BUILDING	740

ACT_VM_RELOAD_RIFLE	1733

ACT_IDLE_SHOTGUN_RELAXED	334

AE_CL_CREATE_PARTICLE_BRASS	36

AE_CL_DISABLE_BODYGROUP	39

ACT_SCRIPT_CUSTOM_25	936

ACT_MP_ATTACK_CROUCH_MELEE	634

ACT_RANGE_ATTACK_PISTOL_LOW	285

AE_ACTION_USE	151

ACT_PRIMARY_VM_IDLE	810

AE_MARINE_RELOAD_SOUND_B	51

AE_REMOVE_CLIENT_AIM	53

ACT_MELEE_ATTACK_SWING	291

ACT_MP_RELOAD_CROUCH_PRIMARY_LOOP	578

ACT_IDLE_AIM_RELAXED	91

ACT_MP_ATTACK_AIRWALK_ITEM2	675

ACT_SCRIPT_CUSTOM_29	940

AE_RELOAD_EMPTY_CLIPIN	68

AE_RELOAD_PUMPEND	71

ACT_VM_PULLBACK	187

ACT_RUN_CROUCH_SMG	1599

AE_ZOMBIE_ATTACK_SCREAM	206

ACT_MP_JUMP_ITEM2	665

AE_DEFIBRILLATOR_SHOCK	77

AE_HIT_SHOULDER_LEFT_FRONT	86

ACT_MELEE_SWEEP_RIFLE_IDLE	1510

AE_HIT_LEG_LEFT_BACK	91

ACT_SIGNAL_ADVANCE	53

ACT_PREP_EXPLODE	909

ACT_MP_ATTACK_STAND_BUILDING	736

AE_REVIVER_DISSOLVE	382

AE_CL_FOOTSTEP_LEFT	103

ACT_COMBINE_LAUNCH_GRENADE	1799

ACT_RANGE_ATTACK_THROW	288

ACT_RANGE_ATTACK2	17

ACT_VM_PICKUP_LAYER	1650

ACT_MP_CROUCHWALK_BUILDING	730

AE_CHARGER_POUND_VOCALIZE	75

ACT_SCRIPT_CUSTOM_15	926

FCVAR_SPONLY	64

AE_PICK_UP_ITEM	154

AE_DROP_ITEM	155

ACT_ITEM1_VM_DRAW	852

ACT_SIGNAL_FORWARD	54

ACT_PRIMARY_VM_LOWERED_TO_IDLE	818

ACT_VM_RELOAD_EMPTY_CLIPOUT_SNIPER	1787

AE_WEAPON_PISTOL_FIRE	122

ACT_SECONDARY_VM_IDLE_LOWERED	828

AE_NPC_BECOME_TEMPORARY_RAGDOLL	175

AE_WEAPON_SMG1_BURSTN	128

AE_IK_ALLOW_PLANE_TILT_NORMAL_UPDATES	178

ACT_CSGO_FALL	1021

AE_FOOTSTEP	184

ACT_CSGO_LAND_HEAVY	1024

ACT_ITEM1_VM_IDLE_LOWERED	861

AE_NPC_WEAPON_FIRE_SHARED	191

ACT_LOOKBACK_RIGHT	60

AE_COMBINE_AIM	324

ACT_CSGO_FLINCH	1017

ACT_MP_RELOAD_AIRWALK_SECONDARY	614

ACT_FIRE	906

ACT_BUSY_SIT_CHAIR_ENTRY	391

ACT_MP_ITEM2_GRENADE2_DRAW	722

ACT_WALK_FIRSTAIDKIT	1612

ACT_SLAM_STICKWALL_TO_THROW_ND	235

AE_VORTIGAUNT_ZAP_POWERUP	229

AE_VORTIGAUNT_ZAP_SHOOT	230

ACT_MP_JUMP_PDA	750

AE_STRIDER_WHOOSH_RIGHT	255

AE_VORTIGAUNT_STOP_HEAL_GLOW	244

AE_STRIDER_FOOTSTEP_RIGHTM	249

ACT_IDLE_AUTOGUN	878

AE_REVIVER_EMERGE	379

AE_STRIDER_FOOTSTEP_RIGHTL	252

AE_STRIDER_WHOOSH_LEFT	254

ACT_FLINCH_CHEST	119

AE_STRIDER_SHOOTMINIGUN	262

ACT_VM_RELOAD_EMPTY_CLIPOUT_DUAL_PISTOL_LAYER	1690

AE_ANTLION_WALK_FOOTSTEP	353

ACT_VM_RELOAD_EMPTY_CLIPIN2_LAYER	1670

ACT_RUN_AIM_RELAXED	99

ACT_VM_RELOAD_SMG_LAYER	1758

ACT_HUNTER_FLINCH_STICKYBOMB	1941

AE_HEADCRAB_FLIPPED	309

AE_MANHACK_START_ENGINE	284

ACT_VM_DROP	191

DMG_PHYSGUN	8388608

ACT_LEANWALL_RIGHT_SHOOT	1847

ACT_ACTIVATE_BATON	1933

ACT_GLIDE	27

ACT_VM_RELOAD_PISTOL_LAYER	1709

ACT_RANGE_ATTACK_SNIPER_RIFLE	289

AE_DOG_PICKUP_NOEFFECT	318

ACT_VM_MELEE_SNIPER	1791

ACT_DI_ALYX_ZOMBIE_SHOTGUN64	417

AE_COMBINE_KICK_DOOR	329

ACT_IDLE_SMG1_STIMULATED	326

ACT_IDLE_AGITATED	80

AE_ANTLIONGUARD_VOICE_GRUNT	350

AE_BLIND_ZOMBIE_KILL_PLAYER	387

ACT_ANTLIONGUARD_PEEK1	1990

AE_ANTLION_MELEE2_SOUND	368

AE_ANTLIONGUARD_VOICE_SQUEEZE	348

ACT_MP_SECONDARY_GRENADE2_IDLE	705

ACT_SLAM_TRIPMINE_ATTACH	252

DMG_CRUSH	1

ACT_BUSY_SIT_GROUND_ENTRY	388

AE_CL_CREATE_ANIM_SCOPE_PROP	182

ACT_DIE_STAND_HEADSHOT	989

ACT_WALK_STEALTH_PISTOL	368

```
