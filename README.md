# ESO-Racing-Panel

Racing Panel. Proudly Sponsored By N-wah Leaf Importers. For all your racing needs!

Racing Panel is an Elder Scrolls Online calibrated speedometer Addon.

> When Racing Panel is installed, please go into your controls and set a hot-key for the Settings Panel. Racing Panel has its own section in the keybinding pages. The default for the settings Panel is UP (up-arrow). The Settings Panel is a popup panel so it can be easily brought up for changes while riding or racing.

Racing Panel provides a digital readout of your character's current speed, in miles per hour (mph), kilometers per hour (kph) or meters per second (m/s). This speedometer can be placed at the edge of your screen for questing, or in the bottom center of your screen for racing. Racing panel also provides a graphical quick-glance speed indicator, a graphical remaining-stamina indicator for both foot or mounted stamina, graphical Major Expedition and Major Gallop remaining-buff displays, and a graphical Minor Expedition display.

You can enable Racing Panel while on foot, while mounted, or both or neither. You can arrange and display all, some, or none of Racing Panel's indicators, per character. Racing Panel will remember your settings.

### Calibrated Map Scale Data is included!

Racing Panel works for all major overland maps, cities, towns, and villages. Each map has a built-in GPS for Addon developers to use. However, each map has a unique scale. Some maps have coordinate grids twenty times larger than other maps. This means, if you run for a while on one map, you may have gone .034 map units. On another map, you can run for the same time at the same speed, and yet you have gone .184 map units.

For Racing Panel to be accurate in a given map, a scaling factor must be determined for that map. Map Scale Data is included in Racing Panel for 99 maps, all of which are mount-friendly. A scale sampling tool is integrated into Racing Panel. This sampling tool is fully documented (see Documentation.lua), and any map can be easily scaled, and the scaling data can then be added to your own MapScaleData.lua file, and your speedometer will now work on that map.

The speedometer is much more accurate than it needs to be. You can hit a small rock or go down one step, and it will impact your forward velocity. It's accurate enough that you can SEE what the game does to your forward speed as you run or ride.

### The Default Reference Speed
    
How "fast" is the default reference speed?
* The default speed can be called jogging, rather than walking.
* In ESO, Walking is 30% of jogging.
* In ESO, Sprinting is 140% of jogging.

```
Default Speeds (on foot)
------------------------
  walk    1.35 m/s    3.01986 mph    4.86 kph    walk
   jog    4.50 m/s   10.06620 mph   16.20 kph    jog
sprint    6.30 m/s   14.09268 mph   22.68 kph    sprint
```

Note: Racing Panel allows for a calibration adjustment of the default 1.35 m/s walking speed, from 1.25 m/s (-7.4%) to 1.60 m/s (+18.5%).

Good Reasons(tm) for a 3.0 mph, 1.35 m/s walking speed:
  * Our walking speed is just under a common crosswalk measurement (people move slightly faster in crosswalks).
  * A 3-mph treadmill exactly matches our walking footfall animation. Check it out yourself, on YouTube!
  * It's just below the speed used by the Design Manual for Roads and Bridges.
  * It's just above the speed recommended by The Transport for London.
  * The walk, jog, and sprint numbers are all relatively wonderfully round.

Enjoy! If you like it, that's great! No gifts or contributions required or desired.
I'll accept gifts of random cool furniture if you absolutely insist.
Please report bugs on ESOUI.com, and suggestions are welcome in-game.
I'm @Undyne at N'Wah Leaf Importers on PC EU!
