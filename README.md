# MIPS Bin Packing Solver

A MIPS assembly program that implements **First Fit (FF)** and **Best Fit (BF)** bin packing heuristics.
The program reads a list of item sizes from a text file (values between 0.0 and 1.0) and determines the **minimum number of bins** needed to store them.

---

## Features

* Supports **First Fit** and **Best Fit** heuristics.
* Validates input to ensure correct float format (`0.0 < item <= 1.0`).
* Outputs the bin allocation and minimum number of bins to `output.txt`.

---

## How to Run

1. Open the project in a **MIPS simulator** (e.g., MARS).
2. Run the program.
3. Enter the **input file name** (text file with one float per line).
4. Choose the heuristic: `FF` for First Fit or `BF` for Best Fit.
5. Check `output.txt` for the results.

---

## Input File Format

* Plain text file.
* Each line contains **one float value** between 0.0 and 1.0.
* Example:

```
0.25
0.5
0.75
1.0
```

---

## Output

* `output.txt` contains:

  * **Minimum number of bins used**
  * Items assigned to each bin
* Example:

```
Minimum Number of Bins: 2
Bin 0: Item 0 | Item 2
Bin 1: Item 1
```

---

## Technologies

* **MIPS Assembly**
* Tested with **MARS MIPS Simulator**

---

## Notes

* Only valid float inputs between 0.0 and 1.0 are accepted.
* Exiting the program: type `Q` or `q` when prompted for input file.
  
---
