# 🗼 Tower of Hanoi Visualizer

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![GUI](https://img.shields.io/badge/GUI-Tkinter-green?style=for-the-badge)
![Algorithms](https://img.shields.io/badge/Algorithms-Recursion-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)

### Interactive Tower of Hanoi Visualization with Recursive Algorithm

</div>

---

# 📖 Overview

Tower of Hanoi Visualizer is an interactive implementation of the famous Tower of Hanoi puzzle. The project demonstrates the recursive algorithm by visually moving disks between three towers while following the puzzle's rules.

The application provides an educational visualization of recursion, algorithm design, and problem solving.

---

# ✨ Features

- 🎮 Interactive Tower of Hanoi simulation
- 🧠 Recursive algorithm implementation
- 📊 Step-by-step disk movement
- ⚡ Automatic puzzle solving
- 🎨 Clean graphical interface
- 🗼 Three tower visualization
- 🔄 Adjustable number of disks
- 📚 Educational recursion demonstration

---

# 🧠 Algorithm

The Tower of Hanoi puzzle follows three simple rules:

1. Only one disk can be moved at a time.
2. Only the top disk of a tower can be moved.
3. A larger disk can never be placed on a smaller disk.

Recursive algorithm:

```
Move(n, Source, Auxiliary, Destination)

If n == 1
    Move Source → Destination

Else

Move(n-1, Source, Destination, Auxiliary)

Move largest disk

Move(n-1, Auxiliary, Source, Destination)
```

---

# 📈 Time Complexity

| Complexity | Value |
|------------|-------|
| Time Complexity | O(2ⁿ) |
| Space Complexity | O(n) |

Minimum moves required:

```
Moves = 2ⁿ − 1
```

Example

| Disks | Minimum Moves |
|--------|---------------|
| 3 | 7 |
| 4 | 15 |
| 5 | 31 |
| 6 | 63 |
| 7 | 127 |

---

# 🛠 Tech Stack

## Programming Language

- Python

## GUI

- Tkinter *(or replace with Pygame if applicable)*

## Concepts Used

- Recursion
- Data Structures
- Algorithm Design
- Problem Solving
- Visualization

---

# 📂 Project Structure

```
Tower-of-Hanoi/

│── main.py
│── tower.py
│── utils.py
│── assets/
│── screenshots/
│── requirements.txt
│── README.md
```

*(Update this to match your repository.)*

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/harshchavan009/Tower-of-Hanoi.git
```

Navigate into the project

```bash
cd Tower-of-Hanoi
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run

```bash
python main.py
```

---

# 🎮 How It Works

1. Select the number of disks.
2. Start the visualization.
3. Watch the recursive algorithm solve the puzzle.
4. Observe each valid disk movement until completion.

---

# 📸 Screenshots

### Home Screen

_Add screenshot here_

---

### Visualization

_Add screenshot here_

---

### Completed Puzzle

_Add screenshot here_

---

# 📚 Learning Outcomes

This project demonstrates:

- Recursive programming
- Stack-based recursion
- Algorithm visualization
- GUI programming
- Problem decomposition
- Mathematical reasoning

---

# 🎯 Applications

- Computer Science Education
- Algorithm Visualization
- Recursion Learning
- Data Structure Demonstrations
- Programming Practice

---

# 🚀 Future Improvements

- Multiple solving speeds
- Pause and Resume
- Manual Play Mode
- Move Counter
- Undo/Redo
- Sound Effects
- 3D Visualization
- Animated Disk Movement
- Dark/Light Theme
- Performance Statistics

---

# 💼 Resume Highlights

- Developed an interactive Tower of Hanoi visualization using Python.
- Implemented an optimized recursive algorithm to solve the puzzle.
- Designed a graphical interface for educational algorithm visualization.
- Demonstrated recursion, stack behavior, and algorithm complexity through animation.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Developer

## Harsh Chavan

**Computer Science Engineering (AI & ML)**

- Python Developer
- Machine Learning Enthusiast
- Full Stack Developer
- AI Engineer

GitHub:
https://github.com/harshchavan009

---

<div align="center">

⭐ If you found this project useful, consider giving it a Star!

Made with ❤️ by Harsh Chavan

</div>
