Assessor: Sal

Repo: https://github.com/KellyMarcilliat/Credit-Check-2

## Functionality: 4

Notes:

* Great job at reaching for the extensions!

- [x] Student completes through Iteration 3

## Mechanics: 3

Notes:

* *Main Comment:* Those instance variables! You're using instance variables where you should be using return values. Reserve instance variables for things that actually feel like the state of the object. In this particular case I would write this algorithm without *any* instance variables.

The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [ ] uses methods, arguments, and return values to break code into logical components
- [x] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 3

Notes:

* Generally looks good. Again here, instance variable use could be improved.
* Really like that you have a separate class for the check digit. I don't know that I would make the same decision, but it shows that you're thinking about Single Responsibility.
* Don't know where to put this comment, but put your readme in the root of your project directory! Currently it's in `lib`. If you put it in the base directory, GitHub will show it to people when they visit your project page.
* There's a `CheckSum` class that has an amount of repetition from `CreditCheck`
* Both classes have a setter method when numbers should be stored on creation
* All variables are instance variables.
* Runner also uses instance variables.

The student(s):

- [x] adheres to the Single Responsibility and DRY principles
- [x] creates Objects and Classes that appropriately encompass state and behavior
- [ ] uses instance and local variables appropriately
- [x] writes readable code with the following characteristics:
    * Variable and method names are self explanatory
    * Methods are under 7 lines
    * Lines of code are under 80 characters
    * Project directory structure adheres to convention
    * A linter reports less than 5 errors

## Testing: 3

Notes:

* Generally looks good!
* Repeated tests in `check_sum_test`
* `holds_card_number` test does not test if it is holding the number
* No real integration testing, tests never touch the methods that bring it all
together

The student(s):

- [x] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [x] names and orders tests so that a test file reads like documentation
- [x] writes Minitest assertions that accurately test a piece of functionality
- [x] writes a test before writing code that implements the behavior to make that test pass
- [x] writes both integration and unit tests

## Version Control: 3

Notes:

* Like the use of pull requests and commits!

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [x] makes commits in small chunks of functionality
- [x] submits and merges Pull Requests using the Github interface
