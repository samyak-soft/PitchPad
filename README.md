# PitchPad

## About Project
This software features a piano‑like layout with a unique tone. The special aspect of this virtual instrument is that each key also acts as a pitch bender.

## Guide to Use
This HTML‑based code runs in modern browsers. By default, two octaves fit within the width, but there is a button above that can be tapped to switch to a single octave view, making each key wider and easier to play.  
You can move forward or backward through the octaves by tapping the arrows at the top.  

Each key is virtually divided into three parts (not visible in the UI but set in the logic): the top 20%, middle 60%, and bottom 20%.  
- Tapping anywhere plays the tone corresponding to the note.  
- Tapping the middle 60% plays the note without pitch bend.  
- Tapping the top 20% or bottom 20% activates pitch bend.  

If you tap the bottom 20% and drag upward, the pitch increases. If you tap the top 20% and drag downward, the pitch decreases. The pitch can shift up or down by 1, 2, 3, or 4 notes depending on your settings.
