# Cortex Documentation - API Documentation

### <b><font color='#fffb12'>Invoke/Fire Events:</font></b>

<b>• Fire Recall</b>
```lua
API:Fire('Fire_Recall', true/false, 1)
```
Initiates fire recall to floor 1

<b>• Fire Service Phase 2</b>
```lua
API:Fire('Phase_2', true/false)
```
Enables/disables phase 2 of fire service

<b>• Stop</b>
```lua
API:Fire('Stop', true/false)
```
Stops/unstops the elevator

<b>• Call Requesting</b>
```lua
API:Fire('Request_Call', 1)
```
Sends a call request to the elevator for the 1st floor

<b>• Door Open</b>
```lua
API:Fire('Door_Open', {'Front','Rear'})
```
Opens the front and rear doors. If no table is provided, all doors will attempt to open instead

<b>• Door Close</b>
```lua
API:Fire('Door_Close', {'Front','Rear'})
```
Closes the front and rear doors. If no table is provided, all doors will attempt to close instead

<b>• Door Nudge</b>
```lua
API:Fire('Door_Nudge', {'Front','Rear'})
```
Nudge closes the front and rear doors. If no table is provided, all doors will attempt to close instead

<b>• Floor Locking</b>
```lua
API:Fire('Lock_Floors', {1,2})
```
Locks the 1st and 2nd floors

<b>• Floor Unlocking</b>
```lua
API:Fire('Unock_Floors', {1,2})
```
Unlocks the 1st and 2nd floors

<b>• Hall Floor Locking</b>
```lua
API:Fire('Lock_Hall_Floors', {1,2})
```
Locks the 1st and 2nd floor call buttons

<b>• Hall Floor Unlocking</b>
```lua
API:Fire('Unlock_Hall_Floors', {1,2})
```
Unlocks the 1st and 2nd floor call buttons