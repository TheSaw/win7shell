<font color='red'><b>This page will be updated after the next public release of the plug-in.</b></font>

<b>I will write a short description about each control on the plug-in configuration window. </b>

# Text #

On this page you will find settings that will affect the text drawn on the thumbnail.

> <img src='http://img35.imageshack.us/img35/2584/tab1c.png' alt='Tab 1' border='0'></li></ul>

<ol><li>Anything you write in this text box will be written on the thumbnail. Some words, let's call them 'metawords' have special meaning, whenever you use one of these, it will be replaced with another value, depending on the type of the metaword. (For example %title% will be replaced with the actual playing song's title)<br>
Some text alignment metawords (they apply to the line that contains them):<br>
<ul><li>%c% - centers the line in its allocated space<br>
</li><li>%l% - uses larger font than the one selected for the current line<br>
</li><li>%f% - aligns the text on the left of the thumbnail, even if there is an album art in iconic form<br>
</li></ul></li><li>Use this button to view the list with all the metawords you can use to create your text.<br>
</li><li>Here you can customize the font of the text, including, but not limited to font family, styles, effects and color.<br>
</li><li>The plug-in can draw a text for the shadow if you want, you can select the shadow color here. To turn the shadow off, just select a white shadow color (RGB: 255, 255, 255). It won't draw a white shadow.<br>
</li><li>By enabling this option, the text will be drawn anti-aliased, having a smoother look.<br>
</li><li>Save and apply settings, close window<br>
</li><li>Close window, without saving or applying<br>
</li><li>Switch between pages</li></ol>

<h1>Background #

Here you can select what kind of background you want for your thumbnail. If you enable the <i>iconic image</i> setting on the next page, this background will be used as the icon. (See next page for details)

> <img src='http://img35.imageshack.us/img35/9251/tab2w.png' alt='Tab 1' border='0'></li></ul>

<ol><li>No background will be used, the text will be written on a transparent thumbnail window.<br>
</li><li>The plug-in will try to find the appropriate album art picture for the currently playing song, and use this as background. The image is scaled according to the maximum thumbnail height allowed, and re-sized preserving aspect ratio.<br>
</li><li>The default background is a blue gradient image loaded from inside the plug-in.<br>
</li><li>If you would like to use your own image as background or icon, you can load an image from your hard drive (or removable, network, anything you want). Supported image types are: BMP, ICON, GIF, JPEG, Exif, PNG, TIFF, WMF, EMF. Images with alpha channel (32bpp, partial transparency) are supported and will be drawn accordingly.<br>
</li><li>This text box contains the path to the custom image.<br>
</li><li>You can browse for your image to find it easier.</li></ol>

<h1>Options #

This page contains general plug-in settings.

> <img src='http://img35.imageshack.us/img35/2278/tab3b.png' alt='Tab 1' border='0'></li></ul>

<ol><li>With this checkbox you can enable or disable the custom thumbnail for Winamp. If you un-check this, nothing will be drawn on the thumbnail. Use this if you don't want to alter the default aero peek thumbnail, and want to use only the rest of the features.<br>
</li><li>This feature adds player control buttons (Previous, Play, Pause, Stop, Next) and a Favorite button to the Aero Peek thumbnail. The first five buttons' roles are obvious, the Favorite button rates the currently playing song with 5 stars.<br>
</li><li>You can re-size the thumbnail if your text is smaller than the whole thumbnail window. Enabling this option will cause the thumbnail window to be scaled just to fit the text. It is recommended to enable this if you are using the <i>iconic image</i> feature.<br>
</li><li>By popular request I've added a feature to remove the title of the Winamp window, which is by default shown on the thumbnail. So far I didn't notice any side effects, but it's not a healthy thing to do (but it looks cooler), especially if you have scrolling Winamp title.<br>
</li><li>If you enable this option, the background image you've selected won't be drawn as background, but instead it will be rescaled to 50x50 and moved to the left of the thumbnail. This way you can have text next to it on the right. (The text will be drawn near the image automatically). This can be used to imitate the notification window of Winamp's modern skin, just select album art as background, and use title, artist and album as text. If no album art is found, the text is drawn on the left, without any image.</li></ol>

<h1>Taskbar Icon #

You can control the behavior of the taskbar icon from this page. This refers to the progress bar in the background of the icon, and to the icon overlays drawn in the bottom right corner of the icon.

> <img src='http://img17.imageshack.us/img17/2558/tab4f.png' alt='Tab 1' border='0'></li></ul>

<ol><li>The progress of the playback is shown using the icon progressbar.<br>
</li><li>If you are listening to streaming media, the progress can't be calculated, so an 'indeterminate' progressbar will be shown, if you enable this option. This progressbar is an infinite looping green bar.<br>
</li><li>When the playback is stopped, the icon will turn red, if you enable this option.<br>
</li><li>This is a fun feature, if you enable it, the progressbar will be used to imitate a simple VU meter, showing the signal level of the audio. The progressbar is colored greed, yellow and red, depending on the strength of the signal.<br>
</li><li>If you enable this option, tiny icons will be drawn in the bottom right corner of the taskbar icon, showing the state of the playback (playing, paused, stopped).</li></ol>

<h1>Jump List #

The jump list can be reach by right clicking on the taskbar icon, or by "dragging it out" with left click.

> <img src='http://img17.imageshack.us/img17/9963/tab5u.png' alt='Tab 1' border='0'></li></ul>

<ol><li>If this checkbox is checked, all files played with Winamp will be shown in this jump list.</li></ol>

<h1>Development #

On this page you'll find some links to several webpages on this site, and similar features.

> <img src='http://img17.imageshack.us/img17/9893/tab6.png' alt='Tab 1' border='0'></li></ul>

<ol><li>This link opens up the bugs reporting page<br>
</li><li>Link to the project's home page<br>
</li><li>Link to translations<br>
</li><li>If you do not want the plug-in to check for updates at Winamp star-up, enable this option