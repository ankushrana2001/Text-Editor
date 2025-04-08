# 📝 My Text Editor (Tkinter GUI)

A simple and beginner-friendly text editor built using Python's Tkinter library. This project replicates the basic functionality of a notepad, allowing users to create, open, and save `.txt` files with a graphical user interface.

## 📺 Reference

This project is based on the tutorial:  
[🎥 Python Text Editor GUI using Tkinter - YouTube](https://youtu.be/mCBTrr_R4qw?si=OgnRPBLza_-cnWpD)

## ✨ Features

- **New File**: Clears the current text area to start a new file.
- **Open File**: Opens existing `.txt` files using a file dialog.
- **Save File**: Saves the current content to a `.txt` file.
- **Exit**: Closes the editor safely.
- **Stylized Text Area**: Uses a clean Helvetica font with blue text and word wrapping.

## 🛠️ Requirements

- Python 3.x
- Tkinter (usually comes pre-installed with Python)

## 🚀 How to Run

1. Make sure Python is installed on your system.
2. Download or clone this repository.
3. Run the following command:

```bash
python Text-Editor.py
```

## 🧾 Code Overview

- `tk.Tk()` sets up the main application window.
- `Menu` is used to create a functional menu bar.
- `Text` widget is used as the editable text area.
- File handling is done using standard Python file dialogs and I/O.

## 📁 File Structure

```
Text-Editor/
├── Text-Editor.py
└── README.md
```

## 📌 Notes

- Only supports plain text files (`.txt`).
- Minimal styling and no advanced features like syntax highlighting or tabs (perfect for learning).
