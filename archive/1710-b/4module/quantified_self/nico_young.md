# Nico & Young

Frontend Production: https://nico24687.github.io/quantified-self/foods.html

Frontend Github: https://github.com/nico24687/quantified-self

Backend Production: https://express-qs.herokuapp.com/

Backend Github: https://github.com/nico24687/express-qs

## Self Assessment Rubric

Please self assess with the rubric below. Provide additional information to explain why you feel your project displays the score you've given yourself in _each_ section.

### Specification Adherence

Application implements **all** functionality as defined, but some bugs or strange behavior where features intersect.

- Above Expectations
**- Meets Expectations**
- Below Expectations

### Documentation

Developer provides easy to navigate documentation showing how to setup and contribute to the application (for _both_ front-end and back-end repos).

**Above Expectations**
- Meets Expectations
- Below Expectations

### HTML/UI

The team put some effort into styling, and the application is not confusing to use (including, but not limited to, user should **not** have to type anything into the URL to go between pages). HTML classes and IDs are kebab case.

- Above Expectations
- **Meets Expectations**
- Below Expectations

### Accessibility

Developer implements code to increase accessibility (your app should have 0 violations according to aXe).

- **Meets Expectations**
- Below Expectations

### JS syntax and Style

JavaScript code is logically divided into files. Developers can show examples of good coding practices and demonstrate OOP concepts, like DRY and separation of concerns. Developers pay attention to indentation and naming conventions. They also _consistently_ utilize ES5 or ES6 syntax and jQuery when working with events.

- Above Expectations
- **Meets Expectations**
- Below Expectations

### Git Workflow

The team uses master for production, uses feature branches for small groups of cards, and has a pull request for each feature with good context and conversation, following the template. Commit messages are in the present tense, and start with a capital letter. Developers that aren't on the team have commented on PRs.

- Above Expectations
- **Meets Expectations**
- Below Expectations

### Project Management

The team is using Pivotal Tracker to keep their project organized and to track progress. Team is documenting conclusions and timelines on relevant cards.

- Above Expectations
- **Meets Expectations**
- Below Expectations

### Communication

The team consistently reaches out to their Technical Lead for feedback on code quality and technical issues. The team responds to their Technical Lead in a timely manner. The team implements feedback from Technical Lead around pacing, refactors, workflow, etc.

- Above Expectations
- **Meets Expectations**
- Below Expectations

-----------

## Instructor Rubric

### Evaluated By: Amy

### Specification Adherence

Application implements **all** functionality as defined, but some bugs or strange behavior where features intersect.

- Meets Expectations 🎉

### Documentation

Developer provides easy to navigate documentation showing how to setup and contribute to the application (for _both_ front-end and back-end repos).

- Above Expectations 💯
  - Beautiful! It is so user friendly, if I were a contributor I would be so grateful for how clear and thorough this is.

### HTML/UI

The team put some effort into styling, and the application is not confusing to use (including, but not limited to, user should **not** have to type anything into the URL to go between pages). HTML classes and IDs are kebab case.

- Meets Expectations 🎉
  - One issue - I couldn't find a button or way to navigate from the diary to the foods page.

### Accessibility

Developer implements code to increase accessibility (your app should have 0 violations according to aXe).

- Meets Expectations 🎉

### JS syntax and Style

JavaScript code is logically divided into files. Developers can show examples of good coding practices and demonstrate OOP concepts, like DRY and separation of concerns. Developers pay attention to indentation and naming conventions. They also _consistently_ utilize ES5 or ES6 syntax and jQuery when working with events.

- Meets Expectations
  - Overall, solid. Consistent style and syntax makes this easy to read through and follow. I liked the decisions you made in terms of pulling pieces out into helper files.
  - [This chaining of `.then((meals))`](https://github.com/nico24687/quantified-self/blob/master/lib/index.js#L45) looks cluttered and isn't necessary - that meals value in all of them is the same - all of the functions called within those should be done so in one single `.then()`.

### Git Workflow

The team uses master for production, uses feature branches for small groups of cards, and has a pull request for each feature with good context and conversation, following the template. Commit messages are in the present tense, and start with a capital letter. Developers that aren't on the team have commented on PRs.

- Meets Expectations 🎉
  - Commit messages were a bit inconsistent (tense and capitalization)

### Project Management

The team is using Pivotal Tracker to keep their project organized and to track progress. Team is documenting conclusions and timelines on relevant cards.

- Meets Expectations 🎉

### Communication

The team consistently reaches out to their Technical Lead for feedback on code quality and technical issues. The team responds to their Technical Lead in a timely manner. The team implements feedback from Technical Lead around pacing, refactors, workflow, etc.

- Meets Expectations 🎉
