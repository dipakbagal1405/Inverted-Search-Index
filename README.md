# Inverted Search Index

A high-performance text-based search database implementation in C utilizing the **Inverted Index** architecture. This data structure maps words directly to their locations in a set of documents, forming the core foundation of modern search engines. It utilizes **Hashing** for optimized word mapping and **Singly Linked Lists** to handle document records.

## 🚀 Features
* **Create Database:** Scans multiple input text files, parses unique words, and indexes them using a Hash Table.
* **Display Database:** Formats and prints the inverted index showing words, their total frequencies, and file-wise distribution.
* **Search Database:** Searches for any keyword instantly and retrieves all the files containing that word along with its frequency.
* **Save/Update Database:** Backs up the entire index into a persistent file (`db.txt`) and allows reloading it for future updates.

## 🛠️ Tech Stack & Concepts
* **Language:** C Programming
* **Data Structures:** Hash Table (Chaining for collision resolution), Singly Linked Lists.
* **Concepts:** Advanced File Handling (File I/O), String Parsing, Modular Code Design, Automation via Makefile.

## 💻 How to Run
This project includes a `Makefile` for automated compilation. Run the following commands in your terminal:

1. **Compilation:**
   ```bash
   make
   ```

2. **Execution (Pass files as arguments):**
   ```bash
   ./a.out file1.txt file2.txt file3.txt
   ```
