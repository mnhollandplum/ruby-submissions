Assessor: Brian

Repo: https://github.com/KeeganCorrigan/enigma

Notes:

* No need to assert_equal and refute_equal
* don't call the encrypt method in the setup
* Used assert instead of assert_equal
* Great job breaking functionality out of Enigma class and into Encryptor, Decryptor, and Cracker
* Instead of making cracked_key being an instance variable, you could return it from the crack method with the cracked text in the form of a hash
* Try and use as few IVars as possible. If it can be easily calculated, it doesn't need to be an Ivar

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
- [x] Naming follows convention (is idiomatic)
- [x] Ruby methods used are logical and readable  
- [ ] Developer implements appropriate enumerable methods (#each is used only when necessary)
- [x] Code is indented properly
- [x] Code does not exceed 80 characters per line
- [x] Each class has correctly-named files and corresponding test files in the proper directories
- [x] Code has been linted and corrected properly.


### 2. Breaking Logic into Components: 3

- [x] Code is effectively broken into methods & classes
- [x] Developer writes methods less than 8 lines
- [x] Methods do not break the principle of SRP


### 3. Test-Driven Development: 3

- [x] Each method is tested  
- [x] Functionality is accurately covered
- [x] Tests implement Ruby syntax & style   
- [x] Balances unit and integration tests
- [x] Evidence of edge cases testing
- [x] Test Coverage metrics are present (SimpleCov)
- [x] Test Coverage metrics exceed 95%

- [ ] 4: Above expectations
- [ ] 3: Meets expectations
- [ ] 2: Below expectations
- [ ] 1: Well-below expectations

### 4. Git Workflow: 3

- [x] Repository demonstrates that each member of team has contributed fairly equally.
- [x] Developers commit at a rate of approximately one commit every 30 minutes.
- [x] Repository shows the use of branches.
- [x] Developers use a pull request workflow.
- [x] Developers resolve HoundCI complaints in their pull requests.

### 5. Functionality: 3

- [x] Application meets all requirements (extensions not required for a 3)
