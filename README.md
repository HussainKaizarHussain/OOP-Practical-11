# OOP-Practical-11: CSV Student Records Using File I/O

## Purpose & Aim
- **Aim**: To practise persistent storage, structured records, file modes and file-position operations.
- **Question**: Implement a CSV reader/writer using fstream to store and retrieve student records. Demonstrate seekg(), seekp(), tellg() and tellp().

---

## What to Do
- Define a Student record with fields such as ID, name and marks. Decide and document a simple CSV format.
- Write at least three records to students.csv. Check whether the file opened and whether writing succeeded.
- Read the records back and display them in a readable format. Handle missing or malformed input where practical.
- Use tellg() and seekg() to inspect and change the read position in a simple demonstration.
- Use tellp() and seekp() to inspect and change the write position in a simple demonstration.
- Explain the difference between input (get) and output (put) positions. Avoid assuming raw struct bytes are a portable CSV format.
