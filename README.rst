==========================
sigfig_and_comma_formatter
==========================

Python string formatter that gets you both significant figures AND commas

Python provides a nice automatic way to insert commas in for the thousands separator.

It also provides an easy way to get only a set amount of significant figures dislayed.

But the sigfig formatter ('g') alwyas used scientifc / engineering notation for large numbers, so there is no way to combine the two. Sometimes we do want both, so this is a little function that provides that.

Code is borrowed haeivly from DrSkippy (Scott Hendrickson)'s Text-Format-Table, in which he does the same thing, but it's a bit mixed in with the table-generating code, so I've pulled it out as a stand alone function.

https://github.com/DrSkippy/Text-Format-Table/blob/master/FNumber.py

NOTE: I can't find a license for his code, so if you are he, or know how he want's it licnese, and it' not OK to put it up here as Public Domain, please let me know.

-Chris

