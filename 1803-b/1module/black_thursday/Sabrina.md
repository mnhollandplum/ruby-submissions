Assessor: Dione Wilson

Repo: https://github.com/shebesabrina/black_thursday

Notes:

  * Nice work with memoization
  * To get your rake file to work gem install reek and gem install cane (then run `rake sanitation:all`)
  * Create a branch for each iteration and more frequent commits
  * Implement rake for tests
  

## Evaluation Rubric

The project will be assessed with the following guidelines:

* 4: Above expectations
* 3: Meets expectations
* 2: Below expectations
* 1: Well-below expectations

**Expectations:**

### 1. Ruby Syntax & Style

* 3: Meets expectations

- [x] Applies appropriate attribute encapsulation  
- [x] Developer creates instance and local variables appropriately
- [x] Naming follows convention (is idiomatic)
- [x] Ruby methods used are logical and readable  
- [x] Developer implements best-choice enumerable methods
- [x] Code is indented properly
- [x] Code does not exceed 80 characters per line
- [x] A directory/file structure provides basic organization via lib/ and/or /test  
- [ ] Rubocop shows five or fewer complaints

### 2. Breaking Logic into Components

* 3: Meets expectations

- [x] Code is effectively broken into methods & classes
- [x] Developer writes methods less than 7 lines
- [x] No more than 3 methods break the principle of SRP

### 3. Test-Driven Development

* 2: Below expectations

- [x] Each method is tested  
- [x] Functionality is accurately covered
- [x] Tests implement Ruby syntax & style   
- [x] Balances unit and integration tests
- [ ] Evidence of edge cases testing
- [ ] Test Coverage metrics are present (SimpleCov)
- [ ] A test RakeTask is implemented

### 4. Functionality

- [ ] Application implements iterations 0, 1, 2, 3, and either 4 or 5

### 5. Version Control

* 2: Below expectations

- [ ] Developers commit at a pace of at least 1 commit per hour
- [x] Developers implements branching and PRs
- [ ] Developer resolves Hound CI complaints on PRs
- [ ] Commit history shows developers contributed evenly
- [x] The final submitted version is merged into master
