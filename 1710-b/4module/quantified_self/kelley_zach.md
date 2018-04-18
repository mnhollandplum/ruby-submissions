# Kelley & Zach

Frontend Production: https://kelleyjenkins.github.io/quantified-self/

Frontend Github:https://github.com/kelleyjenkins/quantified-self

Backend Production http://salty-escarpment-41029.herokuapp.com/api/meals

Backend Github:  https://github.com/zacharylandes/quantified-api

## Self Assessment Rubric

Please self assess with the rubric below. Provide additional information to explain why you feel your project displays the score you've given yourself in _each_ section.

### Specification Adherence

Application implements **all** functionality as defined, but some bugs or strange behavior where features intersect.

- Above Expectations
- Meets Expectations
- Below Expectations

### Documentation

Developer provides easy to navigate documentation showing how to setup and contribute to the application (for _both_ front-end and back-end repos).


- Meets Expectations


### HTML/UI

The team put some effort into styling, and the application is not confusing to use (including, but not limited to, user should **not** have to type anything into the URL to go between pages). HTML classes and IDs are kebab case.


- Meets Expectations


### Accessibility

Developer implements code to increase accessibility (your app should have 0 violations according to aXe).

- Below Expectations

### JS syntax and Style

JavaScript code is logically divided into files. Developers can show examples of good coding practices and demonstrate OOP concepts, like DRY and separation of concerns. Developers pay attention to indentation and naming conventions. They also _consistently_ utilize ES5 or ES6 syntax and jQuery when working with events.

- Above Expectations


### Git Workflow

The team uses master for production, uses feature branches for small groups of cards, and has a pull request for each feature with good context and conversation, following the template. Commit messages are in the present tense, and start with a capital letter. Developers that aren't on the team have commented on PRs.

- Meets Expectations

### Project Management

The team is using Pivotal Tracker to keep their project organized and to track progress. Team is documenting conclusions and timelines on relevant cards.

- Above Expectations


### Communication

The team consistently reaches out to their Technical Lead for feedback on code quality and technical issues. The team responds to their Technical Lead in a timely manner. The team implements feedback from Technical Lead around pacing, refactors, workflow, etc.


- Meets Expectations


-----------

## Instructor Rubric

### Evaluated By: Amy

### Notes:
- Awesome work overall!
- A few notes below, within the categories they apply to.

### Specification Adherence

Application implements **all** functionality as defined, but some bugs or strange behavior where features intersect.

- Above Expectations 🦄
  - I did not find any bugs or strange behavior

### Documentation

Developer provides easy to navigate documentation showing how to setup and contribute to the application (for _both_ front-end and back-end repos).

- Meets-ish Expectations
  - The front-end docs are GREAT! It would be great to see the back-end repo as detailed in terms of setting up on a machine, as well as the endpoints listed on your base heroku app.

### HTML/UI

The team put some effort into styling, and the application is not confusing to use (including, but not limited to, user should **not** have to type anything into the URL to go between pages). HTML classes and IDs are kebab case.

- Meets Expectations 🎉

### Accessibility

Developer implements code to increase accessibility (your app should have 0 violations according to aXe).

- Meets Expectations
  - Four violations were found by aXe (3 - form elements should have a visible label, 1 - heading levels should only increase by 1)

### JS syntax and Style

JavaScript code is logically divided into files. Developers can show examples of good coding practices and demonstrate OOP concepts, like DRY and separation of concerns. Developers pay attention to indentation and naming conventions. They also _consistently_ utilize ES5 or ES6 syntax and jQuery when working with events.

- Meets Expectations 🎉
  - You should still be handling the response from a post rather than `console.log`-ing [here](https://github.com/kelleyjenkins/quantified-self/blob/master/lib/meals/meal_service.js#L16)
  - Both ES5 and ES6 functions are used within the [same file](https://github.com/kelleyjenkins/quantified-self/blob/master/lib/meals/meal_service.js#L28)
  - Make sure you are consistent with your use of white space. In [food-view.js](https://github.com/kelleyjenkins/quantified-self/blob/master/lib/foods/food_view.js) in particular, sometimes you pad functions with one line, sometimes two. Should never see a line of white space directly below function declaration.

### Git Workflow

The team uses master for production, uses feature branches for small groups of cards, and has a pull request for each feature with good context and conversation, following the template. Commit messages are in the present tense, and start with a capital letter. Developers that aren't on the team have commented on PRs.

- Meets Expectations 🎉

### Project Management

The team is using Pivotal Tracker to keep their project organized and to track progress. Team is documenting conclusions and timelines on relevant cards.

- Above Expectations 🦄

### Communication

The team consistently reaches out to their Technical Lead for feedback on code quality and technical issues. The team responds to their Technical Lead in a timely manner. The team implements feedback from Technical Lead around pacing, refactors, workflow, etc.

- Meets Expectations 🎉
