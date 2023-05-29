# Cortex Documentation - API Documentation

<b><font color='#fffb12'>Invoke/Fire Events:</font></b>

<b>• Fire Recall</b> - ```API:Fire('Fire_Recall', true/false, 1)``` - to initiate fire recall to floor 1

<b>• Fire Service Phase 2</b> - ```API:Fire('Phase_2', true/false)``` - enables/disables phase 2 of fire service

<b>• Stop</b> - ```API:Fire('Stop', true/false)``` - stops/unstops the elevator

<b>• Call Requesting</b> - ```API:Fire('Request_Call', 1)``` - sends a call request to the elevator for the 1st floor

<b>• Door Open</b> - ```API:Fire('Door_Open', {'Front','Rear'})``` - opens the front and rear doors. If no table is provided, all doors will attempt to open instead

<b>• Door Close</b> - ```API:Fire('Door_Close', {'Front','Rear'})``` - closes the front and rear doors. If no table is provided, all doors will attempt to close instead

<b>• Door Nudge</b> - ```API:Fire('Door_Nudge', {'Front','Rear'})``` - nudge closes the front and rear doors. If no table is provided, all doors will attempt to close instead

<b>• Floor Locking</b> - ```API:Fire('Lock_Floors', {1,2})``` - locks the 1st and 2nd floors

<b>• Floor Unlocking</b> - ```API:Fire('Unock_Floors', {1,2})``` - unlocks the 1st and 2nd floors

<b>• Hall Floor Locking</b> - ```API:Fire('Lock_Hall_Floors', {1,2})``` - locks the 1st and 2nd floor call buttons

<b>• Hall Floor Unlocking</b> - ```API:Fire('Unlock_Hall_Floors', {1,2})``` - unlocks the 1st and 2nd floor call buttons