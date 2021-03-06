# Collection of Taranis LUA Telemetry Scripts

<b>How to use:</b><br>
Since each telemetry script has his own folder structre, please follow the instructions of each script.


<h2>AnySense LUA Script</h2>

<img src="https://raw.githubusercontent.com/cemizm/TaranisLuaScripts/master/AnySense/telem1.png" />

<h3>Functions</h3>
<ul>
  <li>Lipo monitoring (percentage, lowest cell, current, capacity)</li>
  <li>Naza Flight Mode and GPS quality</li>
  <li>Internal timer which starts and stops automaticaly on arming / disarming</li>
  <li>Flight- and Home-direction</li>
  <li>Background tasks to e.g. set home point, even when script is not shown</li>
  <li>Resets automaticaly distance and altitude when Naza sets Home Point</li>
</ul>

<h3>How To:</h3>
1. Download the <a href="https://github.com/cemizm/TaranisLuaScripts/archive/master.zip">telemetry screen script</a>
2. Create a folder on the radio microSD card called SCRIPTS (if it does not already exist)
3. Put the <b>content</b> of the AnySense folder into /SCRIPTS/ folder
4. Rename the modelname folder to the same name as the model that will use the script
5. If needed, modify the settings section in the telem1.lua

That is it. The new telemetry screen should now automatically appear for the model.

The telem2.lua script is just an example how to split the AnySense combined value.
