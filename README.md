# Simple highlighting of text/plain files

Adds highlighting to plain text files in [Atom](https://atom.io/) to improve the visual structure of the document.

![Screenshot](https://raw.githubusercontent.com/Reyhn3/atom-plain-simple/master/screenshots/screenshot.png)

Contributions, bug reports and feature requests are very welcome!

&nbsp; &nbsp; &nbsp; &nbsp; _- Reyhn_




## Note on auto grammar

This package should be automatically applied to .txt-files.
However, other packages might also use that file extension.

If this highlighting is not applied, check your other grammar packages for their file types.
You might be required to modify their grammar .cson-files and comment out the txt-extension.

For example, change this:
```
'fileTypes': [
  'txt'
  'log'
  'syslog'
  'out'
  'output'
]
```
into:
```
'fileTypes': [
#  'txt'
  'log'
  'syslog'
  'out'
  'output'
]
```




##### Legal

The package icon is made by [Alessandro Roncone](https://github.com/alecive), available under a [CC Attribution-Share Alike 4.0](http://creativecommons.org/licenses/by-sa/4.0/) license.

This package is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
