# CCustomGameEventManager

## Methods

### `Send_ServerToPlayer`
```
void Send_ServerToPlayer(handle, string, handle)
( Entity Player, string EventName, table EventData )
```
------

### `UnregisterListener`
```
void UnregisterListener(int)
( int ListnerID ) - Unregister a specific listener
```
------

### `Send_ServerToAllClients`
```
void Send_ServerToAllClients(string, handle)
( string EventName, table EventData )
```
------

### `RegisterListener`
```
int RegisterListener(string, handle)
( string EventName, func CallbackFunction ) - Register a callback to be called when a particular custom event arrives. Returns a listener ID that can be used to unregister later.
```
------

### `Send_ServerToTeam`
```
void Send_ServerToTeam(int, string, handle)
( int TeamNumber, string EventName, table EventData )
```
------
