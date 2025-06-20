# AI-Mind-Reader-Game
# 🧠 AI Mind Reader Game

A Python-based console game where the computer uses pattern recognition to "read your mind" and predict your next binary input (0 or 1). Built using NumPy and a simple AI learning mechanism based on recent inputs.

## 🎯 Objective

Test your randomness! The AI tries to guess your next move using a memory of the last two entries. If it guesses right, the computer scores a point — otherwise, you do.

## 🧠 How It Works

* A 3D NumPy array (`inputs[2][2][2]`) is used to store past patterns.
* The AI updates this pattern memory after each input.
* If a pattern is recognized (i.e., it occurred previously), the AI uses that to predict your next digit.
* Otherwise, it chooses randomly.

## 🛠️ Requirements

* Python 3.x
* NumPy

Install NumPy if you don't have it:

```bash
pip install numpy
```

## 🚀 How to Run

```bash
python "My AI Mind Reader Game"
```

## 📸 Sample Output

```
Enter 0 or 1: 1  
Computer guessed: 0  
You get a point!

Scores -> AI: 2 | You: 3
```

## 📚 Concepts Demonstrated

* NumPy for efficient data handling
* Pattern recognition using 3D arrays
* Basic AI logic and prediction
* Game state tracking in Python

## 📄 License

Open-source under the [MIT License](LICENSE).
