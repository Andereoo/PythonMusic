# PythonMusic
Small cross-platform music note player for beginners to learn how to manipulate system sounds.

It has been tested tested in python 3.x on Windows.
Uses include playing songs through set notes, playing.wav files, or creating custom 'beeps' with a known hertz frequency.

&nbsp;
### Main Commands

	•Note(note, length, number_of_repeats)
  •Makes a beep sound based off of the note name. length' is in milliseconds; 'number_of_repeats'  is a positive integer 1 or above

	• custom_sound(hertz_frequency, length, number_of_repeats)
  • Makes custom beep based off of hertz frequency and duration; frequency must be from 37 through 32,767


	• wait(length)
  •Pauses the program; 'length' is in milliseconds

	• play_file(directory)
  •Plays a wav file in a given directory
