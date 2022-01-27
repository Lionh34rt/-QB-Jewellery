# Description
Players have to thermite the electrical box on the roof before the front door opens.
https://i.gyazo.com/bc1591a71998ad2c84fb15c754f8a5df.png

Original: https://github.com/qbcore-framework/qb-jewelery
Edited by https://github.com/Lionh34rt

# Dependencies
* [QBCore Framework](https://github.com/qbcore-framework)
* [Memorygame by pushkart2](https://github.com/pushkart2/memorygame)
* [qb-target by BerkieBb](https://github.com/BerkieBb/qb-target)

# Nui-doorlock config:
```lua
Config.DoorList['jewelery'] = {
    doors = {
        {objHash = 1425919976, objHeading = 306.00003051758, objCoords = vec3(-631.955383, -236.333267, 38.206532)},
        {objHash = 9467943, objHeading = 306.00003051758, objCoords = vec3(-630.426514, -238.437546, 38.206532)}
    },
    audioRemote = false,
    slides = false,
    authorizedJobs = { ['police']=0 },
    lockpick = false,
    maxDistance = 2.5,
    locked = true,
    --oldMethod = true,
    --audioLock = {['file'] = 'metal-locker.ogg', ['volume'] = 0.6},
    --audioUnlock = {['file'] = 'metallic-creak.ogg', ['volume'] = 0.7},
    --autoLock = 1000,
    --doorRate = 1.0,
    --showNUI = true
}
```

# qb-doorlock config
```lua
---------------------
-- Jewellery Store --
---------------------
{
    textCoords = vector3(-631.26, -237.29, 38.07),
    authorizedJobs = { 'police' },
    locking = false,
    locked = true,
    pickable = false,
    distance = 1,
    doors = {
        {
            objName = 'p_jewel_door_l',
            objYaw = -55.0,
            objCoords = vector3(-631.26, -237.29, 38.07),
        },

        {
            objName = 'p_jewel_door_r1',
            objYaw = -53.0,
            objCoords = vector3(-631.26, -237.29, 38.07),		
        }
    }
},
```