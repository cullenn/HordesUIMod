==Potential features==

-   Add whisper chat filter
-   Implement inventory sorting
-   Clicking names in party to add as friends
-   Tooltip on buffs to show name+basic effect [cant get level probably]
-   Track gold per hour, must keep inventory open though [make sure user is aware]
-   Ctrl clicking item in inventory when Merchant is open to paste item name into search field, and search
-   Alt+right click item stats should work from other windows - character at least, but ideally stash and auction
-   Locked slots should be specific to each character
-   (MAYBE) Add keybind for friends list (Need to create custom keybind UI, accessible from Settings, disallow using same keybinds as game)
-   (MAYBE) Improved healer party frames
-   (MAYBE) Add toggleable option to include chat messages to right of party frame
-   (MAYBE) Fame/time meter
-   (MAYBE) Heals per second meter

==Technical improvements==

-   Should create interval every 3-5s where state updates in localstorage if it has saved, then remove various setState calls
-   Remove all reliance on svelte- classes, likely breaks with updates (Partially started: Added `getWindow` method to utils.game)
