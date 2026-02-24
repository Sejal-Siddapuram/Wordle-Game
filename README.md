# Wordle – Themed Edition (C)

This project is a **console-based Wordle game implemented in C** with multiple difficulty levels, themed word selection, scoring, and persistent leaderboards.

Unlike a basic Wordle clone, this version introduces **themes, adaptive difficulty, and a scoring system**, making gameplay more strategic and replayable.

---

## Features

- 🎯 **5-letter Wordle gameplay**
- 🎚️ **Three difficulty levels**: Easy, Medium, Hard
- 🎨 **Themed words** (Animals, Countries, Fruits, Colors, Games)
- 🪙 **Score calculation based on attempts used**
- 🏆 **Persistent leaderboards** (stored in text files)
- 🔁 **Replay support**
- 🔤 **Input validation** (only 5-letter alphabetic words)

---

## Difficulty Levels Explained

### 🟢 Easy
- Player **chooses a single theme**
- Word is selected only from that theme
- Best for beginners

### 🟡 Medium
- Two random themes are selected
- The word comes from **either one**
- Player is informed of both themes

### 🔴 Hard
- Word can come from **any theme**
- No narrowing hints
- Highest challenge

---

## Themes Included

- Animals
- Countries
- Fruits
- Colors
- Games

Each theme contains predefined 5-letter words.

---

## Gameplay Rules

- You have **6 attempts** to guess the word
- Each guess must be:
  - Exactly **5 letters**
  - Alphabetic characters only
- Feedback after each guess:
  - `[G]` → Correct letter in correct position  
  - `[Y]` → Correct letter in wrong position  
  - `[ ]` → Letter not in the word  

---

## Scoring System

Score depends on how quickly the word is guessed:
