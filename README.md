# Sudoko Solver using Backtracking Algorithm

![Sudoko Solver using Backtracking Algorithm](./assets/SudokuSolverUsingBacktrack.gif)

> Sudoku is a logic-based, combinatorial number-placement puzzle. The objective is to fill a 9×9 grid with digits so that each column, each row, and each of the nine 3×3 subgrids that compose the grid contain all of the digits from 1 to 9.
> (Source - [Wikipedia](https://en.wikipedia.org/wiki/Sudoku))

This is a project which takes an input of the sudoku puzzles as an 81 characters long string containing the digits from 0 to 9, where 0 represents an unfilled cell of the Sudoku Board. The objective of the algorithm is to replace all the zeros with valid digits such that the entire Sudoku Puzzle is solved. For doing this in a conventional way, the processor will require to try all 2*10<sup>77</sup> possible combinations in a worst case scenario which is a huge number. So, to solve this problem in a comparatively less time, the **Backtracking Algorithm** is one of the best solutions to it.

## Table of Contents

1. [Requirements](#requirements)
2. [Usage](#usage)


## Requirements

To download and use this code, the minimum requirements are:

* [Python 3.0](https://www.python.org/download/releases/3.0/) and above **OR** [Python 2.2](https://www.python.org/download/releases/2.2/) and above

## Usage

Once the requirements are checked, you can easily download this project and use it on your machine in few simple steps.

* **STEP 1** <br>
    Download this repository as a zip file onto your machine and extract all the files from it.

    ![Download and Extract Zip Folder](./assets/DownloadAndExatractZip.gif)

    <br>

* **STEP 2** <br>
  Run the [solve.py](./solve.py) file using python to see the solution

  ![Run solve.py File Using Python](./assets/RunSolvePythonFile.gif)

> NOTE:
>  
> 1 - If you are using Linux or Mac you will need to change one line of code. Instructions for which are commented in the same file on line #3.
>  
> 2 - The algorithm takes only ~1 second to compute most of the Sudoku Puzzles. It takes more time to show the output on every iteration. So, if you want to skip the visualization part to speed it up, feel free to comment out the lines #28 to #30.

* **STEP 3** <br>
  You can change last digits of the `puzzle0` and `solution0` on lines #5 and #6, respectively, to check the algorithm for different puzzles. There are 5 demo puzzles already given in the [puzzles.py](./puzzles.py) file and their respective solutions are stored in the [solutions.py](./solutions.py) file. Feel free to add your own puzzles to explore more.

