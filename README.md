RoboDJ
======

An Ableton Live/Max MSP Automated DJ that will do all the computer work on stage so that I don't have to.

How to use it
======

Clips that should play simultaneousely should belong to one scene (ie. a horizontal row of clips in live).

RoboDJ needs to fire "stop clip" events on a 'dummy' track in order to work, and that track will change for every project. If a trackkeeps getting stopped unintentionally, move everything you need from that track to a new one, and disable that track. Events will continue to fire on it without impacting playback.

If something is not working, it's probably a typo in test_dict.json.
