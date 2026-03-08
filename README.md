# 🐍 Python Mini Projects

A collection of beginner-friendly Python projects covering games, utilities, and automation tools.

---

## 📁 Projects Overview

| Project | File | Description |
|---|---|---|
| 🐍 Snake Water Gun | `SnakeWaterGun.py` | Command-line game (like Rock Paper Scissors) |
| 📂 File Organizer | `fileorginizer.py` | Auto-sorts files into folders by type |
| 🔐 Password Manager | `password.py` | Save & retrieve passwords from a text file |
| 📄 PDF Merger | `pdfmerge.py` | GUI app to merge multiple PDFs into one |
| ❓ Quiz App | `quiz.py` | Multiple-choice terminal quiz game |
| ⌨️ Typing Speed Tester | `typingspeed.py` | Measures WPM and accuracy |
| 💧 Water Reminder | `waterreminder.py` | Desktop notifications to remind you to drink water |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have **Python 3.x** installed. Then install the required libraries:

```bash
pip install pyperclip pypdf plyer
```

> **Note:** `tkinter` comes pre-installed with most Python distributions.

---

## 📌 Project Details

### 🐍 Snake Water Gun (`SnakeWaterGun.py`)
A terminal-based game similar to Rock Paper Scissors with a twist — Snake drinks Water, Water blocks Gun, Gun kills Snake.

**How to run:**
```bash
python SnakeWaterGun.py
```
**How to play:** Enter `s` (Snake), `w` (Water), or `g` (Gun) when prompted. The computer picks randomly and the winner is announced.

---

### 📂 File Organizer (`fileorginizer.py`)
Automatically organizes files in the current directory into categorized subfolders.

**Supported file types:**
- PDFs → `PDFs/`
- Word documents → `Word_Files/`
- Images (jpg, jpeg, png) → `Images/`
- Videos (mp4, mkv) → `Videos/`
- Text files → `Text_Files/`

**How to run:**
```bash
python fileorginizer.py
```
> ⚠️ Run this script from inside the folder you want to organize.

---

### 🔐 Password Manager (`password.py`)
A simple CLI tool to save and retrieve passwords stored in a local `passwords.txt` file. Automatically copies retrieved passwords to your clipboard.

**Requirements:** `pyperclip`

**How to run:**
```bash
python password.py
```
**Features:**
- Save a password for any website
- Retrieve and auto-copy a password to clipboard
- Simple menu-driven interface

---

### 📄 PDF Merger (`pdfmerge.py`)
A GUI application (built with Tkinter) that lets you select multiple PDF files and merge them into a single PDF.

**Requirements:** `pypdf`, `tkinter`

**How to run:**
```bash
python pdfmerge.py
```
**Features:**
- Browse and select multiple PDF files
- Merge them into a single output file
- Choose where to save the merged PDF

---

### ❓ Quiz App (`quiz.py`)
A terminal-based multiple-choice quiz with 4 questions. Tracks your score and displays it at the end.

**How to run:**
```bash
python quiz.py
```
**Topics covered:** Geography, Math, Science, Literature

---

### ⌨️ Typing Speed Tester (`typingspeed.py`)
Tests your typing speed by presenting a random sentence and measuring how fast and accurately you type it.

**How to run:**
```bash
python typingspeed.py
```
**Output includes:**
- Time taken (seconds)
- Words per minute (WPM)
- Accuracy percentage

---

### 💧 Water Reminder (`waterreminder.py`)
Sends a desktop notification every 30 minutes reminding you to drink water. Runs in the background.

**Requirements:** `plyer`

**How to run:**
```bash
python waterreminder.py
```
> The default interval is **30 minutes**. You can change it by modifying the value passed to `water_reminder()` at the bottom of the file.

---

## 🛠️ Dependencies Summary

```bash
pip install pyperclip pypdf plyer
```

| Library | Used In |
|---|---|
| `pyperclip` | Password Manager |
| `pypdf` | PDF Merger |
| `plyer` | Water Reminder |
| `tkinter` | PDF Merger (built-in) |
| `random`, `time`, `os`, `shutil` | Various (standard library) |

---

## 👤 Author

Built as a collection of beginner Python practice projects.
