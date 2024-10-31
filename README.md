PrusaPoo is an alternative start g-code for your Prusa MK4.

|

The MK4 purges before every print. This purge line is actually quite light, weighing only 0.1g. However, the issue with this purge line is that it can be hard to peel off, sometimes even painful. Another downside is that you have to manually remove the purge line.

That's where PrusaPoo comes into play. Instead of purging a line, PrusaPoo purges (you guessed it) a small "poop." It also weighs 0.1g. One of the major advantages is that it ejects automatically into a small bin on the side.

PrusaPoo is, in its current state, compatible only with PLA and PETG.

|

|

The way you implement it is simple. Download "PrusaPoo.txt" and copy the text from it to your clipboard. Next, open Prusaslicer, click on "Printers," then go to "Custom G-code." Navigate to the "Start G-code" field, find the line "; Extrude purge line," delete that line and everything below it, and then paste the new G-code in place of the deleted section. Save your preset, and you're ready to go!
