# SAT-Solving

## Description

This repository contains exercises and implementations related to **Boolean Satisfiability (SAT) solving**.

The exercises focus on understanding how Boolean formulas can be represented, transformed, and solved using SAT-solving techniques.

## Learning Objectives

The main goals of these exercises are to:

- Understand the **Boolean satisfiability problem (SAT)**
- Work with Boolean variables and logical operators
- Convert Boolean formulas into **CNF (Conjunctive Normal Form)**
- Construct and interpret **CNF clauses**
- Understand SAT solver algorithms
- Solve logical constraints using SAT solvers
- Analyze whether a formula is **satisfiable or unsatisfiable**

## SAT Problem

The SAT problem asks whether there exists an assignment of Boolean values (`True` or `False`) to variables that makes a given Boolean formula true.

For example:

```text
(A OR B) AND (NOT A OR C)
```

A satisfying assignment could be:

```text
A = False
B = True
C = True
```

Therefore, the formula is satisfiable.

## Exercises

The repository may contain exercises covering topics such as:

1. Boolean formula representation
2. Conversion to CNF
3. SAT encoding
4. Clause generation
5. Using a SAT solver
6. Finding satisfying assignments
7. Determining whether formulas are satisfiable
8. Modeling real-world constraints as SAT problems

## Example

Consider the formula:

```text
(A OR B) AND (NOT A OR B)
```

A SAT solver searches for an assignment of values to `A` and `B` that satisfies all clauses.

One possible satisfying assignment is:

```text
A = False
B = True
```

## Project Structure

```text
.
├── README.md
├── exercises/
│   ├── exercise1/
│   ├── exercise2/
│   └── exercise3/
├── src/
│   └── ...
└── tests/
    └── ...
```

## Requirements

The requirements depend on the implementation. For example:

- Python 3.x
- A SAT solver library, if used
- Git

Install required Python packages with:

```bash
pip install -r requirements.txt
```

## Running the Exercises

Clone the repository:

```bash
git clone <repository-url>
cd <repository-name>
```

Run an exercise, for example:

```bash
python exercises/exercise1/main.py
```

## Results

For each exercise, the program should indicate whether the given formula or set of constraints is:

- **SAT** – a satisfying assignment exists
- **UNSAT** – no satisfying assignment exists

When applicable, the satisfying assignment is also displayed.

## Purpose

These exercises are intended for educational purposes and provide practical experience with SAT solving, Boolean logic, and constraint modeling.

## Author

**<Your Name>**
