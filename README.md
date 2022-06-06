# FlagCatalog
Possible flags for the Pride event!

# Information

## Structure

The structure of the data goes as so: 

```lua
local dump_data = {
    Patterns = { --> P1
        Blank = { --> P2
            PreviewImage = "rbxassetid://9006528498", --> P3 
            Requirement = "CustomColors", --> P3
            Name = "Blank", --> P3
            Groups = { "Patterns" } --> P3
        }, 
```

## P1

P1 is the table holding the `Groups` the flag is in, currently from scrounging around in decompiled modules I have found 2. `Pattern`s and `Pride`. They are sorted as so. 

## P2

P2 is a table holding the flags themselves, the way I formatted it keeps it so the key holding the table is the Name of the flag. As seen here the flag is `Blank` so the key of the table is named `Blank`. 

## P3

P3 has 3 Different types of Data, Only one has 4.

### P3.1 (PreviewImage)

The preview image holds the Roblox Asset ID of the image. Simple! To find the decals just search them using the link below, since out PreviewImage is `rbxassetid://9006528498` then you copy the ID (numbers after `rbxassetid://` and paste it into a link like below. :)

```
https://www.roblox.com/library/9006528498
```

### P3.2 (Requirement)

Requirement only appears in one Flag. Blank! I don't know it's use but what we can denote is it allows changes to be done. `CustomColors` is present so we can assume it allows for custom colors.

### P3.3 (Name)

The Name is pretty self explanatory, it hold the name of the flag. Simple!

### P3.4 (Groups)

Groups hold the group the flag is in, there are two groups. `Patterns` and `Pride`.
