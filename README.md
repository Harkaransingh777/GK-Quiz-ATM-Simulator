# C Beginner Projects: GK Quiz & ATM Simulator

A collection of foundational C programs demonstrating essential procedural programming concepts, including functions, control flow structures, variable scoping, and user input/output handling.

---

## 📋 Overview

This repository contains two command-line interface (CLI) applications written in C:

1. **HKS General Knowledge Quiz System**: An interactive quiz program that prompts user details, serves trivia questions, and provides feedback choices.
2. **SBI ATM System Simulator**: A basic banking terminal prototype featuring PIN-based authentication and service option menus.

---

## 🚀 Projects Included

### 1. HKS GK Quiz (`quiz.c`)
An interactive CLI-based quiz game.

* **Key Concepts Featured:**
  * Function declarations and definitions.
  * Conditional branching (`if-else`, `switch-case`).
  * Basic array string handling (`char name[]`, `char feed[]`).
* **Game Flow:**
  * User enters their name to register.
  * Navigates through 3 General Knowledge questions.
  * Offers an optional feedback prompt at the end.

---

### 2. SBI ATM Simulator (`atm.c`)
A minimal simulation of an Automated Teller Machine (ATM) transaction portal.

* **Key Concepts Featured:**
  * Multi-function architecture (`atm()` and `atm1()`).
  * Authentication logic using credential comparison.
  * Selection handling via standard symbol inputs (`-`, `+`, `|`).
* **System Capabilities:**
  * **PIN Verification:** Validates user against a preset PIN (`1234`).
  * **Withdrawal Menu (`-`):** Informs users about standard withdrawal limits.
  * **Deposit Menu (`+`):** Highlights pan-card regulatory thresholds for high deposits.
  * **Balance Inquiry (`|`):** Displays account status details.

---

## 🛠️ Built With

* **Language:** C
* **Compiler:** Any standard C compiler (e.g., GCC, Clang, or MSVC)
* **Libraries Used:** `<stdio.h>`, `<conio.h>`

---

## 💻 How to Run Locally

### Prerequisites
Make sure you have a C compiler installed on your system (such as **GCC** via MinGW on Windows or Xcode Command Line Tools on macOS).
