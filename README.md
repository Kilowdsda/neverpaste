# neverpaste

## Notifications

Example usage:

```lua
addNotification(
    "Update complete",
    "All files downloaded",
    faicons("check"),
    {
        duration = 5,
        iconColor = imgui.ImVec4(0,1,0,1),
        barColor = imgui.ImVec4(1,0,0,1),
        onClick = function() print("clicked") end
    }
)
```
