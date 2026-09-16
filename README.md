# The Little Mermaid Hangman

A colorful, terminal-based Hangman game inspired by *The Little Mermaid*, written in C++.

Instead of drawing the traditional Hangman figure, each incorrect guess brings Ursula closer to Ariel. Guess the mystery *Little Mermaid* character before your HP reaches zero and Ursula takes over!

## Features

* Randomly selects a *Little Mermaid* character for each game
* Classic letter-by-letter Hangman gameplay
* Six incorrect guesses before game over
* HP system that decreases with each incorrect guess
* Tracks the remaining letters of the alphabet
* Colorful terminal output using ANSI escape codes
* Custom ASCII artwork featuring Ariel, Ursula, and other themed graphics
* Evolving artwork and dialogue as Ursula gets closer
* Custom victory and game-over screens

## Characters

The mystery character is randomly selected from a collection of familiar names from *The Little Mermaid* universe, including Ariel, Sebastian, Flounder, Ursula, Prince Eric, King Triton, and more.

## How to Play

1. Run the program and press **Enter** to begin.
2. A random *Little Mermaid* character will be chosen.
3. Enter one letter at a time to reveal the hidden name.
4. Correct guesses reveal every occurrence of that letter.
5. Incorrect guesses decrease your HP and allow Ursula to get closer.
6. Reveal the entire character name before your HP reaches **0** to win!

## Running the Game

Compile the program using a C++ compiler such as `g++`:

```bash
g++ main.cpp -o mermaid-hangman
```

Then run:

```bash
./mermaid-hangman
```

For the best experience, use a terminal that supports **ANSI colors and Unicode characters**.

## About the Project

This project was originally created as a C++ programming assignment and turned into a themed version of Hangman. I wanted to make the standard game a little more fun, so I added colorful ASCII art, character dialogue, an HP system, and a progressively changing scene rather than the traditional Hangman drawing.

The goal was to practice C++ fundamentals such as loops, conditionals, strings, arrays, functions, randomization, and console input/output while making something fun and visually unique.

## Made With

* C++
* ASCII / Unicode art
* ANSI terminal colors
* A little bit of Disney nostalgia 🧜‍♀️🐠🐚

---

*The Little Mermaid* characters and related names belong to their respective copyright holders. This is a small educational programming project and is not affiliated with or endorsed by Disney.

