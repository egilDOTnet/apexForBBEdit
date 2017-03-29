# apexForBBEdit
An Apex plist language description for BBEdit

BBEdit supports syntax colouring but they've *still* not supported Apex. Since it's my favourite Mac text editor, I figured I'd get started.

Documentation for building these plist files is here:
http://www.barebones.com/support/develop/clm.html#StringBasedPatterns

- All custom objects are now idenified as keywords
- Thanks to BBEdit support for the help with that
- Custom fields that are only on Person Accounts will now be highlighted as well (these end in __pc) using a single regex
- Custom fields that end in an __r (indicating a relationship through a lookup field) are now syntax coloured as keywords
- Line comments are now properly supported after an oversight on my part
- The Un/Comment Lines and Blocks menu options now work as expected
