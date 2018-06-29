Assessor: Brian

Repo: https://github.com/mmbensalah/credit_check_project

## Functionality: 1

Notes:

- [ ] Student completes through Iteration 3

## Mechanics: 2

Notes:

* syntax error when I try to run the code because the validation_one method is a work in progress. Make sure you are only pushing working code. Also missing an end for the class
* In add_double_digits, you don't need to say integer = integer - 9. You can just say integer - 9 because you are using map 

The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [ ] uses methods, arguments, and return values to break code into logical components
- [ ] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 2

Notes:

* Everything is an instance variable. I like that you were doing this to challenge yourself, but in the end this class shouldn't have any instance variables. You should be passing around data using arguments and return values when you can.
* Your valid_number? validation_output methods aren't taking the card number as input, so it does not satisfy the interaction pattern.

The student(s):

- [x] adheres to the Single Responsibility and DRY principles
- [ ] creates Objects and Classes that appropriately encompass state and behavior
- [ ] uses instance and local variables appropriately
- [x] writes readable code with the following characteristics:
    * Variable and method names are self explanatory
    * Methods are under 7 lines
    * Lines of code are under 80 characters
    * Project directory structure adheres to convention
    * A linter reports less than 5 errors

## Testing: 1

Notes:

The student(s):

- [ ] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [ ] names and orders tests so that a test file reads like documentation
- [ ] writes Minitest assertions that accurately test a piece of functionality
- [ ] writes a test before writing code that implements the behavior to make that test pass
- [ ] writes both integration and unit tests

## Version Control: 1

Notes:

* Make sure you only push working code to master
* You should be using git as your work, not pushing everything at once at the end. Ultimately you will find this to be a huge lifesaver when you want to look at earlier versions of your projects. Keep working to get more comfortable with git.
* You could have used a branch to play around with changing everything to instance variables to keep your previous version intact.

The student(s):

- [ ] hosts their code on the master branch of their remote repository
- [ ] makes commits in small chunks of functionality
- [ ] submits and merges Pull Requests using the Github interface
