Assessor: Brian 

Repo: https://github.com/patmccartney2/credit_check_proj

## Functionality: 4

Notes:

- [x] Student completes through Iteration 3

## Mechanics: 3

Notes:

* The validation_output method returns nil instead of the correct string. It PRINTS the string, but it does not return it. Your tests fail because of that. Make sure you understand difference 

The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [x] uses methods, arguments, and return values to break code into logical components
- [x] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 3

Notes:

* Your terminal interface should be in a separate runner file. If I run your tests right now, I HAVE to use the terminal interface. 
* Instead of using instance variables, your methods should be taking input as arguments and returning the output. This is evidenced by your tests, for example test_it_can_double_every_other_number. You should be able to test the double_every_other_number method by itself, but you have to run take_card_and_split first for it to work. double_every_other_number should take the split number as input. You would do this passing of input in your valid_number? method.

The student(s):

- [ ] adheres to the Single Responsibility and DRY principles
- [ ] creates Objects and Classes that appropriately encompass state and behavior
- [ ] uses instance and local variables appropriately
- [ ] writes readable code with the following characteristics:
    * Variable and method names are self explanatory
    * Methods are under 7 lines
    * Lines of code are under 80 characters
    * Project directory structure adheres to convention
    * A linter reports less than 5 errors

## Testing: 3

Notes:

The student(s):

- [ ] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [ ] names and orders tests so that a test file reads like documentation
- [ ] writes Minitest assertions that accurately test a piece of functionality
- [ ] writes a test before writing code that implements the behavior to make that test pass
- [ ] writes both integration and unit tests

## Version Control: 2

Notes:

* You need to be committing more often
* You need to be using PRs

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [ ] makes commits in small chunks of functionality
- [ ] submits and merges Pull Requests using the Github interface
