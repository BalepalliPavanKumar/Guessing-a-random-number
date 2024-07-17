This language is used to create the logic for the game, manage the leaderboard, and handle user input and output.

Common Libraries:

<iostream>:    For functions involving input and output.
<cstdlib>:       For general utilities and the creation of random numbers.
<ctime>:         To start the random number generator.
<vector>:        For dynamic array management of the leaderboard.
<algorithm>:  Used to arrange the entries on the leaderboard.

Instruction and Ideas:

C++ Code Development:

Knowledge of the syntax and semantics of C++.

Knowledge of common input and output procedures.

Familiarity with control structures (conditionals, loops).

Use of functions to promote code reuse and modularity.

Information Organizations:

Usage of std::vector for dynamic array management.

Sorting operations are performed using std::sort.

Project Overview:

A C++ console program called Random Number Guessing Game asks users to predict a randomly generated number inside a given range. A menu for simple navigation, many difficulty settings, and a leaderboard to keep track of high scores are all included in the game.

Characteristics and Capabilities

Levels of Difficulty:

Simple: 1–20 range, 5 tries.

Medium: 10 tries in the 1–50 range.

Hard: 15 tries in the 1-100 range.



Game mechanics:

Generates random numbers within the specified range of difficulty.
Player guesses and name input.
Please let us know if the estimate is accurate or not.
calculating the score using the number of attempts left.

LeaderBoard:

Top 10 scores will be stored.
Names and scores are shown in descending order.
