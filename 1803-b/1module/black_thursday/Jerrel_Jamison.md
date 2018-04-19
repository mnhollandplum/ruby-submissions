Assessor: Brian

Repo: https://github.com/JerrelMitchell/black_thursday

Notes:

* Iteration 1 average items per merchant takes a very long time
* It would be easier to check if a key is changeable rather than if it is unchangeable
* Good use of Repository and FileLoader module
* Tight coupling makes testing much harder. Lots of methods go untested

## Evaluation Rubric

The project will be assessed with the following guidelines:

* 4: Above expectations
* 3: Meets expectations
* 2: Below expectations
* 1: Well-below expectations

**Expectations:**

### 1. Ruby Syntax & Style: 3

- [x] Applies appropriate attribute encapsulation  
- [x] Developer creates instance and local variables appropriately
- [x] Naming follows convention (is idiomatic)
- [x] Ruby methods used are logical and readable  
- [x] Developer implements best-choice enumerable methods
- [x] Code is indented properly
- [x] Code does not exceed 80 characters per line
- [x] A directory/file structure provides basic organization via lib/ and/or /test  
- [x] Rubocop shows five or fewer complaints

### 2. Breaking Logic into Components: 3

- [x] Code is effectively broken into methods & classes
- [x] Developer writes methods less than 7 lines
- [x] No more than 3 methods break the principle of SRP

### 3. Test-Driven Development: 2

- [ ] Each method is tested  
- [x] Functionality is accurately covered
- [x] Tests implement Ruby syntax & style   
- [ ] Balances unit and integration tests
- [x] Evidence of edge cases testing
- [x] Test Coverage metrics are present (SimpleCov)
- [x] A test RakeTask is implemented

### 4. Functionality: 2

- [ ] Application implements iterations 0, 1, 2, 3, and either 4 or 5

### 5. Version Control: 3

- [x] Developers commit at a pace of at least 1 commit per hour
- [x] Developers implements branching and PRs
- [x] Developer resolves Hound CI complaints on PRs
- [x] Commit history shows developers contributed evenly
- [x] The final submitted version is merged into master
