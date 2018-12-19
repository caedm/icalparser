# CAEDM icalparser
A fork of https://github.com/OzzyCzech/icalparser made for the purpose of being used with https://github.com/caedm/wall-ink-server/ iCalWeb plugin.

The only real difference we've made here is to add the ability to extract the name of the calendar in the ics file processed, if the X-WR-CALNAME property is used.  X-WR-CALNAME is set by both Exchange/Outlook and Google ics files, among others.

Many thanks to OzzyCzech for the work he's done to build this parser!
