# CodinGameShadowsOfTheKnightEpisode2
My solution for the codingame Shadows of the Knight Episode 2
https://www.codingame.com/training/expert/shadows-of-the-knight-episode-2

The solution consists of the following algorithm:

Initialize all windows as potentially containing the bomb.

Jump to average coord of windows potentially containing the bomb.
    
After each jump for each window if batman moved away from the window and output says WARMER or batman moved closer tp that and output says COLDER then that window definitely definitely does not contain the bomb.

We repeat until only one window left.

In cases where the building is too big we group windows into "super windows" of 1600 windows, then when only one superWindow is left we convert back down to regular windows.
