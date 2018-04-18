Assessor: Mike

Repo: https://github.com/JHighland/Nite_Writer


Notes:
* Application does not match specification
* Does not output to files
* Translation only works from English to Braille
* Pull out dictionary stuff to separate class/module
* Overreliance on instance varibles to allow access to infofmation throughout the class
* When using an enumerable to shovel into or add to an empty collection, there's probably a better enumerable to use


## Evaluation Rubric

The project will be assessed with the following guidelines:

* 4: Above expectations
* 3: Meets expectations
* 2: Below expectations
* 1: Well-below expectations

**Expectations:**

### 1. Ruby Syntax & Style

- [ ] Applies appropriate attribute encapsulation  
- [ ] Developer creates instance and local variables appropriately
- [x] Naming follows convention (is idiomatic)
- [x] Ruby methods used are logical and readable  
- [ ] Developer implements appropriate enumerable methods (#each is used sparingly)
- [x] Code is indented properly
- [x] Code does not exceed 80 characters per line
- [x] Each class has correctly-named files and corresponding test files in the proper directories

* 3: Meets expectations


### 2. Breaking Logic into Components

- [x] Code is effectively broken into methods & classes
- [x] Developer writes methods less than 8 lines
- [x] No more than 3 methods break the principle of SRP

* 3: Meets expectations

### 3. Test-Driven Development

- [x] Each method is tested  
- [x] Functionality is accurately covered
- [ ] Tests implement Ruby syntax & style   
- [x] Balances unit and integration tests
- [ ] Evidence of edge cases testing
- [ ] Test Coverage metrics are present (SimpleCov)

* 2: Below expectations


### 4. Version Control

- [X] Developer commits at a pace of at least 1 commit per hour
- [X] Developer implements branching and PRs
- [X] The final submitted version is merged into master


* 3: Meets expectations

### 5. Functionality

- [ ] Application meets all requirements (extension not req'd)

* 1: Well-below expectations
