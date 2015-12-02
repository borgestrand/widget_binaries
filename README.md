
SDR Widget and Audio Widget binaries
====================================

How to reinstall DAC firmware: Read from line 508 of the <a href="https://github.com/amontefusco/sdr-widget/blob/audio-widget-experimental/AW_readme.txt">Audio Widget Readme file</a>.





<b>File:</b> <a href="https://github.com/borgestrand/widget_binaries/raw/master/awx_20151202_ext_pwr_01.elf">awx_20151202_ext_pwr_01.elf</a>
<b>Date:</b> 20151202
<b>Author</b>: Borge
<br>
Henry Audio USB DAC 128 mkII experimental firmware for better operation with external power and iPad/iPhone.
<br>


<b>File:</b> <a href="https://github.com/borgestrand/widget_binaries/raw/master/awx_20140918_mkII_RC03.elf">awx_20140918_mkII_RC03.elf</a>
<b>Date:</b> 20140918
<b>Author</b>: Borge
<br>
Henry Audio USB DAC 128 mkII shipping firmware without debug.
<br>


<b>File:</b> <a href="https://github.com/borgestrand/widget_binaries/raw/master/awx_20140917_silent.elf">awx_20140917_silent.elf</a>
<b>Date:</b> 20140917
<b>Author</b>: Borge
<br>
An attept to prevent (very rare) metallic noise at some player start events. This build has no debug information
<br>
NB: This is an beta release


<b>File:</b> <a href="https://github.com/borgestrand/widget_binaries/raw/master/awx_20140917_debug.elf">awx_20140917_debug.elf</a>
<b>Date:</b> 20140917
<b>Author</b>: Borge
<br>
An attept to prevent (very rare) metallic noise at some player start events. This build has debug information on RS232 and pin toggles.
<br>
NB: This is an beta release


<b>File:</b> <a href="https://github.com/borgestrand/widget_binaries/raw/master/ASIO_bin_patch_20140429.zip">ASIO_bin_patch_20140429.zip</a>
<b>Date:</b> 20140429
<b>Author</b>: Borge / Ti / Nikolay
<br>
Initial release of 64-bit ASIO driver, minor bug-fix in 32-bit ASIO driver, 32 and 64-bit WidgetTest RAM based .wav file player. Manual install - you 
must consider readme.txt
<br>
Built with libusbK 3.0.5.16
<br>
NB: This is an alpha release


<b>File:</b> <a href="https://github.com/borgestrand/widget_binaries/raw/master/WidgetTest_20140410A.tgz">WidgetTest_20140408A.tgz</a>
<b>Date:</b> 20140410
<b>Author</b>: Borge
<br>
Play wav files with Windows UAC2 driver, bypassing ASIO. Now with less CPU consumption, more playback options, callback monitoring
<br>
Built with libusbK 3.0.5.16
<br>
NB: This is an alpha release


<b>File:</b> <a href="https://github.com/borgestrand/widget_binaries/raw/master/AWSetup_20130211.zip">AWSetup_20130211.zip</a>
<b>Date:</b> 20130211
<b>Author</b>: Nikolay, build by Borge
<br>
Windows UAC2 ASIO driver and WidgetControl program. It has these major updates:
<br>
1) Built with libusbK 3.0.5.16
<br>
2) Improved Windows 8 support
<br>
3) Increased stability for 44.1/88.2/176.4 playback

<b>File:</b> <a href="https://github.com/borgestrand/widget_binaries/raw/master/audio-widget-20131208clean_RC.elf">audio-widget-20131208clean_RC.elf</a>
<b>Date:</b> 20131210
<b>Author</b>: Borge Strand-Bergesen
<br>
Release candidate firmware for AB-1.1 and AB-1.2. No debug features


<b>File:</b> <a href="https://github.com/borgestrand/widget_binaries/raw/master/awx_20131115c2.elf">awx_20131115c2.elf</a>
<b>Date:</b> 20131115 
<b>Author</b>: Borge Strand-Bergesen
<br>
Firmware for AB-1.2 and AB-1.1 with gracefull degradation through sample skip/insert. Gracefull degradation ONLY kicks in where there would otherwise be metallic noise. Normal playback should be unaffected.


<b>File:</b> <a href="https://github.com/borgestrand/widget_binaries/raw/master/audio_widget_20130902.elf">audio_widget_20130902.elf</a>
<b>Date:</b> 20131010 
<b>Author</b>: Borge Strand-Bergesen
<br>
Firmware for AB-1.2 and AB-1.1 with improved UAC1 enumeration for OS X and general code cleanup. This file contains debug features.



Add new uploads to the top of this file.


Formatting information for this file:
<br>
https://help.github.com/articles/github-flavored-markdown
<br>
http://daringfireball.net/projects/markdown/syntax