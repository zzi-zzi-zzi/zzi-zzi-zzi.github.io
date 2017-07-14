---
title: Mew
permalink: mew.html
---

# Mew

Mew is a plugin that allow you to set you gathering journey. There is a tab for each mode/feature : 

(Click a link below to be taken to a page with more information about that tab)

- [General](/mew/general.html) : Miscellaneous settings.
- [Shop](/mew/shop.html) : How to spend your scrips.
- [Unown A](/mew/unown.html) : Unspoiled gathering settings.
- [Unown B](/mew/unown.html) : Unspoiled items scehdule.
- [Psyduck](/mew/psyduck.html) : Fish that require Weather and/or Time conditions.
- [Chansey](/mew/chansey.html) : Housing.
- [Snorlax](/mew/snorlax.html) : Regular/Normal nodes farm.
- [Slowpoke](/mew/slowpoke.html) : Fish that don't require Weather and/or Time conditions.
- [Onix](/mew/onix.html) : Ephemeral nodes.
- [Magikarp](/mew/magikarp.html) : FSH red/yellow scrips farm from 24/7 fish. 
- [Ditto](/mew/ditto.html) : BTN/MIN red/yellow scrips items gathered from 24/7 nodes.

About the logic behind, the highest (in the list) mode is the one with the most priority.
#The priorities are :
 * Timed :
   - Psyduck (Conditionnals Fish) with Keep Fishing on
   - Unown (Unspoiled)
   - Psyduck (Conditionnals Fish) with Keep Fishing off
   - Chansey (Housing)
   - Onix (Ephemeral nodes) with Timed Mode on
 * H24 :
   - Snorlax (Regular Items)  untill amounts set reached
   - Slowpoke (Non Conditionnals Fish) untill amounts set reached
   - Onix (Ephemeral nodes) with Timed Mode off
   - Magikarp (FSH Scrips farm)
   - Ditto (BTN/MIN Scrips farm)

So it'll first check what you set for Unown, if there is nothing available right now it'll then check the next mode etc...
When something from an higher mode is available it'll stop the current mode to do it.
