# 🤖 Artificial Intelligence Lab - Spring 2026

**Course:** 6th Semester - AI Lab  
**Institution:** [Your University Name]  
**Lab Manuals:** Lab#01, Lab#02, Lab#03

---

## 📚 Lab Contents

This repository contains the lab work for the Artificial Intelligence course, covering foundational Python programming, intelligent agents, and machine learning agent architectures.

---

## 🗂️ Repository Structure

```
AI(LAB)/
├── README.md                 # This file
├── LAB1 (1) (1).ipynb       # Lab 1: Python & NumPy Fundamentals
├── LAB2.ipynb               # Lab 2: Simple Reflex Agent - Vacuum Cleaner
├── LAB3 (1).ipynb          # Lab 3: Learning Agent - Temperature & Water Control
│
├── Lab#01/                  # Lab 1 Supporting Materials
│   ├── Dataset/
│   ├── Lab#01.pptx
│   ├── Lab#01_AI_Spring_2026.ipynb
│   └── Scoring Rubric - Lab#01.pdf
│
├── Lab#01_Complete_Manual (1).docx
├── Lab02_manul.docx
├── Lab03_manul.docx
├── Lab#01_AI_Spring_2026.pdf
├── Lab#02_AI_2026.pdf
└── Lab#03_AI_2026.pdf
```

---

## 🧪 Lab 1: Python & NumPy Fundamentals

**File:** `LAB1 (1) (1).ipynb`

### Topics Covered
- **Python Basics:** Variables, data types, operators, booleans, strings
- **Data Structures:** Lists, dictionaries, sets, tuples
- **Control Flow:** Loops, list comprehensions, slicing
- **Functions & Classes:** Defining functions, object-oriented programming
- **NumPy:** Array creation, indexing, broadcasting, array mathematics

### Practice Exercises (11 Questions)
| Q# | Description |
|----|-------------|
| 1 | Determine parity (even/odd) of a number |
| 2 | Check string length parity for a list |
| 3 | Reverse "hello" using indexing |
| 4 | Multiples of 2 but not 5 (list comprehension) |
| 5 | Broadcasting: square of sum of two random arrays |
| 6 | Merge dictionaries (student IDs, names & scores) |
| 7 | Replace negative elements with squares (boolean indexing) |
| 8 | Array statistics (max, standard deviation, sum) |
| 9 | Count uppercase & lowercase letters in a string |
| 10 | FizzBuzz implementation |
| 11 | Two-sum problem solution |

### Advanced Tasks
- **Nested Dictionary Access:** Multi-level dictionary traversal
- **TupleOperations Class:** Custom class for tuple arithmetic (addition, subtraction, multiplication, division, power)
- **Twitter Handle Extraction:** Regex-based @username extraction from tweets
- **Multilingual Text Cleaning:** Urdu & English mixed text preprocessing (punctuation removal, digit removal, single-character removal)
- **Urdu Digit Conversion:** Convert English numerals to Urdu script (۰-۹)
- **Frequency Analysis:** Top-10 word frequency for Urdu words starting with "م"

---

## 🧹 Lab 2: Simple Reflex Agent

**File:** `LAB2.ipynb`

### Project: Two-Room Vacuum Cleaner Agent

A classic AI agent implementation demonstrating a **simple reflex agent** architecture.

#### Features
- 🏠 **Two-room environment:** Room A & Room B
- 🤖 **Agent percepts:** Current location, room status (clean/dirty)
- 🧹 **Actions:** Suck (clean), Move Left, Move Right
- 💰 **Performance Measure:** Cost tracking (each action = cost 1)
- 🔄 **Rational Decision Making:** Cleans if dirty, moves if clean

#### How It Works
1. User inputs robot's starting position (A or B)
2. User specifies dirt status for both rooms (0=clean, 1=dirty)
3. Agent executes loop until all rooms are clean:
   - If current room dirty → **Clean**
   - If current room clean → **Move** to other room
4. Outputs action sequence and total cost

---

## 🌡️ Lab 3: Learning Agent

**File:** `LAB3 (1).ipynb`

### Topics: Agent Architecture Components
- **Performance Element:** Makes decisions based on current knowledge
- **Critic:** Evaluates performance by calculating error
- **Learning Element:** Updates internal model based on feedback
- **Problem Generator:** Simulates environmental changes

### Task 1: Temperature Control Learning Agent
A thermostat agent that learns optimal heating offset through feedback.

#### Architecture
| Component | Function |
|-----------|----------|
| Performance | Decides heater ON/OFF based on temperature comparison |
| Critic | Calculates error = target_temp - applied_temp |
| Learning | Updates model offset: `offset += learning_rate × error` |
| Problem Generator | Alternates environment temperature ±0.5°C |

#### Sample Output
```
Step 1: Heater ON, Temp: 17.0°C, Error: -1.0, Model Offset: -0.1
Step 2: Heater OFF, Temp: 16.5°C, Error: -0.5, Model Offset: -0.2
...
```

### Task 2: Water-Level Learning Agent (Post-Lab)
An adaptive water tank agent with random environmental disturbances.

#### Features
- 🚰 Valve control (OPEN/CLOSED)
- 🎲 Random disturbances: usage (-1), stable (0), rain (+1)
- 📊 10-step learning cycle with real-time adaptation

---

## 🛠️ Technologies Used

| Technology | Version | Purpose |
|------------|---------|---------|
| Python | 3.x | Core programming language |
| NumPy | Latest | Numerical computing & array operations |
| Jupyter Notebook | Latest | Interactive development environment |
| Regex (re) | Built-in | Text processing & pattern matching |
| Collections | Built-in | Counter for frequency analysis |

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install numpy jupyter
```

### Running the Labs
```bash
# Navigate to the lab directory
cd "f:/6thsem/AI(LAB)/"

# Launch Jupyter Notebook
jupyter notebook

# Open any .ipynb file to run interactively
```

---

## 📖 Course Materials

- **Textbook:** *Artificial Intelligence: A Modern Approach* (4th Edition) - Russell & Norvig
- **Lab Manuals:** Available in `.docx` and `.pdf` formats
- **Scoring Rubrics:** Evaluation criteria included for each lab

---

## 📝 Evaluation Rubrics

Each lab is evaluated based on:
- ✅ Code correctness & functionality
- ✅ Understanding of AI concepts
- ✅ Proper use of data structures
- ✅ Code documentation & comments
- ✅ Completion of post-lab tasks

---

## 🎯 Learning Outcomes

After completing these labs, students will be able to:
1. Write efficient Python code for AI applications
2. Implement fundamental AI agent architectures
3. Apply NumPy for numerical computations
4. Design simple reflex and learning-based agents
5. Process multilingual text data using regex
6. Understand agent components: PEAS (Performance, Environment, Actuators, Sensors)

---

## 👨‍💻 Author

**Name:** [Your Name]  
**Roll Number:** FA21-CSE-040  
**Course:** BS Computer Science - 6th Semester  
**Session:** Spring 2026

---

## 📄 License

This repository is for academic purposes only. Unauthorized distribution or plagiarism is strictly prohibited.

---

> **Note:** Ensure all input validations are properly handled when running interactive cells. Some labs require user input during execution.

🌟 **Happy Coding & Learning AI!**
