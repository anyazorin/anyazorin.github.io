---
title: "LED Mushroom Hat"
summary: "Music reactive LED Mushroom Hat"
coverImage: "/assets/mushroom/mushroom_prev.gif"
order: 5
---
This is a fun and simple project I did with friends, where we made cardboard mushroom hats with sound reactive LEDs.

### Cardboard structure
The simple hat structure was modeled in Fusion360, then put through Slicer for Fusion 360 with a radial slice to get the layout, which we could then laser cut from cardboard. 
<div style="display: flex; gap: 8px;"><img src="https://raw.githubusercontent.com/anyazorin/mushroom_hat/refs/heads/main/img/img_beforeslice.png" style="width: 50%; object-fit: contain;"><img src="https://raw.githubusercontent.com/anyazorin/mushroom_hat/main/img/img_afterslice.png" style="width: 50%; object-fit: contain;"></div>

This let us have a sturdy, lightweight cardboard hat.

### LEDs
We cut notches in the hat so that we could place the LEDs in three layers. A friend soldered them together, and then to an ESP8266, which allowed us to program the lights using [WLED](https://kno.wled.ge/) and [LEDFX](https://www.ledfx.app/). The ESP8266 was connected to a portable battery so that we could wear the hats and move around. The ESP8266 has WiFi, so we were able to control the LEDs from our phones. 

<div style="display: flex; justify-content: center;"><img src="https://raw.githubusercontent.com/anyazorin/mushroom_hat/main/img/ledmushroom.png" style="width: 66%;"></div>

### Finishing Touches
I cut large red fabric covers with holes to go over the top of the mushroom, and hot glued tulle to the bottoms for aesthetics. I then added a large yarn rope so they would stay on our heads, and the mushrooms were done! :)

<div style="display: flex; justify-content: center;"><img src="https://github.com/anyazorin/mushroom_hat/raw/main/img/mushroomLED.gif" style="width: 66%;"></div>