# [Sudoku Solver](https://www.freecodecamp.org/learn/quality-assurance/quality-assurance-projects/sudoku-solver)

<p>
  built a sudoku solver using nodejs express and chai for functionelle and unit test ,
  check https://repl.it/@CharlesDickens1/boilerplate-project-sudoku-solver-1#README.md for working demo

</p>


<h2>user Story</h2>
All puzzle logic can go into /controllers/sudoku-solver.js
All routing logic can go into /routes/api.js
See the puzzle-strings.js file in /controllers for some sample puzzles your application should solve
To run the challenge tests on this page, set NODE_ENV to test without quotes in the .env file
To run the tests in the console, use the command npm run test. To open the Repl.it console, press Ctrl+Shift+P (Cmd if on a Mac) and type "open shell"
Write the following tests in tests/1_unit-tests.js:

Logic handles a valid puzzle string of 81 characters
Logic handles a puzzle string with invalid characters (not 1-9 or .)
Logic handles a puzzle string that is not 81 characters in length
Logic handles a valid row placement
Logic handles an invalid row placement
Logic handles a valid column placement
Logic handles an invalid column placement
Logic handles a valid region (3x3 grid) placement
Logic handles an invalid region (3x3 grid) placement
Valid puzzle strings pass the solver
Invalid puzzle strings fail the solver
Solver returns the the expected solution for an incomplete puzzzle
Write the following tests in tests/2_functional-tests.js

Solve a puzzle with valid puzzle string: POST request to /api/solve
Solve a puzzle with missing puzzle string: POST request to /api/solve
Solve a puzzle with invalid characters: POST request to /api/solve
Solve a puzzle with incorrect length: POST request to /api/solve
Solve a puzzle that cannot be solved: POST request to /api/solve
Check a puzzle placement with all fields: POST request to /api/check
Check a puzzle placement with single placement conflict: POST request to /api/check
Check a puzzle placement with multiple placement conflicts: POST request to /api/check
Check a puzzle placement with all placement conflicts: POST request to /api/check
Check a puzzle placement with missing required fields: POST request to /api/check
Check a puzzle placement with invalid characters: POST request to /api/check
Check a puzzle placement with incorrect length: POST request to /api/check
Check a puzzle placement with invalid placement coordinate: POST request to /api/check
Check a puzzle placement with invalid placement value: POST request to /api/check
