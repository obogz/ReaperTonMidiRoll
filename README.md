# ReaPerTonMidiRoll
Ableton like midi editor step input actions for Reaper

THIS VERSION IS ALPHA (aka half-assed)!! Hightly unstable!!!

To install, copy the scripts to the reaper script directory and add them in your Midi Edito actions.
To use make sure you have the normal step recording option turned off!

This project was started using this work: https://github.com/thenfour/ReaperScripts


TODO: 
- Make undo work properly
- Make back action work properly (delete if note is too small)
- optimise and cleanup the code
- see if there is another way to detect retriggerd notes besides comparing velocity
- cleanup, cleanup some more, optimise, organise and add integration with ReaPack

Long term:
- create an jsfx extension that improves on this

Know issue: any new pressed note with the same velocity and pitch as the note at the cursor will not be considered a new note and will result in extending the previous note. This rearly happnes if you use a keyboard with variable velocity.
