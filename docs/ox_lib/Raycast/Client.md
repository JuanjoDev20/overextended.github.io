### lib.raycast.cam

Starts a shapetest originating from the camera, extending to ~10m.

```lua
---@param flags number? Defaults to 1|2|8|16 (see: https://docs.fivem.net/natives/?_0x377906D8A31E5586)
---@param p8 number? A bit mask with bits 1, 2, 4, or 7 relating to collider types. 4 and 7 are usually used.
---@return boolean hit
---@return number entityHit
---@return vector3 endCoords
---@return vector3 surfaceNormal
---@return number materialHash
function lib.raycast.cam(flags, p8) end
```
