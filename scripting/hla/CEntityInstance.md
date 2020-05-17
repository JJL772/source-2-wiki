# CEntityInstance

## Methods

### `GetEntityIndex`
```
int GetEntityIndex()

```
------

### `DisconnectRedirectedOutput`
```
void DisconnectRedirectedOutput(string, string, handle)
Removes a connected script function from an I/O event on the passed entity.
```
------

### `GetOrCreatePublicScriptScope`
```
handle GetOrCreatePublicScriptScope()
Retrieve, creating if necessary, the public script-side data associated with an entity
```
------

### `GetOrCreatePrivateScriptScope`
```
handle GetOrCreatePrivateScriptScope()
Retrieve, creating if necessary, the private per-instance script-side data associated with an entity
```
------

### `GetPrivateScriptScope`
```
handle GetPrivateScriptScope()
Retrieve the private per-instance script-side data associated with an entity
```
------

### `RedirectOutput`
```
void RedirectOutput(string, string, handle)
Adds an I/O connection that will call the named function on the passed entity when the specified output fires.
```
------

### `GetIntAttr`
```
int GetIntAttr(string)
Get Integer Attribute
```
------

### `FireOutput`
```
void FireOutput(string, handle, handle, table, float)
Fire an entity output
```
------

### `GetDebugName`
```
string GetDebugName()
Get the entity name w/help if not defined (i.e. classname/etc)
```
------

### `DisconnectOutput`
```
void DisconnectOutput(string, string)
Removes a connected script function from an I/O event on this entity.
```
------

### `Destroy`
```
void Destroy()

```
------

### `GetClassname`
```
string GetClassname()

```
------

### `GetName`
```
string GetName()

```
------

### `ConnectOutput`
```
void ConnectOutput(string, string)
Adds an I/O connection that will call the named function on this entity when the specified output fires.
```
------

### `entindex`
```
int entindex()

```
------

### `GetEntityHandle`
```
ehandle GetEntityHandle()
Get the entity as an EHANDLE
```
------

### `RemoveSelf`
```
void RemoveSelf()
Delete this entity
```
------

### `SetIntAttr`
```
void SetIntAttr(string, int)
Set Integer Attribute
```
------

### `GetPublicScriptScope`
```
handle GetPublicScriptScope()
Retrieve the public script-side data associated with an entity
```
------
