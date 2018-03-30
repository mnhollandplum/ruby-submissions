# Max & Tim

Frontend Production: https://tyjoo26.github.io/quantified-self/ (view on mobile or with dev tools to resize)

Frontend Github: https://tyjoo26.github.io/quantified-self/

Backend Production: https://qs-1710-js.herokuapp.com/

Backend Github: https://github.com/Maxscores/quantified-self-js-backend

## Self Assessment Rubric

Please self assess with the rubric below. Provide additional information to explain why you feel your project displays the score you've given yourself in _each_ section.

### Specification Adherence

Application implements **all** functionality as defined, but some bugs or strange behavior where features intersect.

- Above Expectations, We've done quite a bit of UI testing to elminiate any bugs with the integrations.

### Documentation

Developer provides easy to navigate documentation showing how to setup and contribute to the application (for _both_ front-end and back-end repos).

- Meets Expectations

### HTML/UI

The team put some effort into styling, and the application is not confusing to use (including, but not limited to, user should **not** have to type anything into the URL to go between pages). HTML classes and IDs are kebab case.

- Above Expectations, We focused on building a mobile UI that looks nice and is compact for a small phone screen. The color scheme seems good and doesn't have AXE violations.

### Accessibility

Developer implements code to increase accessibility (your app should have 0 violations according to aXe).

- Meets Expectations

### JS syntax and Style

JavaScript code is logically divided into files. Developers can show examples of good coding practices and demonstrate OOP concepts, like DRY and separation of concerns. Developers pay attention to indentation and naming conventions. They also _consistently_ utilize ES5 or ES6 syntax and jQuery when working with events.

- Above Expectations, We use classes to organize our code and did a lot of refactoring to break out what each piece of a functionality is doing. We reused methods in a lot of places to make them more flexible.

### Git Workflow

The team uses master for production, uses feature branches for small groups of cards, and has a pull request for each feature with good context and conversation, following the template. Commit messages are in the present tense, and start with a capital letter. Developers that aren't on the team have commented on PRs.

- Meets Expectations

### Project Management

The team is using Pivotal Tracker to keep their project organized and to track progress. Team is documenting conclusions and timelines on relevant cards.

- Meets Expectations

### Communication

The team consistently reaches out to their Technical Lead for feedback on code quality and technical issues. The team responds to their Technical Lead in a timely manner. The team implements feedback from Technical Lead around pacing, refactors, workflow, etc.

- Meets Expectations. We didn't reach out much to our Tech lead, but that's because we felt good about our approach and were able to tackle technical issues between the two of us.

-----------

## Instructor Rubric

### Evaluated By: Amy

### Notes:
- You are awesome & build a really strong project 🎉
- Details included in each section of rubric
- Please feel free to reach out with any questions/follow up!

### Specification Adherence

Application implements **all** functionality as defined, but some bugs or strange behavior where features intersect.

- Meets Expectations
  - Looks awesome overall!
  - One small bug: When a food is added to a meal, there is an `Uncaught TypeError: Cannot read property push of undefined at mealService.appendFoodToMeal` coming up in the console. The food does not append to meal; only showing up in meal UI after a refresh.

### Documentation

Developer provides easy to navigate documentation showing how to setup and contribute to the application (for _both_ front-end and back-end repos).

- Meets Expectations
  - The explanation of all endpoints at your base back-end heroku app was awesome and so helpful!
  - Your instructions on the front-end repo to get the project running on a machine are perfect and the back-end has the same type of content but is harder to read since it's all inside that paragraph; I'd recommend pulling it out and following the pattern you used in the front-end docs!

### HTML/UI

The team put some effort into styling, and the application is not confusing to use (including, but not limited to, user should **not** have to type anything into the URL to go between pages). HTML classes and IDs are kebab case.

- Above Expectations
  - A little weird that there aren't initially tables for empty meals, but if you delete all foods out of a meal there is an empty table.

### Accessibility

Developer implements code to increase accessibility (your app should have 0 violations according to aXe).

- Meets Expectations
  - Four violations were found by aXe (3 - form elements should have a visible label, 1 - page must contain a level one heading)

### JS syntax and Style

JavaScript code is logically divided into files. Developers can show examples of good coding practices and demonstrate OOP concepts, like DRY and separation of concerns. Developers pay attention to indentation and naming conventions. They also _consistently_ utilize ES5 or ES6 syntax and jQuery when working with events.

- Above Expectations
  - Your style and syntax is beautiful! Nice architecture using the classes (on both front- and back-end)
  - I'd like to see a cleaner/more readable way to access the IDs from [these meals](https://github.com/Tyjoo26/quantified-self/blob/master/lib/meal-service.js#L47-49). Super small, just wanted to point it out to you 😉

### Git Workflow

The team uses master for production, uses feature branches for small groups of cards, and has a pull request for each feature with good context and conversation, following the template. Commit messages are in the present tense, and start with a capital letter. Developers that aren't on the team have commented on PRs.

- Meets Expectations
  - Great commit message content
  - `start with a capital letter` - done inconsistently

### Project Management

The team is using Pivotal Tracker to keep their project organized and to track progress. Team is documenting conclusions and timelines on relevant cards.

- Meets Expectations

### Communication

The team consistently reaches out to their Technical Lead for feedback on code quality and technical issues. The team responds to their Technical Lead in a timely manner. The team implements feedback from Technical Lead around pacing, refactors, workflow, etc.

- Meets Expectations
