


setting particular blips for location.

`
local blip1 = AddBlipForCoord(563.76, 2753.27, 41.88)
SetBlipSprite(blip1, 273)  // Find blips sprite from  https://docs.fivem.net/docs/game-references/blips/
SetBlipScale(blip1, 0.5) 
SetBlipColour(blip1, 48) // Colours also can find there
SetBlipAsShortRange(blip1, true)
BeginTextCommandSetBlipName("STRING")
AddTextComponentString('Pet Shop')
EndTextCommandSetBlipName(blip1)
`