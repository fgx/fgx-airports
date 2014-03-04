Display CSV Read Me
===================

### Live Demo

Display CSV
<iframe src="http://fgx.github.io/fgx-airports/cookbook/display-csv/latest/index.html" width=100% height=500px class='overview' >
There is an `iframe` here. It is not visible when viewed on github.com/fgx. To view, please go to fgx.github.io. See 'Project Links' just below.
</iframe>

[ Display CSV R2 ]( http://fgx.github.io/fgx-airports/cookbook/display-csv/latest/index.html )

* Zoom in close to objects to view the ASCII data for the object

## Concept
To show as many things in 3D as possible all at once and still have the data for each thing instantly available 

Currently, the demo is really quite ugly. Prettiness is not an objective here. Neither is accuracy. 

Data is not formatted in any way. The text records, as of this writing, are probably synced with incorrect graphics. These are not the issues of import here and now. 

What this demo is about: This is a proof of concept for three things:

1. You can load a good number of megabytes - perhaps twenty or so - with hundreds of thousands of data points - all within a time limit acceptable to most users.
Data that formerly needed to be accessed via a database - may now be accessed as static files.

2. Huge amounts of data can be viewed graphically in 3D with real-time zoo, pand and rotate all at 60 frames per seconds

3. The text and data 'behind' or relating to the graphic image of the data may be accessed and displayed in real time.


## Features

* Reads 274,954 records from eight ASCII CSV files
* The entire X-Plane / FlightGear database
* Displays it all in 3D all at once
* Loads in seconds
* Rotate, pan and zoom at 60 FPS
* 'Nearby' data displayed in real-time for 200 closest objects

## Road Map

* Better display of ASCII data


## Issues /Bugs

* Needs prettifying
* Color types being assigned inappropriately
* Colors do not update as you move close to the object


## Project Links

You have two ways of viewing the FGx files:

* Code hosted on GitHub: [fgx.github.io]( http://fgx.github.io/fgx-/ "view the files as apps." ) <input value="<< You are now probably here." size=28 style="font:bold 12pt monospace;border-width:0;" >  
* Source code on GitHub: [github.com/fgx]( https://github.com/fgx/fgx-/ "View the files as source code." ) <scan style=display:none ><< You are now probably here.</scan>

FGx home page: [fgx.ch]( http://www.fgx.ch )

## Copyright Notice and License

[FGx copyright notice and license]( https://github.com/fgx/fgx.github.io/blob/master/fgx-copyright-notice-and-license.md )

This app is at an early and volatile stage. Not all licensing requirements may have been fully met let alone identified. It is the intension of the authors to play fair and all such requirements will either be met or the feature in question will turned off.


## Change Log

2014-03-03 ~ Theo

* R2 up. More objectification
* Adds limited display of altitudes
* Sets colors by type in a broken way  
* Adds display of data for nearby objects  

2014-03-01 ~ Theo

* R1 up. 272,000 objects loaded from ASCII CSV files and displayed in 3D quite quickly




