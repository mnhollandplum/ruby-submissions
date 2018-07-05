Assessor: Megan McMahon

Repo: https://github.com/henryquante/credit_check

## Functionality: 2

Notes:

* The approach that you took here is really interesting! We would have liked to see you use an enumerable like #each to iterate through the array of numbers, rather than doing it by hand.

- [ ] Student completes through Iteration 3

## Mechanics: 2

Notes:

* It looks like you used the global variable naming convention to distinguish between numbers in the original array and numbers being doubled and summed - this is very confusing to read through and I think you would be better served with more explicit local variable names and no global variables.
* I would also encourage you to try to reach for an enumerable before iterating through an array by hand.  With a small collection of numbers, this doesn't seem like a big deal, but what if credit card numbers had 200 digits, or 1000?

The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [ ] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [ ] uses methods, arguments, and return values to break code into logical components
- [x] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 2

Notes:

* Your `valid_number?` method has a lot going on inside of it (the whole algorithm) - try to break each piece of the algorithm into their own methods.  (using enumerables should help with this)

The student(s):

- [ ] adheres to the Single Responsibility and DRY principles
- [x] creates Objects and Classes that appropriately encompass state and behavior
- [ ] uses instance and local variables appropriately
- [ ] writes readable code with the following characteristics:
    * Variable and method names are self explanatory
    * Methods are under 7 lines
    * Lines of code are under 80 characters
    * Project directory structure adheres to convention
    * A linter reports less than 5 errors

## Testing: 2

Notes:

* I really like that you have tests for methods that don't yet exist in your Credit Check class!  This sets you up for Test Driven Development (TDD) which we will cover soon.

The student(s):

- [ ] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [x] names and orders tests so that a test file reads like documentation
- [ ] writes Minitest assertions that accurately test a piece of functionality
- [x] writes a test before writing code that implements the behavior to make that test pass
- [ ] writes both integration and unit tests

## Version Control: 3

Notes:

* Your commit history looks great, and the pull request is right on track!

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [x] makes commits in small chunks of functionality
- [x] submits and merges Pull Requests using the Github interface
