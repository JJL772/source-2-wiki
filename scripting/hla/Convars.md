# Convars

## Methods

### `GetFloat`
```
table GetFloat(string)
GetFloat(name) : returns the convar as a float. May return null if no such convar.
```
------

### `GetStr`
```
table GetStr(string)
GetStr(name) : returns the convar as a string. May return null if no such convar.
```
------

### `SetStr`
```
void SetStr(string, string)
SetStr(name, val) : sets the value of the convar to the string.
```
------

### `SetInt`
```
void SetInt(string, int)
SetInt(name, val) : sets the value of the convar to the int.
```
------

### `RegisterCommand`
```
void RegisterCommand(string, handle, string, int)
RegisterCommand(name, fn, helpString, flags) : register a console command.
```
------

### `GetCommandClient`
```
handle GetCommandClient()
GetCommandClient() : returns the player who issued this console command.
```
------

### `GetInt`
```
table GetInt(string)
GetInt(name) : returns the convar as an int. May return null if no such convar.
```
------

### `SetFloat`
```
void SetFloat(string, float)
SetFloat(name, val) : sets the value of the convar to the float.
```
------

### `RegisterConvar`
```
void RegisterConvar(string, string, string, int)
RegisterConvar(name, defaultValue, helpString, flags): register a new console variable.
```
------

### `GetBool`
```
table GetBool(string)
GetBool(name) : returns the convar as a boolean flag.
```
------

### `SetBool`
```
void SetBool(string, bool)
SetBool(name, val) : sets the value of the convar to the bool.
```
------
