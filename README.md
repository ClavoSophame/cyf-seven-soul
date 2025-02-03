# cyf-seven-soul
A seven soul library for CYF v0.6.5.<br>
***This library uses the Rotational Collision library of WD200019.***

## How to use
Put this line of code on the first line of your turn:
```lua
local soul = require("soul-finale")
```
Then you can use `soul:Initialize(mode, tab)` to change your soul.
```lua
-- Red soul.
soul:Initialize(1)

-- Orange soul.
soul:Initialize(2)

-- Yellow soul.
soul:Initialize(3, {control = 1})

-- Green soul.
soul:Initialize(4)
soul:GreenAddShield({0, 0, 1}, {"W.", "S.", "A.", "D."})
```
Please refer to the documentation for the usage of other souls.
