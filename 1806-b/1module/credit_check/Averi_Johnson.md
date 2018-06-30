Assessor: Brian

Repo: https://github.com/averimj/Credit_Check

## Functionality: 2

Notes:

- [ ] Student completes through Iteration 3

## Mechanics

Notes:

* Instead of storing the data in instance variables, I would prefer to see you using arguments and return values. For instance, instead of calling `reverse` in the `validation_output` method and having that reverse method set the @card_numb variable, pass the card number into the reverse method and have it output the reversed number. The reverse method would look like:

```ruby
def reverse(card_numb)
    card_numb.reverse
end
```

and the call to it in `validation_output` would look like:

```ruby
reversed_number = reverse(card_number)
```

* In `validation_output`, you are printing the output instead of returning it. Make sure you understand the difference between printing and returning.

The student(s):

- [ ] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [ ] implements best-choice enumerable methods to iterate over collections
- [ ] uses boolean expressions and flow control structures to logically manage a program's flow
- [ ] uses methods, arguments, and return values to break code into logical components
- [ ] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design

Notes:

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

* The tests you have look good. I understand you probably ran out of time, but I would prefer that you write the tests for the valid_number? and validation_output methods before tests for the helper methods. 

The student(s):

- [ ] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [ ] names and orders tests so that a test file reads like documentation
- [x] writes Minitest assertions that accurately test a piece of functionality
- [ ] writes both integration and unit tests

## Version Control: 2

Notes:

* I know you had some issues with git, so I'm not able to see any commits besides the ones you did at the end of the project. In the future, make sure you are committing frequently in small chunks of functionality. 

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [ ] makes commits in small chunks of functionality
- [ ] submits and merges Pull Requests using the Github interface
