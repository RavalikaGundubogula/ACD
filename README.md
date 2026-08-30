# ACD
# Automata Theory & Subset Construction in Python

A hands-on implementation and visualization of **Deterministic Finite Automata (DFA)**, **Non-Deterministic Finite Automata (NFA)**, and the **Subset Construction Algorithm (NFA to DFA Conversion)** using Python and Graphviz.

---

## Video Walkthrough

Watch the complete explanation and step-by-step code demonstration:

https://github.com/Akshara-Yannam/ACD/blob/main/Untitled.mov

---

##  Project Highlights

- **DFA Implementation:** Formal definition using 5-tuples (states, alphabet, transition functions, start state, final states) and state diagram generation.
- **NFA Simulation:** Handles branching transitions where a state-symbol pair leads to multiple potential states or empty sets ($\emptyset$).
- **NFA $\rightarrow$ DFA Conversion (Subset Construction):**
  - Explores reachable composite states starting from $\{q_0\}$ using a queue-based approach.
  - Automatically identifies final accepting states containing any original NFA final state.
  - Generates side-by-side visual graphs and transition tables for comparison.

---

## Notebook Structure

| Section | Description |
| :--- | :--- |
| **1. Basic DFA** | Defines a 3-state DFA and generates its directed state graph. |
| **2. Basic NFA** | Demonstrates set-valued transition mappings for non-deterministic behavior. |
| **3. NFA to DFA Converter** | Implements the power-set / subset construction algorithm and renders both the original and converted state machines. |

---

## Installation & Requirements

Use Google Colab 

If running outside Google Colab, install the required dependencies:

```bash
pip install graphviz
