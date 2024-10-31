PrusaPoo is an alternative start g-code for your Prusa MK4.

|

The MK4 purges before every print. This purge line is actually quite light, weighing only 0.1g. However, the issue with this purge line is that it can be hard to peel off, sometimes even painful. Another downside is that you have to manually remove the purge line.

That's where PrusaPoo comes into play. Instead of purging a line, PrusaPoo purges (you guessed it) a small "poop." It also weighs 0.1g. One of the major advantages is that it ejects automatically into a small bin on the side.

PrusaPoo is, in its current state, compatible only with PLA and PETG.

|

|

The way you implement it is simple. Download "PrusaPoo.txt" and copy the text from it to your clipboard. Next, open Prusaslicer,![Prusaslicer](https://github.com/user-attachments/assets/61099ca3-dbbd-4b99-8088-3b0b68d742a8) click on "Printers,"![Printers](https://github.com/user-attachments/assets/a8d6c1f2-43c1-467b-aa4b-18a4404e5193)then go to "Custom G-code."![Custom G-code](https://github.com/user-attachments/assets/6fdb9857-8ab8-466b-ae26-7b9533c1b164)
 Navigate to the "Start G-code" field,![Start_G-code](https://github.com/user-attachments/assets/0ef46199-b506-4f3c-a8fe-ea86eb06fc6b) find the line "; Extrude purge line," delete that line and everything below it,![Extrude_Purge_Line](https://github.com/user-attachments/assets/95e1246a-1b0a-4992-88dd-435c3a47393e) 
and then paste the new G-code in place of the deleted section.
![New_G-code](https://github.com/user-attachments/assets/8cfe71b4-a9ab-4799-adb4-27e26bc1a587)Save your preset,![Save_Preset](https://github.com/user-attachments/assets/c8081aee-aa09-45fe-923b-1eb033cf7684) and you're ready to go!

|

If someone has any suggestions contact me via printables! @VOJTAsak_272820
