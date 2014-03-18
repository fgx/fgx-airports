Read Me
=======

### Live Demo

[Display Mag R1](  http://fgx.github.io/fgx-airports/cookbook/display-mag/latest/index.html)

* Careful: this is currently a browser resource hog

## Concept
Display the declination of the earth's magnetic field in 3D over its entire surface at a variety of altitudes

## Features
Displays the declination at every ten degree of latitude and longitude over the surface of the globe - 576 locations  
Displays declination at each location at five different altitudes  
Displays the differences in the declination in time in tenths of years at lowest level only

## Road Map
Currently to movements are too slight for the human eye to see.  
Need to invent some kind of augmented physics such that the changes in relative declination over time are visible to the human eye and perceptible by the brain. 

## Issues /Bugs
Very slow because demo uses Three.js 3D boxes as the pointers  
Should use use Three.js particles instead    
Also should not erase and redraw each frame, but merely carry out updates  
The latter is not a simple task. Requires monitoring the diffs between to 4x4 matrices   

## Project Links

See also:

Geoff McLane's [WMM - World Magnetic Model]( http://geoffair.org/fg/map-test2/wmm-test.html )

National; Geophysical Data Center  

* [Magnetic Field Calculators]( http://www.ngdc.noaa.gov/geomag-web/#declination )
* [The World Magnetic Model and Associated Software]( http://www.ngdc.noaa.gov/geomag/WMM/soft.shtml )

WMM JavaScript routine from

* [Libraries and Web Services for Outdoor Pursuits Mashups]( http://www.bdcc.co.uk/Gmaps/Services.htm] )
* http://www.bdcc.co.uk/Gmaps/WorldMagneticModel.js 

You have two ways of viewing the Display Mag files:

* Web pages hosted on GitHub: [fgx.github.io/fgx-airports/cookbook/display-mag]( http://fgx.github.io/fgx-airports/cookbook/display-mag/readme-reader.html "View the files as apps." ) <input value="<< You are now probably here." size=28 style="font:bold 12pt monospace;border-width:0;" >  
* Source code on GitHub: [github.com/fgx/fgx-airports/ ... /cookbook/display-mag/]( https://github.com/fgx/fgx-airports/tree/gh-pages/cookbook/display-mag "View the files as source code." ) <scan style=display:none ><< You are now probably here.</scan>

FGx home page: [fgx.ch]( http://www.fgx.ch )

## Copyright Notice and License

[FGx copyright notice and license]( https://github.com/fgx/fgx.github.io/blob/master/fgx-copyright-notice-and-license.md )

This app is at an early and volatile stage. Not all licensing requirements may have been fully met let alone identified. It is the intension of the authors to play fair and all such requirements will either be met or the feature in question will turned off.


## Change Log

2014-03-18 ~ Theo

* R1 added



