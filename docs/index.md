# New in Onyx 4.32

## **New Features**  

### **Dylos**

*   [Parameter Weight Sub-Channels](Programming/DyLOS/Parameter_Weight_Sub-Channels.htm)
    
*   [Virtual Gobo Mapping](Programming/DyLOS/Mapping/Virtual_Gobo_Mapping.htm)
    
*   [Group Masking](Programming/DyLOS/Mapping/Group_Masking.htm)
    

### **Cue Playback**

*   [Parameter Tracking Release](Playback/Tracking/Parameter_Tracking_Release.htm)
    
*   [Tracking Cue Skip](Playback/Tracking/Tracking_Cue_Skip.htm)
    

### **Programming**

*   [Quick Access Mode Fade And Delay](Programming/Manipulating_Fixtures/Quick_Access_Fade_And_Delay.htm)
    

### **System**

*   [Audio LTC Timecode Input Processor](Programming/DyLOS/Input_Processors/Audio_LTC_Timecode_Input_Processor.htm)
    
*   [AnyDesk Remote Support](System/AnyDesk_Remote_Support.htm)
    

### Updated Menus

*   [Timecode Settings](Menus/System_Settings/IO_Settings/Timecode_Settings.htm)
    
*   [Input Sources](Programming/DyLOS/Input_Sources.htm)
    
*   [NDI Settings](Networking/NDI.htm)
    
*   [Control Surface Backlight Settings](Hardware_Assignment_Settings/Control_Surface_Backlight_Settings.htm)
    

**4.32 Overview** 
------------------

Onyx 4.32 brings powerful new tools for even greater control and flexibility in your lighting workflow. The introduction of **S****KIP** **cues** and **parameter release within cues** gives you precision over tracking like never before. A new **LTC Audio Timecode Input Processor** expands synchronization options, while **improved FADE/DELAY/WEIGHT editing** streamlines programming.

This update also introduces a brand-new **weight system**, allowing dynamic control over transitions by blending between direct cue and Dylos output per parameter. Additionally, new **virtual gobo mapping** unlocks advanced texture effects, and a **dual fixture group mapping mask** provides more flexible fixture control. Improved **show backup naming** ensures better organization, while **AnyDesk remote support**, expanded **Focusrite ASIO driver compatibility**, and numerous bug fixes enhance overall system stability.

**Discover the latest enhancements and take your show to the next level!**

 

### Feature Overview Video[![](../assets/images/image349.png)](https://files.obsidiancontrol.com/s/4_32_Feature_Video)

**Release Notes**
-----------------

4.32.1307 (07/11/2025)  
/======================  
ONYX-1261    Fixed DMX timings not showing on NX1 and NX2  
ONYX-1258    Fixed not listening to Art-Net timecode after boot  
ONYX-1257    Fixed parameter window reverting to live values when editing highlight  
ONYX-1255    Fixed the highlight filter bug in the programmer windows  
ONYX-1254    Fixed list view not being scrollable when filling slightly more than one page  
ONYX-1245    Additional hardware support  
ONYX-1256, ONYX-1253    Minor fixes and improvements  
ONYX-1042    Added support for NX W  
ONYX-1252    Fixed DyLOS not using very small ring-segment parts  
ONYX-1251    Fixed highlight values permanently edited after cloning  
ONYX-1248    Fixed audio error  
ONYX-1247    Fixed placing fixture multiple times on 2D plan page, causing pixel mapping problems  
ONYX-1246    Fixed faulty color tint parameters in legacy fixture types (causing show files not being able to load)  
ONYX-1244    Fixed UI becoming unresponsive or crashing when navigating complex views on multiple displays  
ONYX-1243    Ignore updating fixture types that were previously enabled for virtual intensity, but are no longer eligible due to improvements in the AtlaBase translator (causing show files not being able to load)  
ONYX-1240    Fixed adding fixture groups to 2D plan while mirror is enabled  
ONYX-1234    Fixed exporting large patch reports on consoles  
ONYX-1233    Fixed the preparation of fixtures that only had (0%) intensity value recorded in mark cue  
ONYX-1231    Fixed FX wave/step size calculation when fan spread across mask steps is enabled  
ONYX-1230    Fixed fixture name not being visible on 2D plan when bright colors are assigned  
ONYX-1229    Fixed network interface enumeration issues on systems with MAC address pass-through enabled (assigning same MAC address to multiple interfaces)  
ONYX-1227    Fixed screen rotation issues when connecting/disconnecting external screens to NX2/NX4 consoles that run Windows 11 (IoT Enterprise)  
ONYX-1224    Fixed the "new fixture" wizard potentially causing fixture(s) to be created twice  
ONYX-1217    Fixed using physical encoders to set effect values for combined/linked channels, sometimes leaving FX wave and step calculations at zero  
ONYX-1213    Improved NX-K & NX1 encoder responsiveness  
ONYX-1215    Fixed fixtures with multiple DMX (start) addresses not being rendered on 2D plan  
ONYX-1245, ONYX-1242, ONYX-1237, ONYX-1228    Visual improvements

4.32.1302  
\======================  
ONYX-1226    Fixed freeze when cloning cues containing time and weight values  
ONYX-1225    Fixed weight range 50% ("DEFAULT") -> 100% ("CUE")  
ONYX-1222    Fixed missing segments on some combined fixtures (like ACME Tornado) in 2D plan  
ONYX-1220    Fixed being able to disable NDI public group when no other groups available  
ONYX-1218    Fixed MSC command format popup not showing on small screens  
ONYX-1042    Fixed licensing issues for some PC systems, fader mini module (NX4, M6 with ONYX upgrade kit) in ConsoleTester

**Onyx 4.32.1301**  
 

**New Features**  
\======================  
\- ONYX-939 Added LTC Audio timecode input processor  
\- ONYX-1109 Added AnyDesk to diagnostic tools for remote support  
\- Added "Release" value in cues to release a channel from tracking through subsequent cues  
\- Added new "Skip" cue option (default ON) for genuine cue-only behavior  
\- Added dual fixture group mapping mask with logical combination options  
\- Added gobo pixel mapping mode  
\- Added weight sub channels to cross fade direct <-> pixel-mapped output per parameter  
\- Added fade/delay/weight editing modes behind double click on LINK button  
\- Added fixture group mapping mask  
\- Added palette support to effect slots  
\- ONYX-1137 Added NDI Discovery Service support

**Updates / Improvements**  
\======================  
\- ONYX-1025 Improved parameter encoder behavior and FADE/DELAY/WEIGHT editing toggling  
\- ONYX-74 Improved show backup naming with show name, time, and build in filename  
\- ONYX-1112 Allowed installation of 4th gen Focusrite ASIO drivers and uninstallation of 3rd-party ASIO  
\- Improved gobo pixel mapping mode  
\- Improved channel/parameter group buttons with CLEAR/DEFAULT/LOAD/SET SELECTION  
\- ONYX-1042 Added NX W control surface support  
\- ONYX-1187 Revised license schemes to "ONYX Key"  
\- ONYX-1201 Fixed FADE/DELAY/WEIGHT keyboard shortcuts not working  
\- ONYX-1198 Support ring segments for pixel mapping  
\- ONYX-846 2D plan improvements: extended zoom out and page map panel  
\- ONYX-1179 Added support for NDI Groups (not just "Public")  
\- ONYX-1155, ONYX-1138, ONYX-1092, ONYX-1075 Visual fixes and improvements

**Fixes**  
\======================  
\- ONYX-1088 Fixed Patch help  
\- ONYX-1094 Fixed \[GROUP\] \[ENTER\] and \[GROUP\] \[FULL\] behavior  
\- ONYX-1115 Fixed DyLOS color palette selection/preview issues  
\- ONYX-1037 Fixed parameter release visuals and "RELEASE" indicators after recording  
\- ONYX-1112 Fixed uninstall of Focusrite packages and mixer access to multiple ASIO devices  
\- ONYX-1065 Fixed intensity output in cuelist ID 10,000 and up  
\- ONYX-1116 Fixed software grand master display  
\- ONYX-1124 Fixed "Division by zero" error during two-finger scroll  
\- Fixed WEIGHT not applied to Pan/Tilt and others  
\- Fixed CLEAR/DEFAULT/LOAD via right-click  
\- Fixed FADE/DELAY OUT applying during IN fanning  
\- Fixed CLEAR SELECTION filters in programmer  
\- ONYX-1156 Fixed CLEAR FIXTURE behavior  
\- Fixed weight tracking and clearing through filter  
\- Fixed CLEAR on parameter group in FADE/DELAY/WEIGHT mode  
\- ONYX-778 Fixed RGB flags in 2D plan  
\- ONYX-846 Visual fixes in 2D plan  
\- ONYX-1042 Fixed NX W rendering to multi-target displays  
\- ONYX-1204 Fixed CMY emitters rendering  
\- ONYX-1180 Fixed live output and programmer loading bugs  
\- ONYX-1184 Parameter groups no longer page after FADE/DELAY/@/RECORD  
\- ONYX-1185 Fixed stuck cuelist after "GO" MIDI macro  
\- ONYX-1104 Fixed MIDI macros forcing playbacks to full  
\- ONYX-1105 Fixed "Reset BPM" key  
\- ONYX-1119 Fixed audio stutter from audio-only NDI  
\- ONYX-1144 Fixed FADE/DELAY command line behavior and parameter scope  
\- ONYX-1151 Fixed DyLOS defaults on show load  
\- ONYX-1154 Fixed Mx/button OSC feedback issues  
\- ONYX-1162 Fixed main playback LED feedback inconsistencies  
\- ONYX-1172 Fixed status and selection info in title bar  
\- ONYX-1174 Fixed single-digit preset entry  
\- ONYX-1181 Fixed Ableton Link reconnection  
\- ONYX-1167 Fixed beat tapping  
\- ONYX-1067 Fixed fixture type color popup closing  
\- ONYX-1087 Fixed patch conflict errors  
\- ONYX-1089 Fixed fixture park status refresh  
\- ONYX-1127 Fixed DyLOS preset mapping limits  
\- ONYX-1147 Fixed Sidebar touch selection  
\- ONYX-1158 Fixed freeze with virtual dimmer fixtures (dup. of ONYX-1157)  
\- ONYX-1159 Fixed weight data updates in cues  
\- ONYX-1161 Fixed Windows 8 USB stick visibility  
\- ONYX-1165 Fixed 2D plan page access on non-installing user accounts  
\- ONYX-1169 Limited preset number to 9999  
\- ONYX-1171 Fixed fixture sync with Capture visualizer  
\- ONYX-1196 Fixed Ableton Link tempo reset on close  
\- ONYX-1194 Fixed 2D plan Groups tab color bug  
\- ONYX-1192 Fixed preset name display  
\- ONYX-1186 Fixed local NDI source detection  
\- ONYX-1178 Fixed emitter rendering order in 2D plan  
\- ONYX-1148 Fixed group drag-select in 2D plan live mode  
\- ONYX-1108 Fixed X-Net dropouts

**Miscellaneous**  
\======================  
ONYX-1075, ONYX-1084, ONYX-1121, ONYX-1136, ONYX-1109, ONYX-1123, ONYX-1130, ONYX-1133

 

©2025  Obsidian Control Systems. All Rights Reserved.

[![](../assets/images/Homepage/Obsidian_PrimaryWordmark_RGB_White.png)](http://obsidiancontrol.com)