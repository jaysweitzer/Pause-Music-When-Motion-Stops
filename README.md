# Pause-Music-When-Motion-Stops
Pause Music When Motion Stops

Install the 2 SmartApps in IDE and Publish.

Go into Automation > SmartApps 
Add a SmartApp > MyApps, then select 'Pause Music When No Motion'

Add music players, and select the motion sensor to monitor per player
Select the number of minutes to wait before pausing the music

The default automation is 'Pause <player name> after <x> minutes when no motion on <motion sensor>

The child SmartApp will automatically set a timer on installation so that the music will pause even if the motion sensor has not been triggered in the <Minutes> period.
