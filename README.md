# TYPO3 Fluid Language package

Adds syntax highlighting to TYPO3 Fluid tags and inline notations in Atom.

In version 0.2 the language is rewritten with more general scope names and the
XML nature of fluid tags in mind.  
Styles are added that use syntax variables from the active theme
[(see styles/typo3-fluid.less)](https://github.com/dokumediacoach/language-typo3-fluid/blob/master/styles/typo3-fluid.less).  
Folding and indentation of fluid tags should now work like with html tags
[(see settings/language-typo3-fluid.cson)](https://github.com/dokumediacoach/language-typo3-fluid/blob/master/settings/language-typo3-fluid.cson).

## Language detection

Language auto detection does not always work properly (HTML was a bad choice for
the Fluid file extension IMO).  
If auto detection fails, use the Grammar Selector by clicking on "HTML" in the
Atom status bar at the bottom on the right or by pressing
`Ctrl+Shift+L` and pick "TYPO3 Fluid".
