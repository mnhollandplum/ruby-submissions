Assessor: Brian 

Repo: https://github.com/mnhollandplum/credit_check

## Functionality: 1

Notes:

- [ ] Student completes through Iteration 3

## Mechanics: 2

Notes:

* @card_divisble at the end of credit_check.rb should be card_divisible. When you try to use an instance variable that hasn't been created yet, like @card_divisible, it defaults to nil. So this program will always print the card is invalid. It does work when you change it to card_divisble

The student(s):

- [x] appropriately uses Strings, Integers, Floats, Ranges, Symbols, Nils, Arrays, and Hashes
- [x] implements best-choice enumerable methods to iterate over collections
- [x] uses boolean expressions and flow control structures to logically manage a program's flow
- [ ] uses methods, arguments, and return values to break code into logical components
- [ ] creates Classes that utilize instance variables, attribute accessors, and instance methods

## Design: 2

Notes:

* Logic looks great!
* Instance variables should only be used to convey the state/attributes of an object
* Your indentations need to line up. The end and the corresponding def/if/do/class statement should be indented at the same level. For instance
* In your sum method, you should be summing the numbers, not shoveling them into an array. 
* I like that you made this mess_around file and attempted to put all of this into a class. Keep pushing yourself.

```ruby  
def integer
  @card_integer = []
  @card_reverse.each do |number|
    @card_integer << number.to_i
    end
  @card_integer
  end
```

should look like

```ruby  
def integer
  @card_integer = []
  @card_reverse.each do |number|
    @card_integer << number.to_i
  end
  @card_integer
end
```

The student(s):

- [x] adheres to the Single Responsibility and DRY principles
- [ ] creates Objects and Classes that appropriately encompass state and behavior
- [ ] uses instance and local variables appropriately
- [ ] writes readable code with the following characteristics:
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

## Version Control: 2

Notes:

* No PRs

The student(s):

- [x] hosts their code on the master branch of their remote repository
- [x] makes commits in small chunks of functionality
- [ ] submits and merges Pull Requests using the Github interface
