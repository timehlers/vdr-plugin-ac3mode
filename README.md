# vdr-plugin-ac3mode

This is a "plugin" for the Video Disk Recorder (VDR).

Written by:                  Michael Baer (Miki1@gmx.net)
Adjusted for VDR >= 1.7	     Tim Ehlers

See the file COPYING for license information.

Description:
If a channel broadcasts "Dolby Digital" (AC3) Sound, there is no information 
about the number of channels (Dolby Stereo, 5.1 etc.) actually 
available.
This plugin will display this information in a short hint text, whenever
the Dolby Digital mode is changed.

Additionally, a main menu entry is added, which will also display the 
selected Dolby Digital type.
If no Dolby track is selected, "PCM Sound" will be displayed.

Note that the plugin uses svdrpsend.pl for displaying the hint text.
Therefore, this file should be in the path of the user running VDR.
