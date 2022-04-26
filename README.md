# Redor
Sequencer amalgamation in Pure Data

-- Important Info -- 

- The sequencers / other patches are all inside sub-patches in the main window, feel free to organize them however you like.
- Loadbang triggers a tempo of 105 milliseconds.
- Loadbang turns on DSP, no need to do it manually.
- The_big_one aka the start / stop button inside the main window is also able to control rhythm because the amount of steps the sequencers are at are not cleared once you press that button.
- Specify a number inside rand_seq-limit_all in the main window, this will give every oscillator the sequencers possess a maximum interger which will then be sent inside randomizers which are used for randomized pitches. (NOTE: the unit is Hz)
- Simply click the randomize_sequencers button in the main window in order to bang the randomizers which are then fed to the sequencers.
- Anything else would be self explanatory if you know Pure Data, have fun! 😄

![img01](https://user-images.githubusercontent.com/103774736/165374350-29ebb403-94b1-4ef7-ab9f-3dbba88a06e3.PNG)
