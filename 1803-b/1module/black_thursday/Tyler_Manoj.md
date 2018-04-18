Assessor: Brian 

Repo: https://github.com/manojpanta/black_thursday

Notes:

* Some tests for searching are expecting to not find the thing
* Tight coupling is making things harder to test
* Missing some unit tests for attributes. For example, Merchant unit tests
* 


## Evaluation Rubric

The project will be assessed with the following guidelines:

* 4: Above expectations
* 3: Meets expectations
* 2: Below expectations
* 1: Well-below expectations

**Expectations:**

### 1. Ruby Syntax & Style: 2

- [ ] Applies appropriate attribute encapsulation  
- [ ] Developer creates instance and local variables appropriately
- [ ] Naming follows convention (is idiomatic)
- [x] Ruby methods used are logical and readable  
- [x] Developer implements best-choice enumerable methods
- [x] Code is indented properly
- [x] Code does not exceed 80 characters per line
- [x] A directory/file structure provides basic organization via lib/ and/or /test  
- [x] Rubocop shows five or fewer complaints

### 2. Breaking Logic into Components: 2

- [ ] Code is effectively broken into methods & classes
- [x] Developer writes methods less than 7 lines
- [x] No more than 3 methods break the principle of SRP

### 3. Test-Driven Development: 2

- [ ] Each method is tested  
- [ ] Functionality is accurately covered
- [x] Tests implement Ruby syntax & style   
- [x] Balances unit and integration tests
- [x] Evidence of edge cases testing
- [x] Test Coverage metrics are present (SimpleCov)
- [x] A test RakeTask is implemented

### 4. Functionality: 3

- [x] Application implements iterations 0, 1, 2, 3, and either 4 or 5

### 5. Version Control: 2

- [ ] Developers commit at a pace of at least 1 commit per hour
- [x] Developers implements branching and PRs
- [x] Developer resolves Hound CI complaints on PRs
- [ ] Commit history shows developers contributed evenly
- [x] The final submitted version is merged into master
