# Max/MSP Patches, Abstractions, Externals, RNBO, VSTs, and Ableton Max for Live 

###br.utility.gain-1.0   
By Brian Riordan  
[guaguanco127@gmail.com](mailto:guaguanco127@gmail.com)  
[brianriordanmusic@gmail.com](mailto:brianriordanmusic@gmail.com)  
Additional programs can be found here: [https://github.com/guaguanco127](https://github.com/guaguanco127)

These files were created with Max/MSP version 8.5.6, or RNBO 1.2.3. Instructions on how to install below. 

## Table of Contents

[br.utility.gain-1.0 Info](#info)   
[Ableton Max for Live Device](#M4L) Change this to hyperlink  
[Max/MSP Abstraction](#Max) Change this to hyperlink   
[Max/MSP External](#Max) Change this to hyperlink    
[Max/MSP RNBO for External or VST](#RNBO) Change this to hyperlink 


## <a name="info"></a>br.utility.gain-1.0 Info

This is a basic patch/external/plugin/device that allows the user to adjust a the volume of a stereo signal. The decibel range is from -72 dB to +35 dB.
-72 dB is converted to negative infinity dB.
Currently works in any sample rate or bit depth.  

## <a name="M4:"></a>Ableton Max for Live Device  
 

## EVERYTHING BELOW IS A PLACEHOLDER TO BE DELETED

## Table of Contents

[br.utility.gain-1.0 Info](#plugininfo)  
[Instructions on installing the plugin](#installation)  
[Instructions on using as an abstraction in Max/MSP](#maxmsp)  
[Max for Live Device](#maxforlive)

## <a name="plugininfo"></a>BR-Utility-Gain-1.0 Info 

Plugin Name: BR-Utility-Gain-1.0 from 10-29-2023  
Plugin Manufacturer Name: guaguanco127  
Plugin Manufacturer Code: U001

A basic audio plugin for adjusting the volume of a stereo signal. 
The decibel range is from -72 dB to +35 dB.
-72 dB is converted to negative infinity dB.
Currently works in any sample rate or bit depth. 


## <a name="installation"></a>Instructions on installing the plugin:

1: Install your favorite audio software (DAW) on your computer. Make sure the software is off when installing the plugin
 
2: Locate your plugin plug-in directory. (Usually called a VST directory)  

Some software has this built in to the program file, in which case you may skip this step and proceed to the next one. A DAW such as Ableton Live requires you to do this manually, like so:  

Go to the "Options" menu and select "Preferences".  
Under "Preferences", select the "File Folder" menu.
Click the "Browse" button next to "VST Plug-In Custom Folder".  
Select the folder you would like Ableton to use for VST Plug-Ins.
Confirm that the "Use VST Plug-In Custom Folder" option is turned on, and the file path listed under "VST Plug-In Custom Folder" leads to the folder you just selected.

For VST3:   
For Windows use BR-Win-Utility-Gain-1.vst3   
For Macintosh use BR-Mac-Utility-Gain-1.vst3 or BR-AU-Utility-Gain-1.component

3: Reopen your DAW and search for the plugin the same way you'd open any effect in a track

## <a name="maxmsp"></a>Instructions on using as an abstraction in Max/MSP:


For Max/MSP, create a patch inside a folder. Then copy and paste BR-Utility-Gain-1.0.maxpat inside of that folder. Create a new object with the name BR-Utility-Gain-1.0 and you can use it as an object in your main patch. 

This abstraction was created using gen~ 

The basic version of this abstraction is called BR-Utility-Gain-Gasic-1.0.maxpat
It has the same functionality but uses MSP instead of gen~
The purpose of the basic version is for beginners to be able to learn how to program using Max/MSP, and to compare and contrast the same concept in gen~ 

The BR-Utility-Gain-RNBO-1.0.maxpat version is designed for those who want to learn from, or observe the RNBO methods I used to create all of these plugins. 

## <a name="maxforlive"></a>Max for Live Device:

Coming soon.....
 