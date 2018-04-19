# Lee Chow

Production Links:
- https://my-hep.herokuapp.com/api/v1
- There is no production link for the client (I used Expo with React Native)

Repo Links:
- https://github.com/leepuppychow/myHEP_server
- https://github.com/leepuppychow/myHEP
- https://github.com/leepuppychow/image_segmentation_API

-----------

## Self Assessment Rubric

Please self assess with the rubric below. Provide additional information to explain why you feel your project displays the score you've given yourself in _each_ section.

### 1. Project Planning & Management

Developer uses an iteration map to plan project scope, breaks down broad features into granular tasks, and exercises good Git workflow (e.g., feature branches, descriptive commits, incremental PRs)

- Meets Expectations. I feel that I used Waffle.io well to track progress. The workflow for the Rails server was well setup and I had TravisCI and auto-deploy to Heroku. The workflow for the client-side app and the Flask API was not as good, as I did not have tests for these.

### 2. Completion & Pace

Developer plans stories ahead of sprint and makes some scope adjustments along the way. Developer communicates adjustments to Technical Lead as soon as possible (if necessary).

- Below Expectations. I intended to get more done with the image processing, but honestly I did not work as hard as I could have on this project. I feel like I kept my technical lead up to date with my progress, but could have pushed myself harder.

### 3. Implementation Quality

Project exhibits tested (where applicable), maintainable, and well-organized code. Developer can speak to architecture and implementation decisions and best practices.

- Meets Expectations. I'm pretty proud of the Rails codebase as well as most of the React Native codebase (except for the lack of testing). I think the structure and design of my application is solid (using JWT, Flask API as a image segmentation microservice, and posting to Amazon S3 bucket), but I did not accomplish as much as I wanted.

### 4. Application of Techniques

Developer implements four new techniques or patterns.

- Meets Expectations. React Native, OpenCV, Flask, Google Vision API, Amazon S3, knock gem for JWT.

### 5. Documentation

Developer provides easy to navigate documentation showing how to setup and contribute to the application.

- Meets Expectations. The README for the Rails server is pretty accurate, although I need to modify the schema picture. The README for the React Native repo is decent, but I did not include many details on language versions. Setup instructions could be more detailed.

### 6. Accessibility

Developer implements code to increase accessibility.

- Below Expectations. Unfortunately, I did not focus on this last step, sorry for that! I ended up diving into the computer vision/image processing algorithms and got lost with that.

-----------

## Instructor Rubric

## Instructor Name: Holt

### 1. Project Planning & Management

Developer uses an iteration map to plan project scope, breaks down broad features into granular tasks, and exercises good Git workflow (e.g., feature branches, descriptive commits, incremental PRs)

- Meets Expectations

### 2. Completion & Pace

Developer plans stories ahead of sprint and makes some scope adjustments along the way. Developer communicates adjustments to Technical Lead as soon as possible (if necessary).

- Meets Expectations

### 3. Implementation Quality

Project exhibits tested (where applicable), maintainable, and well-organized code. Developer can speak to architecture and implementation decisions and best practices.

- Meets Expectations

### 4. Application of Techniques

Developer implements four new techniques or patterns.

- Above Expectations

### 5. Documentation

Developer provides easy to navigate documentation showing how to setup and contribute to the application.

- Meets Expectations

### 6. Accessibility

Developer implements code to increase accessibility.

- Below Expectations
