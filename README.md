# WordCraft

**WordCraft** is a terminal-based text editor built in C, inspired by the simplicity and functionality of classic text editors, aiming to implement over 50% of the key features of MS Word.

## 📦 Features

- Basic text editing (insert, delete, overwrite)
- File I/O (Save/Load)
- Cursor movement & scrolling
- Undo/Redo with stack
- Find & Replace (basic and regex)
- Cut/Copy/Paste
- Multi-file tab simulation
- CLI Help menu
- Text formatting support (rendering tags)

## 🛠️ Build Instructions (Windows - MinGW)

```bash
gcc WordCraft.c -o WordCraft
./WordCraft
