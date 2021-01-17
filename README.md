# [Sudoku Solver](https://www.freecodecamp.org/learn/quality-assurance/quality-assurance-projects/sudoku-solver)

<p>
  built a sudoku solver using nodejs express and chai for functionelle and unit test ,
  check https://repl.it/@CharlesDickens1/boilerplate-project-sudoku-solver-1#README.md for working demo

</p>


<h2>user Story</h2>

<section id="instructions">
<ul>
<li>All puzzle logic can go into <code>/controllers/sudoku-solver.js</code></li>
<li>All routing logic can go into <code>/routes/api.js</code></li>
<li>See the <code>puzzle-strings.js</code> file in <code>/controllers</code> for some sample puzzles your application should solve</li>
<li>To run the challenge tests on this page, set <code>NODE_ENV</code> to <code>test</code> without quotes in the <code>.env</code> file</li>
<li>To run the tests in the console, use the command <code>npm run test</code>. To open the Repl.it console, press Ctrl+Shift+P (Cmd if on a Mac) and type "open shell"</li>
</ul>
<p>Write the following tests in <code>tests/1_unit-tests.js</code>:</p>
<ul>
<li>Logic handles a valid puzzle string of 81 characters</li>
<li>Logic handles a puzzle string with invalid characters (not 1-9 or <code>.</code>)</li>
<li>Logic handles a puzzle string that is not 81 characters in length</li>
<li>Logic handles a valid row placement</li>
<li>Logic handles an invalid row placement</li>
<li>Logic handles a valid column placement</li>
<li>Logic handles an invalid column placement</li>
<li>Logic handles a valid region (3x3 grid) placement</li>
<li>Logic handles an invalid region (3x3 grid) placement</li>
<li>Valid puzzle strings pass the solver</li>
<li>Invalid puzzle strings fail the solver</li>
<li>Solver returns the the expected solution for an incomplete puzzzle</li>
</ul>
<p>Write the following tests in <code>tests/2_functional-tests.js</code></p>
<ul>
<li>Solve a puzzle with valid puzzle string: POST request to <code>/api/solve</code></li>
<li>Solve a puzzle with missing puzzle string: POST request to <code>/api/solve</code></li>
<li>Solve a puzzle with invalid characters: POST request to <code>/api/solve</code></li>
<li>Solve a puzzle with incorrect length: POST request to <code>/api/solve</code></li>
<li>Solve a puzzle that cannot be solved: POST request to <code>/api/solve</code></li>
<li>Check a puzzle placement with all fields: POST request to <code>/api/check</code></li>
<li>Check a puzzle placement with single placement conflict: POST request to <code>/api/check</code></li>
<li>Check a puzzle placement with multiple placement conflicts: POST request to <code>/api/check</code></li>
<li>Check a puzzle placement with all placement conflicts: POST request to <code>/api/check</code></li>
<li>Check a puzzle placement with missing required fields: POST request to <code>/api/check</code></li>
<li>Check a puzzle placement with invalid characters: POST request to <code>/api/check</code></li>
<li>Check a puzzle placement with incorrect length: POST request to <code>/api/check</code></li>
<li>Check a puzzle placement with invalid placement coordinate: POST request to <code>/api/check</code></li>
<li>Check a puzzle placement with invalid placement value: POST request to <code>/api/check</code></li>
</ul>
</section>



