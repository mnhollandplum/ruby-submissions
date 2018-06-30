Assessor: Sal/Brian

Repo: https://github.com/averimj/Credit_Check

## Functionality: 2

Notes:

* Looks like you were really close!

- [ ] Student completes through Iteration 3

## Mechanics: 2

Notes:

* Generally moving in the right direction!
* See comment below about instance variables!
* The methods don't take input. The card number is hard coded into initialize
* Instead of storing the data in instance variables, I would prefer to see you using arguments and return values. For instance, instead of calling `reverse` in the `validation_output` method and having that reverse method set the @card_numb instance variable, pass the card number into the reverse method and have it output the reversed number. The reverse method would look like:

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
* Like the way you're writing your methods!
* Like how you're thinking through things.
* Think that you have some good logic here.
* *Main Comment:* Recommend that you switch to using return values instead of instance variables. Reserve instance variables for those things that feel like the *state* of the object you're dealing with. Use return values when you just need to move information around.

The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [ ] uses methods, arguments, and return values to break code into logical components
- [ ] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 3

Notes:

* The card number should be passed as an argument to the valid_number? and validation_output methods, not hard coded into the initialize. 

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

* Seems to be moving down the right path!
* Think you could have some more tests, but you are definitely doing the right thing. Just a little more of it!

The student(s):

- [x] writes Minitest tests that describe the expected behavior of a program according to technical specifications
- [x] names and orders tests so that a test file reads like documentation
- [x] writes Minitest assertions that accurately test a piece of functionality
- [ ] writes both integration and unit tests

## Version Control: 2

Notes:

* For next project see if you can add some commits/pull requests!
* I know you had some issues with git, so I'm not able to see any commits besides the ones you did at the end of the project. In the future, make sure you are committing frequently in small chunks of functionality. 

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [ ] makes commits in small chunks of functionality
- [ ] submits and merges Pull Requests using the Github interface
