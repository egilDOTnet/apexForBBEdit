# apexForBBEdit
An Apex plist language description for BBEdit

BBEdit supports syntax colouring but they've *still* not supported Apex. Since it's my favourite Mac text editor, I figured I'd get started.

Documentation for building these plist files is here:
http://www.barebones.com/support/develop/clm.html#StringBasedPatterns

- All custom objects are now idenified as keywords
- Thanks to BBEdit support for the help with that
- Custom fields that are only on Person Accounts will now be highlighted as well (these end in __pc) using a single regex
