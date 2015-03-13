# 1.13 #
  * New: Added option to activate (somewhat) smoother text scrolling, and drawing in general > more CPU usage
  * Improvement: Rating drawing on the aero peek is similar to what you see on the Bento skin, the missing stars till 5 are "padded" with bulbs
    * ex: ★ ★ ★ ● ●
  * Improvement: Album art is not forced to square anymore, it keeps aspect ratio
  * Fix: Some of the Winamp exit crashes / hangs, and some other minor ones... please report if you notice any more
  * (Some other changes I might forgot)

# 1.12 #
  * New: Added option to disable mouse wheel volume control. It caused performance drop on certain systems and incompatibilities with ObjectDock.
  * Fix: A bug with mouse wheel volume control, when the volume jumped back to 100 after scrolling below 0.
  * Fix: A text centering bug when iconic background was enabled, and no album art was found
  * Improvement: Re-added MusePack file format support for album art, using TagLib
  * Fix: Some title and artist formatting bugs; Missing last character from artist and first character from title
  * Improvement: Some changes to recent and frequent jump list categories. The plug-in doesn't add the played song to the recent docs if it's already there by some other application.
  * Translations: Added 1 line, change 'favorite' line

# 1.11 #
  * New: **Volume can be controlled using mouse wheel scroll** when hovering over the Winamp icon on the taskbar.
  * Improvement: **Album art is taken directly from Winamp**, so everything that is supported there, is used as aero peek background.
  * Improvement: Longer **text lines will scroll** on the aero peek window.
  * New: Added text formatting flag: %d% to prevent that specific line from scrolling, even if it's longer than the width of the thumbnail window.
  * New: Added "Apply" button to immediately see the effects of the settings.
  * New: "Favorite" button now opens a little window where you can rate the current song from 0 to 5
  * Fix: Some albums that had characters that are not allowed to be in a file name weren't loaded. It's fixed now.
  * Translations: 2 new lines in the translation file

# 1.10 #
  * Fix: got rid of an **important and old memory leak** (it caused several other bugs, especially if you didn't restart Winamp for a long time)
  * Fix: Corrected icon order in the jump list
  * Fix: Corrected several text formatting bugs, such as the shadow being sometimes one character short
  * New: Added two more text formatting flags:
    * %s% - Draws text shadow for containing line using selected shadow color
    * %b% - The line containing this will have a darker background for the text, using the selected shadow color
  * Fix: Right-to-left works yet again
  * Translations: Added 5 lines to the translation file

# 1.09 #
  * New: Added **media library playlists** to the jump list
  * New: Thumbnail button: "Stop after current song"
  * Fix: Small bugfixes
  * Translations: Added 2 lines to the translation file

# 1.08b #
  * Fix: Taskbar icon progressbar always showed 0 or 100 for some users

# 1.08 #
  * Improvement: Recent and frequent categories reworked. The list contains links instead of files. (Artist, title and track length are added to the list)
  * Translations: Added Hungarian, updated some others

# 1.07 #
  * New: **APE (Musepack format) tag support**. Album art is extracted from APEv2 tagged music files.
  * Improvement: Another fix on the settings path finding... (sigh)
  * Translations: Updated translations (template not changed)

# 1.05 #
  * Improvement: Using Winamp's official path finding for the settings file
  * Improvement: All version checking is done in a separate thread
  * Fix: Lots of reported annoying bugs fixed
  * Translations: Updated translations (template not changed)

# 1.04 #
  * New: Added **Media Library bookmarks** to the jump list
  * New: Added "Mute" button on the aero peek thumbnail
  * Fix: A bug that prevented empty lines on the thumbnail text
  * Improvement: Added vertical scrollbar to the text editor
  * Fixed some more bugs with the settings file
  * Fix: Several other bugfixes
  * Translation: Updated some translations and template file

# 1.01 - 1.03 #
  * New: Added "Play from beginning task to the jump list. It plays the current playlist from the start
  * New: Added "Resume Playback" task to the jump list. It starts Winamp playing the last song before it was shut down, from the same position.
  * Fix: Settings are saved correctly for users who have Unicode characters in their Windows user name
  * Fix: Media info wasn't updated when stream was playing
  * Fix: Jump list tasks do not open other players settings when Winamp is closed
  * Fix: Some other minor reported bugs
  * Fix: Other bugs with .ini file path

# 1.00 #

  * Improvement: **Album art is read from embedded picture** from ID3v2 tag
  * Improvement: Album art is drawn with  higher quality
  * New: You can select what to use as background, if selected is not available
  * New: Jump list is configurable by categories
  * Fix: Previous version didn't update title and artist while stream was playing
  * Translation: 6 new lines in translations, 1 removed

# 0.92 #
  * Fix: Several huge bugs from 0.91

# 0.91 #
  * Fix: LOTS of important fixes, reported bugs
  * Fix: Fixed and improved jump list, added Recent, Frequent and Tasks category.
  * Improvement: Re-designed thumbnail progressbar.
  * Improvement: Added notice about the thumbnail buttons taking effect only after restart.
  * New: Added application ID 'Winamp', for the taskbar control. It "should" fix lots of related issues, including the dual monitor one.
  * Translation: 3 new lines in translation.

IF YOU HAD WINAMP PINNED TO TASKBAR, REMOVE THE OLD ICON AND PIN THE NEW ONE.
IN ORDER TO USE THE JUMP LIST, YOU MUST HAVE WINAMP REGISTERED TO HANDLE YOUR AUDIO/VIDEO FILES.

# 0.90 #
  * Improvement: Re-wrote a large part of the code; significantly reduced CPU usage (If you had performance drops while using some features of this plug-in, they should be gone now)
  * Improvement: You can now customize thumbnail buttons, enable and disable them one by one
  * Improvement: Any ID3 tag (text only) can be used as metaword, just surround the tag with '%' (percent) characters. e.g. %comment%
  * New: Added 3 new thumbnail buttons: Volume Up, Volume Down and Open File
  * New: Added feature to show playback progress on thumbnail
  * New: Installer now contains all language files, and will copy the selected one into the destination folder.
  * Translation: Added 4 lines, removed 'addfav'

# 0.84 #
  * Fix: a bug that crashed Winamp on saving settings
  * Improvement: Lots of code optimization, hopefully fixing some of the reported bugs (file size under 200kb!!!)
  * Remake: Removed Winamp logo, if no album art is found, transparent background is used
  * Translation: "Author" is translatable

# 0.83 #
  * New: The plug-in is now compiled as pure native code. File size is half of the previous size, and it should be more robust.
  * Improvement: 'Favorite' button is now optional, and it's semi-last button on the thumbnail.
  * Improvement: Some minor GUI adjustments

# 0.82 #
  * Improvement: Re-sized config window
  * Fix: Some texts weren't translated

# 0.81 #
  * Fix: Ugly bug crashing Winamp when trying to save settings

# 0.80 #

  * Improvement: Re-designed all the GUI, it's much smaller now, with <b>tabbed windows</b>
  * New: Customizable text font, text color and shadow color
    * As a side-effect, the font size is measured in different units
    * To disable the shadow, set the shadow color to white (RGB 255,255,255)
  * New: Added a <b>new 'Favorite' button</b> on thumbnail. It rated the current song with 5 stars.
  * New: feature allowing images to be displayed as icons
    * You can display the selected background as a 50x50 image on the left of the thumbnail
    * Select album art as background, and lower the text size to have album art on the left and text on the right (like the Winamp modern skin notifications)
  * New: feature that uses the taskbar icon progressbar as a <b>VU meter</b>
    * It doesn't really uses more CPU as I've noticed, someone might like it :)
  * Improvement: you can now load images with alpha channel (partial transparency)
  * Lots of other fixes / improvements.
  * Translation: changed, 12 lines added, please update if you can

# 0.74 #
  * Fix: Some lines in the GUI weren't translated correctly.
  * New: Fully customizable drawing font. Color is only applied to shadow color. Shadow won't be drawn in transparent background mode. <b>Removed %red% metaword</b>
  * Translation: Support for "Right to Left" languages. You can mirror the GUI by settings a value in the translation file
  * Improvement: Re-sized GUI again

# 0.73 #
  * Fix: plug-in didn't check online version correctly.

# 0.72 #
  * Remake: GUI is somewhat larger to make room for more text.
  * New: The plug-in doesn't check for Windows version anymore, it's done in the installer. (Removed 3 associated lines from translation file)
  * Fix: Winamp isn't reporting streaming playback status correctly, added a workaround to detect all streaming medias
  * New: Added an option to remove Winamp title, making the thumbnail cleaner. This could cause some side-effects, I didn't really try it out. (New line in translation file)

# 0.71 #
  * New: <b>Translation support</b> - check the [wiki page](http://code.google.com/p/win7shell/wiki/Translations) for more info
  * New: added metawords %track%, %rating1% and %rating2%. Read help in the configuration window for more info
  * Fix: previous version didn't save settings

# 0.70 #
  * New: Added version control: it will automatically check for new version on Winamp startup, and you can check current version in the configuration window
  * Added new metaword %timeleft%, it will show the remaining time from the current song
  * Code optimization

# 0.67 #
  * Fix: previous fix prevented displaying album art for the first song in playlist

# 0.66 #
  * Fix: starting Winamp with empty playlist, and opening the thumbnail preview caused it to crash

# 0.65 #
  * Remake: remade all progressbar and icon overlay coding, which fixed a nasty bug causing visual glitches when Winamp was paused

# 0.64 #
  * Fix: previous fix prevented displaying information about first song in playlist

# 0.63 #
  * Fix: a bug preventing the plug-in to detect the correct Windows version
  * Fix: opening the thumbnail preview with an empty playlist crashed Winamp

# 0.62 #
  * New: you can force the plug-in to install even if Windows 7 wasn't detected. This can be helpful if you're running Winamp in compatibility mode. No, it won't make it usable on some other OS, which doesn't support the features.

# 0.61 #
  * Fix: a bug with the thumbnail player control buttons not updating properly

# 0.6 #
  * Remake: Re-wrote the whole plug-in's memory management
  * New: Added option to enable / disable custom thumbnail image

# 0.6b #
  * Remake: the whole configuration mechanism
  * Improvement: different album art scaling
  * Improvement: improved compatibility with some features with eachother

# 0.54 #
  * Improvement: changed album art searching mechanism again
  * Fix: album art image scaling (it was stretching in width for some images)

# 0.53 #
  * Improvement: changed the album art searching mechanism
  * New: added 'album' and 'year' to be available for selection to display on thumbnail

# 0.52 #
  * Fix: memory leak issues
  * Improvement: changed text drawing font to 'Segoe UI'
  * Improvement: removed all UI links with Winamp main window

# 0.51 #
  * Fix: a minor issue with disabled intermediate progress bar for streaming media. It was showing a tiny 1% green line.

# 0.5 #
  * New: <b>album art support</b> (read main page on how to use it)
  * Improvement: different text drawing mechanism
  * Improvement: small performance tweaks (image and mp3 metadata caching)

# 0.4 #
  * New: <b>added transparent (blurred) background</b> for media info display
  * New: support for all major image formats: BMP, ICON, GIF, JPEG, Exif, PNG, TIFF, WMF, EMF.

# 0.31 #
  * Improvement: you can display only a selected image with no text on it, by setting all lines to 'Empty'. The image and the frame won't resize in this case

# 0.3 #
  * New: <b>added custom background image option</b>
  * Improvement: thumbnail and frame resizing depending on the number of lines of text selected
  * Fix: several minor bugs / compatibility issues

# 0.2 #
  * Fix: the messagebox workaround that made Winamp not to process keyboard events
  * Fix: a bug preventing Winamp to be closed via the system menu
  * Improvement: added customizable font size

# 0.1 #
  * Initial release