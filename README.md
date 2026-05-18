# Deloitte Virtual Internship – Task 1

## Project Overview

This project focuses on converting telemetry data from two different JSON input formats into a single unified output format.

The task demonstrates:
- JSON data processing
- Data transformation
- Python function implementation
- Unit testing

---

# Project Structure

```bash
task1/
│
├── data-1.json
├── data-2.json
├── data-result.json
├── main.py
└── README.md
```

---

# Understanding the Input Formats

## Input Files

Open the following files:

- `data-1.json`
- `data-2.json`

Both files contain the same telemetry information, but each uses a different JSON structure.

Your goal is to normalize both formats into a common structure.

---

# Target Unified Format

Open:

```bash
data-result.json
```

This file contains the expected unified output format.

Your conversion functions should produce data matching this structure exactly.

---

# Tasks to Complete

Open:

```bash
main.py
```

Locate the following functions marked with `IMPLEMENT:`:

```python
convertFromFormat1(jsonObject)
convertFromFormat2(jsonObject)
```

Complete both functions so they correctly transform the input data into the target format.

---

# Running the Project

## Run Locally

Make sure Python 3 is installed.

Execute the following command in the terminal:

```bash
python main.py
```

---

## Online IDE (Optional)

You may also:
- upload the project files into any online Python editor
- run `main.py`

Examples:
- Replit
- Programiz
- OnlineGDB

---

# Running the Tests

The project includes automated unit tests.

A successful implementation will show:

```text
All tests passed
```

with no failures.

---

# Notes

- Ignore unrelated console output or warnings.
- Focus only on the unit test results.
- Ensure both conversion functions return the exact expected structure.

---

# Skills Demonstrated

- Python programming
- JSON parsing
- Data transformation
- Unit testing
- Problem solving
- Clean code practices
