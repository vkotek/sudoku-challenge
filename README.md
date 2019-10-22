# Sudoku Challenge

Welcome to the Sudoku Challenge!

### Objective:
- Create a program to solve Sudoku puzzles

### Input:
- CSV file with one columns "puzzle". Generate it [here](https://qqwing.com/generate.html).

```csv
Puzzle,
....5..18..9...5.........271.8.....5.65..1.9..9....2..72.98....4..6........1..68.,
```

### Output:
- CSV file with the solution.

```csv
Solution,
632759418879214536514836927148392765265471893397568241726983154481625379953147682,
```

### Instructions:

Your script should take one argument <input.csv> and produce a file with the solution <output.csv>

### Example:

$ solver.py input.csv
