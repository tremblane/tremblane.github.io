---
title: Bookmark Naming
---

#Bookmarks (naming conventions, how do they work!?)
The format for wormhole bookmarks is as follows:

`[@/#][class] - [name] - [sig]`

* @ - for bookmarks leading away from #Home
*  # - for bookmarks leading towards #Home
* class - C1/2/3/4/5/6, NS, LS, or HS as appropriate
* name - The name of the system the hole leads to
* sig - The letter code of the signature for this hole

## Examples

`@NS - GE-8JV - ABC`
This bookmark takes you away from #Home, leads to a nullsec system (GE-8JV), and is at signature ABC

`#C3 - YouGuysSuck - MOO`
This bookmark takes you towards #Home, leads to a C3 system which has been named YouGuysSuck, and is at signature MOO

`@HS - Jita - FUK`
This bookmark takes you away from #Home, leads to a highsec system (Jita), and is a signature FUK

`#Home - XYZ`
This bookmark leads to #Home. Only wormholes that connect directly to #Home should be named "#Home"

## Example chain
  **#Home** <=> **C3 Stuff** <=> **C2 Things** <=> **Amarr**

These systems should have the following bookmarks:

**#Home**
>`@C3 - Stuff - OMG`

**C3 Stuff**
>`#Home - XYZ`

>`@C2 - Things - WTF`

**C2 Things**
>`#C3 - Stuff - BBQ`

>`@HS - Amarr - LOL`

**Amarr**
>`#C2 - Things - RIP`
