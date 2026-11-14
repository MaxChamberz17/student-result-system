# Student Result Management System

A menu-driven Python application for managing student records, scores, grades and reports.

It allows users to register students, update their information, enter examination scores and generate result reports.

## Features

* Register new students.
* View all registered students.
* Search for students.
* Update student information.
* Delete student records.
* Enter scores for five subjects.
* Calculate total and average scores.
* Automatically assign grades.
* Generate individual student result reports.
* Display class statistics.
* Rank students according to their average scores.
* Save and load student records using JSON.
* Validate user inputs.

## Grading scale
| Average | Grade | Remark |
|---|---|---|
| 70-100 | A | Excellent |
| 60-69 | B | Very Good |
| 50-59 | C | Good |
| 45-49 | D | Pass |
| 0-44 | F | Fail |

## Technologies Used

* Python
* JSON
* Visual Studio Code

## Subjects

1. Mathematics
2. English
3. Computer Science
4. Physics
5. Chemistry


## How to Run

1. Install Python.
2. Open the project folder in Visual Studio Code.
3. Open the terminal.
4. Run the following command:

```bash
python main.py
```

## How to run
```
git clone https://github.com/<your-username>/student-result-system.git
cd student-result-system
python main.py
```

## Data Storage

The system uses JSON to store student records and examination scores. This allows information to remain available after the program closes.


## Python concepts used
Variables and type conversion, if/elif/else, for/while loops, lists, tuples, dictionaries, functions, sorting (`sorted` with `key`), try/except/else/finally, file handling (JSON), modules, OOP (`Student` class), `datetime`, `os`, `json`, `re`.

