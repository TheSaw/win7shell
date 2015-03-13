# Translating The Plug-In #

## Winamp Translation System ##
Windows 7 Taskbar Integration plugin (starting from v2.0) uses the Winamp Translation system. Winamp Translation System uses special language packs, called WLZ.

A WLZ file is a packed ZIP archive that contains all necessary language files. Basically, WLZ stores `*`.lng files and graphic files for skins (png + xml). WLZ files are located in Winamp Language Pack directory:
'C:\Program Files\Winamp\Lang\'.

All Winamp translations .lng files must be stored in WLZ files or be placed in a special subfolder. This subfolder's name is WLZ language ID (_e.g.: For German: C:\Program Files\Winamp\Lang\de-DE\`*`.lng. For Spain:  C:\Program Files\Winamp\Lang\es-US\`*`.lng_).

So, if we go to Winamp settings and choose german language (_choose: Winamp-de-de_), Winamp will use translation files from German WLZ file (_C:\Program Files\Winamp\Lang\de-DE\Winamp-de-de.wlz_) and all `*`.lng translation files placed in Winamp Language Pack subfolder (_for German: C:\Program Files\Winamp\Lang\de-DE\`*`.lng_).


## Plugin Translation ##
In order to translate Windows 7 Taskbar Integration plugin you need to:

  1. Download the plugin and its translation file (gen\_win7shell.lng)
  1. Install the plugin. It will be copied to Winamp plugins directory.
  1. Translate downloaded example .lng file (gen\_win7shell.lng) to your language.

This file is a resource file (_http://en.wikipedia.org/wiki/Resource`_`(Windows)_). That means, it needs to be edited in resource editor. There are few good resource editors that can do the job:
  * XN Resource Editor (free) (http://www.wilsonc.demon.co.uk/d10resourceeditor.htm)
  * ResEdit (free) (http://www.resedit.net/)
  * Resource Editor (free) (http://melander.dk/reseditor/)
  * Restorator (not free!) (http://www.bome.com/products/restorator)

Once you have your resource editor, open the .lng file and change
its resources (Dialogs, Menus, Strings, Accelerators, Version info etc.) to your language.<br />You may also change the position of the controls, if it is needed.

## Using your translation file ##
To use your translation you need to be sure your language file has corresponding WLZ file. For now Winamp supports several official translations:
  * Winamp-de-de.wlz (German)
  * Winamp-es-us.wlz (Spanish)
  * Winamp-fr-fr.wlz (French)
  * Winamp-it-it.wlz (Italian)
  * Winamp-ja-jp.wlz (Japanese)
  * Winamp-ko-kr.wlz (Korean)
  * Winamp-nl-nl.wlz (Dutch)
  * Winamp-pl-pl.wlz (Polish)
  * Winamp-pt-br.wlz (Brazilian Portuguese)
  * Winamp-ro-ro.wlz (Romanian)
  * Winamp-ru-ru.wlz (Russian)
  * Winamp-sv-se.wlz (Swedish)
  * Winamp-tr-tr.wlz (Turkish)
  * Winamp-zh-cn.wlz (Chinese)
  * Winamp-zh-tw.wlz (Chinese)

There are also few unofficial Winamp WLZ translations. For example:
  * Winamp-el-GR.wlz (Greek)
  * Winamp-id-ID.wlz (Indonesian)

Now, if you use a language mentioned above, you are lucky. If there is a WLZ language pack for Winamp that support your language you need to:
  * Go to Winamp Language Pack directory - C:\Program Files\Winamp\Lang
  * Check if there your language WLZ file exists (for example if you use German, find Winamp-de-de.wlz file)
If not, download your language WLZ (in our example - german) and copy it there (try here: http://www.winamp.com/plugins/language-packs/9).
  * Create a directory with your language ID. For example: C:\Program Files (x86)\Winamp\Lang\de-DE -> for German language
  * Copy your translated gen\_win7shell.lng file to that location, for example: C:\Program Files (x86)\Winamp\Lang\de-DE\gen\_win7shell.lng
  * Run Winamp and change Winamp Language Pack to yours (in this example to German)
That is all. Your plugin should be displayed in your language now.

If you just translated gen\_win7shell.lng to language that doesn't have corresponding WLZ file, you need to do following:
  * Translate gen\_win7shell.lng to your language, for example: Vietnamese (Vietnam)
  * Download latest official English Winamp Language Pack (http://xlat.meggamusic.co.uk/winamp/docs/xlat/files/Winamp-en-us.wlz)
  * Copy this WLZ file to the following directory: C:\Program Files\Winamp\Lang.
  * Create subdirectory: C:\Program Files\Winamp\Lang\en-US
  * Copy your plugin to this subdirectory: C:\Program Files\Winamp\Lang\en-US\gen\_win7shell.lng
  * Run Winamp, change language to en-us English (Winamp-en-us -> NOT default English(US))
That is all. Your plugin should be displayed in your language now (but Winamp will be displayed in English).

You can always translate Winamp to your language.<br />
Read: http://xlat.meggamusic.co.uk/winamp/docs/xlat/xlat.html