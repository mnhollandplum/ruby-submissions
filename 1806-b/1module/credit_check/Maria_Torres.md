Assessor: Sal

Repo: https://github.com/tmaria17/credit_check_2

## Functionality: 3

Notes:

* Generally looks good!

- [x] Student completes through Iteration 3

## Mechanics: 3

Notes:

* Would prefer that you have a runner method that uses return values as input for the next method.
* Currently you have a structure that feels like a chain (links from one method to the next to the next from directly within the method). This is a very flat structure. Introducing a runner or `CEO` method would make it so that your structure had more of a hierarchy and would provide better opportunity for abstraction/testing at a unit level.

The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [ ] uses methods, arguments, and return values to break code into logical components
- [x] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 3

Notes:

* Again, generally think this looks good!

The student(s):

- [x] adheres to the Single Responsibility and DRY principles
- [x] creates Objects and Classes that appropriately encompass state and behavior
- [x] uses instance and local variables appropriately
- [x] writes readable code with the following characteristics:
    * Variable and method names are self explanatory
    * Methods are under 7 lines
    * Lines of code are under 80 characters
    * Project directory structure adheres to convention
    * A linter reports less than 5 errors

## Testing: 2

Notes:

* Would like to see those tests that you have commented out implemented.
* Think that having methods that are organized as a chain (as described above) can make testing more difficult.
* Creating methods that have a single input and single output (that don't then call to another method) can make unit testing easier.
* Because of the structure of your code, each test that you write is going to be an integration test.

The student(s):

- [x] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [x] names and orders tests so that a test file reads like documentation
- [x] writes Minitest assertions that accurately test a piece of functionality
- [ ] writes both integration and unit tests

## Version Control: 2

Notes:

* Like the commits, and looks like you have a branch.
* Would've liked to see a pull request from that branch!

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [x] makes commits in small chunks of functionality
- [x] submits and merges Pull Requests using the Github interface
