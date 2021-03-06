---
title: Bookmark Naming
---

#Bookmarks (naming conventions, how do they work!?)
The format for wormhole bookmarks is as follows:

`[@/#][class] - [name] - [sig]`

* @ - for bookmarks leading away from #Exile
* \# - for bookmarks leading towards #Exile
* class - C1/2/3/4/5/6/13, NS, LS, or HS as appropriate
* name - The name of the system the hole leads to
* sig - The letter code of the signature for this hole

## Examples

| Bookmark | Description |
|---|---|
| `@NS - GE-8JV - ABC` | This bookmark takes you away from #Exile, leads to a nullsec system (GE-8JV), and is at signature ABC |
| `#C3 - YouGuysSuck - MOO` | This bookmark takes you towards #Exile, leads to a C3 system which has been named YouGuysSuck, and is at signature MOO |
| `@HS - Jita - FUK` | This bookmark takes you away from #Exile, leads to a highsec system (Jita), and is a signature FUK |
| `#Exile - XYZ` | This bookmark leads to #Exile. Only wormholes that connect directly to #Exile should be named "#Exile" |
| `@C? - ? - HOY` | This bookmark is a temporary one marking a wormhole leading to a J-space system at signature HOY. The class and system name is not yet known. You may see these if the wormhole was scanned down but for whatever reason the person scanning did not jump through. As soon as the information about the connection is known the bookmark should be updated. |

## Example chain
  **#Exile** <=> **C3 Stuff** <=> **C2 Things** <=> **Amarr**

These systems should have the following bookmarks:

**#Exile**

>`@C3 - Stuff - OMG`

**C3 Stuff**

>`#Exile - XYZ`

>`@C2 - Things - WTF`

**C2 Things**

>`#C3 - Stuff - BBQ`

>`@HS - Amarr - LOL`

**Amarr**

>`#C2 - Things - RIP`
