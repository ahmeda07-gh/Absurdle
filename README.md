Absurdle (Java Implementation)

Absurdle is a twist on the popular game Wordle, designed to be as evil as possible.
Rather than choosing a secret word at the start, Absurdle dynamically adapts to your guesses, always keeping the set of possible answers as large as possible. The goal is to prolong the game and resist being solved.

This Java implementation loads a dictionary of words, filters them by length, and interacts with the user through the console. After each guess, the program responds with:

🟩 Green — correct letter, correct position

🟨 Yellow — letter present but in the wrong position

⬜ Gray — letter not in the word

Unlike Wordle, the program partitions all possible words into pattern groups and always chooses the group with the most remaining words, making it as hard as possible for the player.

✨ Features

Loads any dictionary file the user provides

Filters the dictionary by the player’s chosen word length

Gives Wordle-style feedback for every guess

Dynamically updates the possible word set to keep the game going

Prints all generated patterns at the end

Implemented entirely in plain Java
