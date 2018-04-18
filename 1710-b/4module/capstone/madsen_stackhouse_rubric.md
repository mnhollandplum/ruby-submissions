# Tyler Madsen & Max Stackhouse

Production Links:
[App on Expo](https://expo.io/@maxscores/dominion-with-friends)
[Backend](https://dominion-backend.herokuapp.com)
Repo Links:
[Front-End](https://github.com/Maxscores/dominion-app)
[Back-End](https://github.com/tylermarshal/dominion_backend)

-----------

## Self Assessment Rubric

Please self assess with the rubric below. Provide additional information to explain why you feel your project displays the score you've given yourself in _each_ section.

### 1. Project Planning & Management

Developer uses an iteration map to plan project scope, breaks down broad features into granular tasks, and exercises good Git workflow (e.g., feature branches, descriptive commits, incremental PRs)

- Above Expectations

Over 60 branches between both Repos, we kicked ass with [Pivotal](https://www.pivotaltracker.com/n/projects/2159424). Also, the last week we switched focus from trying to build the complete game and focused on building out the auxiliary features to make this a true MVP.

### 2. Completion & Pace

Developer plans stories ahead of sprint and makes some scope adjustments along the way. Developer communicates adjustments to Technical Lead as soon as possible (if necessary).

- Above Expectations

This was a beast of a project. We even started 1 week early and needed to make some concessions on the gameplay in order to have a functional app with the features we felt were 'core' to the user experience.

### 3. Implementation Quality

Project exhibits tested (where applicable), maintainable, and well-organized code. Developer can speak to architecture and implementation decisions and best practices.

- Meets Expectations

Not gonna try to spin this, but we have some UGLY code in places on the Front End. This is expected since this was our first time building something with React-Native (or React) and it wasn't an easy project premise. That being said, we did spend some time refactoring out some of the game mechanics in order to expose them for testing. We have unit tests for each of the cards in the game as well as with the game mechanics.

On the backend, things are beautiful. We heavily utilize ActiveRecord callbacks to setup games with a single HTTP request and serve our data using heavily customized serializers.

### 4. Application of Techniques

Developer implements four new techniques or patterns.

- Above Expectations

React-Native, Expo, iOS development, Game Development, local storage, push notifications.

### 5. Documentation

Developer provides easy to navigate documentation showing how to setup and contribute to the application.

- Meets Expectations

We got Docs....

### 6. Accessibility

Developer implements code to increase accessibility.

- Below Expectations

Don't even know where to start with a phone app, but we did do some user testing with friends to get a general sense of what our weak spots were in the UX. We knew how to do things since we built it, but giving it to someone for the first time was a bit of a shock for them. It wasn't the most intuitive experience at the beginning and it is getting better.
-----------

## Instructor Rubric

## Instructor Name:

## Notes:

### 1. Project Planning & Management

Developer uses an iteration map to plan project scope, breaks down broad features into granular tasks, and exercises good Git workflow (e.g., feature branches, descriptive commits, incremental PRs)

- Above Expectations
- Meets Expectations
- Below Expectations

### 2. Completion & Pace

Developer plans stories ahead of sprint and makes some scope adjustments along the way. Developer communicates adjustments to Technical Lead as soon as possible (if necessary).

- Above Expectations
- Meets Expectations
- Below Expectations

### 3. Implementation Quality

Project exhibits tested (where applicable), maintainable, and well-organized code. Developer can speak to architecture and implementation decisions and best practices.

- Above Expectations
- Meets Expectations
- Below Expectations

### 4. Application of Techniques

Developer implements four new techniques or patterns.

- Above Expectations
- Meets Expectations
- Below Expectations

### 5. Documentation

Developer provides easy to navigate documentation showing how to setup and contribute to the application.

- Above Expectations
- Meets Expectations
- Below Expectations

### 6. Accessibility

Developer implements code to increase accessibility.

- Above Expectations
- Meets Expectations
- Below Expectations
