Assessor: Mike

Repo:https://github.com/emmiehayes/night_writer/tree/kim

Notes:
* Application only converts from english to braille
* Runner file only handles two filenames
* opportunities to refactor - pulling blocks out to separate methods
* the pattern of #each putting something into a collector local variable and then returning it is a sign a better enumerable could be used
* if a method sets something to a local variable, you can probably pull that out to another method

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
- [ ] Naming follows convention (is idiomatic)
- [x] Ruby methods used are logical and readable  
- [ ] Developer implements appropriate enumerable methods (#each is used sparingly)
- [x] Code is indented properly
- [x] Code does not exceed 80 characters per line
- [x] Each class has correctly-named files and corresponding test files in the proper directories

* 3: Meets expectations


### 2. Breaking Logic into Components

- [x] Code is effectively broken into methods & classes
- [x] Developer writes methods less than 8 lines
- [ ] No more than 3 methods break the principle of SRP

* 3: Meets expectations

### 3. Test-Driven Development

- [x] Each method is tested  
- [x] Functionality is accurately covered
- [x] Tests implement Ruby syntax & style   
- [x] Balances unit and integration tests
- [ ] Evidence of edge cases testing
- [ ] Test Coverage metrics are present (SimpleCov)

* 3: Meets expectations

### 4. Version Control

- [x] Developer commits at a pace of at least 1 commit per hour
- [x] Developer implements branching and PRs
- [x] The final submitted version is merged into master

* 3: Meets expectations
### 5. Functionality

- [ ] Application meets all requirements (extension not req'd)

* 2: Below expectations