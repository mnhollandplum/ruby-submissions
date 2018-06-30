Assessor: Sal

Repo: https://github.com/dmeskis/credit_check

## Functionality: 4

Notes:

* Like that you implemented this in a way that accounts for AmEx numbers!

- [x] Student completes through Iteration 3

## Mechanics: 3

Notes:

* Generally looks good!
* Methods are very readable. Can tell what each one should do and what it does.
* Doing a good job of splitting functionality into smaller chunks.

The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [x] uses methods, arguments, and return values to break code into logical components
- [x] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 3

* *Main Comment:* `valid_number?` is on the right path, but use return values in place of instance variables.
* Instance variables should be reserved for those things that are actually state, not as a way to avoid using return values.
* Recommend that you prefer a pattern of using the return value from one method to be the input/argument of another method.

Notes:

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

* Would like to see tests of supporting methods at this point.
* Think there *could be* an argument for only testing the methods that you did since those are the only methods that I'm going to be able to access from outside the class, but at this point would err on the side of over-testing vs. under-testing.
* Currently all tests are integration tests. Testing those supporting methods would allow you to have some unit tests in place.

The student(s):

- [x] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [x] names and orders tests so that a test file reads like documentation
- [x] writes Minitest assertions that accurately test a piece of functionality
- [ ] writes both integration and unit tests

## Version Control: 2

Notes:

* Pull request would have pulled you up to a 3!

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [x] makes commits in small chunks of functionality
- [ ] submits and merges Pull Requests using the Github interface
