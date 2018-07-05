Assessor: Brian

Repo: https://github.com/NickLindeberg/credit_check

## Functionality

Notes:

- [ ] Student completes through Iteration 3

## Mechanics: 3

Notes:

* `require "../lib/credit_check.rb"` should be `require "./lib/credit_check.rb"`. Remember, we run should run the tests from the root of the project with `ruby test/credit_check_test.rb`
* Your valid_number? method should be returning the value of true or false, NOT `puts`ing it. This method is printing the value to the string, but it is returning nil.


The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [ ] uses methods, arguments, and return values to break code into logical components
- [x] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 3

Notes:

* Should not have executable code at the bottom of credit_check.rb
* If your initalize method doesn't do anything, you can just not write the initialize method
* In test file, expected and actual values should not be indented.

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

## Testing: 3

Notes:

* name your variable "expected" instead of "assumed". You also don't have to set it to a variable if it will fit nicely on one line, for instance in test_total_sum_test.
* Great job testing the helper methods! This is good unit testing.
* Missing tests for valid_number? and validation_output. These are your integration tests

The student(s):

- [ ] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [x] names and orders tests so that a test file reads like documentation
- [x] writes Minitest assertions that accurately test a piece of functionality
- [ ] writes both integration and unit tests

## Version Control: 2

Notes:

No PRs

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [x] makes commits in small chunks of functionality
- [ ] submits and merges Pull Requests using the Github interface
