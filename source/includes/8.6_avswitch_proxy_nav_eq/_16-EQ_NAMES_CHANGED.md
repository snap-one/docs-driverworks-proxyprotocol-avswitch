## EQ\_NAMES\_CHANGED

Navigator EQ notification of the current names for the equalizer presets.


### Name

`EQ_NAMES_CHANGED`


| Parameter       | Type           | Description     |
| --------------- | -------------- | --------------- |
| OutputBindingID | INT            | OutputBindingID |
|                 | Table of names | Table of names  |


### Returns

`None`


### Example


```lua
C4:SendToProxy(5001, "EQ_NAMES_CHANGED", { [1] = "FLAT", [2] = "CLASSICAL", [3] = "JAZZ", [4] = "POP",   [5] = "ROCK", OUTPUT = "4002" }, "NOTIFY")

C4:SendToProxy(5001, "EQ_NAMES_CHANGED", {"FLAT", "CLASSICAL", "JAZZ", "POP", "ROCK", OUTPUT = 4002}, "NOTIFY")
```
