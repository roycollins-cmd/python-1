Guido's Gorgeous Lasagna: Notes (what I have learnt working on the exercise.

- The program running can also still provide errors due to the difference in instructions, make sure you name all your variable and constant names are the same as the one provided by the instructions.
- I have read that there's no explicit way to define constant in python (stack overflow), but the difference in readability for a variable and constant are in the styling: 1. SCREAMING_SNAKE_CASE: constants 2. snake_case: variable
- to define a constant --> CONSTANT_NAME = int (a single number with no decimal points, e.g. 40 | 45 | 37) you get the memo.
- The exercise is kind of tricky at first but that was because I didn't read carefully, I had to read again but with attention to detail to be able to tackle it properly

THE LOGIC BEHIND IT:
- the logic behind the calculations is simple enough - it might help you figure it out and or understand it better.

1. We want to bake lasagna with a Recipe ( it has instructions and time), we are more interested in the time which the expected time to bake the lasgana is 40 minutes
2. When you're preparing the lasagna it has layers and each layer takes 2 minutes to prepare (meaning a lasagna with 3 layers takes 6 minutes to prepare)
3. the amount of time elapsed (used) in the process is the sum of the preparation and the time in the oven.
4. the amount of time remaining out of 40 minutes is, yes you guessed, the 40 minutes minus the elapsed time.

- so at the end of this exercise we should have values returned for these:
  1. Expected time
  2. preparation time
  3. used time
  4. remaining time

Roy. C. K 04/24/2025
Time to read: 1 minute, 15 seconds
