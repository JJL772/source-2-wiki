# CDebugOverlayScriptHelper

## Methods

### `VertArrow`
```
void VertArrow(Vector, Vector, float, int, int, int, int, bool, float)
Draws a vertical arrow. Specify endpoints in world space.
```
------

### `Sphere`
```
void Sphere(Vector, float, int, int, int, int, bool, float)
Draws a wireframe sphere. Specify center in world space.
```
------

### `YawArrow`
```
void YawArrow(Vector, float, float, float, int, int, int, int, bool, float)
Draws a arrow associated with a specific yaw. Specify endpoints in world space.
```
------

### `Capsule`
```
void Capsule(Vector, Quaternion, float, float, int, int, int, int, bool, float)
Draws a capsule. Specify base in world space.
```
------

### `SweptBox`
```
void SweptBox(Vector, Vector, Vector, Vector, Quaternion, int, int, int, int, float)
Draws a swept box. Specify endpoints in world space and the bounds in local space.
```
------

### `EntitySkeleton`
```
void EntitySkeleton(ehandle, float)
Draws the skeleton of the entity
```
------

### `Line2D`
```
void Line2D(Vector2D, Vector2D, int, int, int, int, float)
Draws a line between two points in screenspace
```
------

### `Texture`
```
void Texture(string, Vector2D, Vector2D, int, int, int, int, Vector2D, Vector2D, float)
Draws a screen-space texture. Coordinates are in pixels.
```
------

### `EntityAxis`
```
void EntityAxis(ehandle, float, bool, float)
Draws the axis of the entity origin
```
------

### `Cross3D`
```
void Cross3D(Vector, float, int, int, int, int, bool, float)
Draws a world-aligned cross. Specify origin in world space.
```
------

### `PushAndClearDebugOverlayScope`
```
void PushAndClearDebugOverlayScope(utlstringtoken)
Pushes an identifier used to group overlays. Deletes all existing overlays using this overlay id.
```
------

### `Triangle`
```
void Triangle(Vector, Vector, Vector, int, int, int, int, bool, float)
Draws a filled triangle. Specify vertices in world space.
```
------

### `Line`
```
void Line(Vector, Vector, int, int, int, int, bool, float)
Draws a line between two points
```
------

### `BoxAngles`
```
void BoxAngles(Vector, Vector, Vector, Quaternion, int, int, int, int, bool, float)
Draws an oriented box at the origin. Specify bounds in local space.
```
------

### `Axis`
```
void Axis(Vector, Quaternion, float, bool, float)
Draws an axis. Specify origin + orientation in world space.
```
------

### `DrawTickMarkedLine`
```
void DrawTickMarkedLine(Vector, Vector, float, int, int, int, int, int, bool, float)
Draws a dashed line. Specify endpoints in world space.
```
------

### `CircleScreenOriented`
```
void CircleScreenOriented(Vector, float, int, int, int, int, bool, float)
Draws a circle oriented to the screen. Specify center in world space.
```
------

### `Cross`
```
void Cross(Vector, float, int, int, int, int, bool, float)
Draws a screen-aligned cross. Specify origin in world space.
```
------

### `EntityText`
```
void EntityText(ehandle, int, string, int, int, int, int, float)
Draws text on an entity
```
------

### `Circle`
```
void Circle(Vector, Quaternion, float, int, int, int, int, bool, float)
Draws a circle. Specify center in world space.
```
------

### `EntityAttachments`
```
void EntityAttachments(ehandle, float, float)
Draws the attachments of the entity
```
------

### `PopDebugOverlayScope`
```
void PopDebugOverlayScope()
Pops the identifier used to group overlays. Overlays marked with this identifier can be deleted in a big batch.
```
------

### `Cone`
```
void Cone(Vector, Vector, float, float, int, int, int, int, bool, float)
Draws a wireframe cone. Specify endpoint and direction in world space.
```
------

### `Box`
```
void Box(Vector, Vector, int, int, int, int, bool, float)
Draws a world-space axis-aligned box. Specify bounds in world space.
```
------

### `Cross3DOriented`
```
void Cross3DOriented(Vector, Quaternion, float, int, int, int, int, bool, float)
Draws an oriented cross. Specify origin in world space.
```
------

### `RemoveAllInScope`
```
void RemoveAllInScope(utlstringtoken)
Removes all overlays marked with a specific identifier, regardless of their lifetime.
```
------

### `EntityBounds`
```
void EntityBounds(ehandle, int, int, int, int, bool, float)
Draws bounds of an entity
```
------

### `VectorText3D`
```
void VectorText3D(Vector, Quaternion, string, int, int, int, int, bool, float)
Draws 3D text. Specify origin + orientation in world space.
```
------

### `FilledRect2D`
```
void FilledRect2D(Vector2D, Vector2D, int, int, int, int, float)
Draws a screen-space filled 2D rectangle. Coordinates are in pixels.
```
------

### `SolidCone`
```
void SolidCone(Vector, Vector, float, float, int, int, int, int, bool, float)
Draws a solid cone. Specify endpoint and direction in world space.
```
------

### `UnitTestCycleOverlayRenderType`
```
void UnitTestCycleOverlayRenderType()
Toggles the overlay render type, for unit tests
```
------

### `HorzArrow`
```
void HorzArrow(Vector, Vector, float, int, int, int, int, bool, float)
Draws a horizontal arrow. Specify endpoints in world space.
```
------

### `PushDebugOverlayScope`
```
void PushDebugOverlayScope(utlstringtoken)
Pushes an identifier used to group overlays. Overlays marked with this identifier can be deleted in a big batch.
```
------

### `Text`
```
void Text(Vector, int, string, float, int, int, int, int, float)
Draws 2D text. Specify origin in world space.
```
------
