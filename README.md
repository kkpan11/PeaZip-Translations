PeaZip Translations
======

To use additional translations, download the desired language file and copy it in (peazip)/res/share/lang folder.
PeaZip is usually installed in C:\Program Files\PeaZip on Windows, or /usr/lib/peazip on Unix systems.
If the language file is compressed, extract and copy in the aforementioned path the .txt file.

To change PeaZip's language, use Options > Localization.

PeaZip comes with multiple language files, but since additional translations are made available asynchronously from third parts contributors, latest available translation for each language is featured here for separate download.
Each x.y subfolder contains language file for a specific release, minor releases x.y.z shares the same text.

On Windows systems, context menu and SendTo menu items can be translated independently from the text of the main app.

Windows 7+ context menu entries are avaliable as .reg scripts in (peazip)\res\share\lang-wincontext folder, and contributed translations are in https://github.com/peazip/PeaZip-Translations/releases/tag/0.0

Windows 11 mini-context menu entries are available as .reg scripts too, in (peazip)\res\share\batch folder.

SendTo menu entries are .lnk files (changing the link file name changes the text in the SendTo menu entry) available in (peazip)\res\share\batch folder, and contributed translations are in https://github.com/peazip/PeaZip-Translations/releases/tag/0

Note For Translators
------

Instructions about how to provide a translated language file is provided in peazip-x.y.z.about_translations.zip package, featured in github.com/peazip/PeaZip-Translations/releases/tag/x.y.z subfolder.

Translations are covered by [GFDL copyleft license](https://www.gnu.org/licenses/fdl-1.3.html), and can be sent to support email address giorgio.tani.software@gmail.com. As alternative method, language files can be directly updated on Git repository so commits can be evaluated and merged in the online code base:
* https://github.com/peazip/PeaZip/tree/sources/peazip-sources/res/share/lang (language files)
* https://github.com/peazip/PeaZip/tree/sources/peazip-sources/res/share/lang-wincontext (Windows 7+ context menu items)

Additional links:

PeaZip official domain https://peazip.github.io

PeaZip free archiver online help and tutorial https://peazip.github.io/peazip-help.html

PeaZip project's Frequently Asked Questions https://peazip.github.io/peazip-help-faq.html
