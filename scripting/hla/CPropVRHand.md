# CPropVRHand

## Methods

### `GetHandID`
```
int GetHandID()
Get hand ID
```
------

### `GetHandAttachment`
```
handle GetHandAttachment()
Get the attachment on this hand
```
------

### `RemoveAllHandModelOverrides`
```
void RemoveAllHandModelOverrides()
Remove all model overrides for this hand
```
------

### `SetHandAttachment`
```
void SetHandAttachment(handle hAttachment)
Set the attachment for this hand
```
------

### `AddHandModelOverride`
```
handle AddHandModelOverride(string pModelName)
Add a model override for this hand
```
------

### `GetVelocity`
```
Vector GetVelocity()
Get the filtered controller velocity.
```
------

### `GetPlayer`
```
handle GetPlayer()
Get the player for this hand
```
------

### `GetLiteralHandType`
```
int GetLiteralHandType()
Get literal type for this hand
```
------

### `RemoveHandModelOverride`
```
void RemoveHandModelOverride(string pModelName)
Remove a model override for this hand
```
------

### `AddHandAttachment`
```
void AddHandAttachment(handle hAttachment)
Add the attachment to this hand
```
------

### `RemoveHandAttachmentByHandle`
```
void RemoveHandAttachmentByHandle(handle hAttachment)
Remove hand attachment by handle
```
------

### `FindHandModelOverride`
```
handle FindHandModelOverride(string pModelName)
Find a specific model override for this hand
```
------

### `FireHapticPulse`
```
void FireHapticPulse(int nStrength)
Fire a haptic pulse on this hand. [0,2] for strength.
```
------

### `FireHapticPulsePrecise`
```
void FireHapticPulsePrecise(int nPulseDuration)
Fire a haptic pulse on this hand. Specify the duration in micro seconds.
```
------
