             🎲 DICE ROLLING SIMULATOR 🎲
How a Dice Rolling Simulator Works in Python A dice rolling simulator in Python uses the random module's randint() function to generate random numbers that simulate the roll of a die.

Key Steps:

The program imports the random module, which provides functions for generating random numbers.

When the user wants to "roll" the dice, the program calls random.randint(1, 6). This function returns a random integer between 1 and 6, inclusive, mimicking the possible outcomes of a standard six-sided die.

If rolling multiple dice, the function is called multiple times—once for each die—so each die gets its own random result.

The results are then displayed to the user, either as numbers or using ASCII art for a visual effect.
