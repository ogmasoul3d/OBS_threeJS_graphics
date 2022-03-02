# OBS_threeJS_graphics
<img align="left"  src="https://github.com/ogmasoul3d/OBS_threeJS_graphics/blob/main/OBS%20setup%20stormtrooper.png"> Some fun stuff, creating 3d gfx elements with transparent BG for use in OBS

This is just a small plaything. I wanted to test three.JS for creating realtime 3d rendered elements that I could add to a OBS stream.

I was surprised that I could output it with transparent backdrop so you get a perfect alpha for the 3d element.
Just took some threeJs examples and made sure they rendered with alpha and no background.


<br>

--------

Installation:
=========
0. Clone this to a local folder
1. in OBS, create a Browser element
2. check "Local File" chk box. If you just want to run it directly from the folder. 
3. Browse to the HTML file you want to show inside this REPO.
4. Add the following css to be sure that you do not get an background color:
```
body { background-color: rgba(0,0,0,0)!important }; margin: 0px auto; overflow: hidden; }
```

![Alt text](https://github.com/ogmasoul3d/OBS_threeJS_graphics/blob/main/OBS%20setup.png "add a Browser element and point to the local html file")
