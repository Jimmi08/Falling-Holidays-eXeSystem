/*************************** README *******************************************/

To get this plugin work in your theme you need to insert this there:

One way:   put menu in theme $LAYOUT['_header_'] or just some layout
{MENU: path=fallingholidays/XMasLights}  
{MENU: path=fallingholidays/Snow3D}

Second way:  put content of  XMasLights_menu.php in your theme.php

<div id='lights'>
  <!-- lights go here -->
 </div>
<div id='Div1' class='snow'></div>

New way:
just set correct HTML tag and date values in admin prefs