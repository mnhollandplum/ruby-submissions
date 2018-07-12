Assessor:

Repo:

## Functionality: 3

Notes:

- [x] Student completes through Iteration 3

## Mechanics: 3

Notes:

The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [x] uses methods, arguments, and return values to break code into logical components
- [x] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 2

Notes:

* I like that you check for the correct number of parameters
* Break up your split_lines_over_80_characters method into one high level method that calls helper methods.
* You can remove the unused attr_readers
* Instead of passing the FileIO object to the Translator, you can just pass the text to be translated.
* In ReverseTranslator, you do a good job making the high level method. You could refactor the map into another method
* Prefer that you pass in the input to be translated rather than reading and storing in instance variable
* You're breaking SRP when you call the file reading method in your get_braille_arrays method that breaks the input up

The student(s):

- [ ] adheres to the Single Responsibility and DRY principles
- [ ] utilizes Test Driven Development to drive the design of the code.
- [ ] creates Objects and Classes that appropriately encompass state and behavior
- [ ] uses instance and local variables appropriately
- [ ] writes readable code with the following characteristics:
    * Variable and method names are self explanatory
    * Methods are under 7 lines
    * Lines of code are under 80 characters
    * Project directory structure adheres to convention
    * A linter reports less than 5 errors

## Testing: 2

Notes:

* Translator test isn't working

The student(s):

- [ ] writes Minitest tests that describe the expected behavior of a program
- [ ] names and orders tests so that a test file reads like documentation
- [ ] writes Minitest assertions that accurately test a piece of functionality
- [ ] translates technical specifications into tests
- [ ] writes a test before writing code that implements the behavior to make that test pass
- [ ] writes both integration and unit tests

## Version Control: 2

Notes:

* Make sure both partners are committing
* Make sure you get comfortable with the git workflow we have covered thus far

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [x] makes commits in small chunks of functionality
- [x] submits and merges Pull Requests using the Github interface
