# FE2 Wallhops

## Script:

```lua
local Players = game:GetService('Players')
local LocalPlayer = Players.LocalPlayer

local character = LocalPlayer.Character
if not character then
  repeat task.wait() until LocalPlayer.Character ~= nil
  character = LocalPlayer.Character
end

character["Anti-Wallhop"]:Destroy()
```
