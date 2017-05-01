<div id="container">

# Setting the spell check language

N1 uses the electron-spellchecker module for spell check: https://www.npmjs.com/package/electron-spellchecker  This is neat because it automatically detects the language you're writing in and spellchecks in that language.  If you reply in multiple languages, it will even only spell check certain phrases in the correct language!  On Linux and older versions of Windows, it downloads Hunspell dictionaries on-the-fly, because shipping them all would be costly.  If your N1 doesn't detect the language that you're typing in, please write a draft in the language of your choice and allow N1 to try to download the language in the background. 

On Mac OS X and Windows 10, N1 will default to your operating system language for spell checking your drafts. To change your spellchecking language, you'll need to change your system language.

On Linux and older versions of Windows, N1 will spell check in English when your system language is English. System dictionaries are not available for other languages, and N1 will not perform spell check if your system language is not English. We're working to expand spell check support for other languages on Linux and Windows, and you can follow the discussion here: https://github.com/nylas/N1/issues/1392

</div>
