---
title: "Steven Coy Web Developer Projects"
layout: "single"
toc: true
toc_sticky: true
share: false
author_profile: true
author: Steven Coy
---

<link rel="stylesheet" href="assets/css/custom.css">

## Web Developer Projects

I am a self-taught web developer who believes in and enjoys project-based learning. I am looking for a role as a full-stack web developer to further develop the skills I have learned and demonstrated in the projects below.

## GridSquid (2022) - Custom Grid Creator

<a target="_blank" rel="noopener noreferrer" href="https://gridsquid.ragmats.com/"><img style="padding: 10px; border: 0px; filter: brightness(2.0);" src="https://gridsquid.pythonanywhere.com/static/gridsquid/img/gs_logo_long.svg" alt="GridSquid Logo" width="100%"/></a>

[GridSquid](https://gridsquid.ragmats.com/){:target="\_blank"}{:rel="noopener noreferrer"} is an educational single-page application coded in JavaScript and Python (Django) that lets users make custom grids of images with associated sounds and captions. Originally, the idea was to help toddler-aged kids learn the faces and names of all their relatives, but it developed into a much broader application that is useful in homeschool, language studies, and other general education.

I learned so much from this project, namely how to set up a CRUD-capable backend with user authentication, custom APIs, and integration of open-source libraries, as well as a good understanding of JavaScript concepts like promises, async/await, destructuring, the spread operator, array methods, and the Fetch API (to name a few). I also became more familiar with Git and the deployment process.

**Features Include:**

- A front-end written in JavaScript, HTML, and responsive CSS ([Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/){:target="\_blank"}{:rel="noopener noreferrer"} in part, the rest hand-coded).
- Implementation as a single-page application (SPA) with history states for better user navigation.
- A fully CRUD-capable backend written in [Django](https://www.djangoproject.com/){:target="\_blank"}{:rel="noopener noreferrer"}/Python with many custom-written APIs.
- User authentication and password resets via email.
- Guest accounts (w/ same user access) that get deleted every 30 days, checked daily via automated task and custom command.
- User accounts for creating and storing sets of custom grids storing uploaded images, audio, and/or text captions.
- Cropping functionality for user-submitted images using the [Cropper.js](https://fengyuanchen.github.io/cropperjs/){:target="\_blank"}{:rel="noopener noreferrer"} library.
- Backend image compression using [Pillow](https://python-pillow.org/){:target="\_blank"}{:rel="noopener noreferrer"}.
- User-uploaded audio files converted to mp3 using [Pydub](http://pydub.com/){:target="\_blank"}{:rel="noopener noreferrer"}.
- File/mime type validation of image and audio files via [Python Magic](https://github.com/ahupp/python-magic){:target="\_blank"}{:rel="noopener noreferrer"}.
- The option to record and save audio using [Microphone Recorder to Mp3](https://github.com/closeio/mic-recorder-to-mp3){:target="\_blank"}{:rel="noopener noreferrer"}.
- A memory game that can be played on any grid complete with sound effects and CSS "card flip" animations.
- Auto-generated quizzes for any grid that can be taken with audio only, text only, or both.
- A collection page called "MyGrids" where all user grids can be viewed and organized into albums.
- Deployed on [PythonAnywhere](https://pythonanywhere.com/){:target="\_blank"}{:rel="noopener noreferrer"}.

**View this project in action:** [gridsquid.ragmats.com](https://gridsquid.ragmats.com/){:target="\_blank"}{:rel="noopener noreferrer"}

**Video demo:**

<iframe width="560" height="315" src="https://www.youtube.com/embed/qhYY0cqv-ig" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Oopsie (2021) - Anti-Fertility Calculator

<a target="_blank" rel="noopener noreferrer" href="https://oopsie.ragmats.com/"><img style="padding: 10px; border: 0px;" src="https://oopsie.pythonanywhere.com/static/images/oopsie_logo.svg" alt="Oopsie Logo" width="100%"/></a>

[Oopsie](https://oopsie.ragmats.com/){:target="\_blank"}{:rel="noopener noreferrer"} is a web-based anti-fertility application that celebrates the wonderful, life-altering event of not getting pregnant. I made this tool because I love my kids and two are enough for me 😊

This project was built with Flask/Python and JavaScript. I learned how to set up a backend and render templates with calculations based on user input and data from a database. I also learned how to work with classes for cleaner code, Python's datetime module, time zone localization, and persistent user sessions.

**Features Include:**

- A main page that gives the user their "oopsie" chance as a percentage based on method inputs and researched data.
- Responsive design using CSS media queries.
- Complex algorithms for determining oopsie chance based on date, time, and user inputs.
- A "permanent" session for a persistent user experience.
- Time zone localization.
- A calendar view that displays the current, last, and next week of oopsie chances.
- A JavaScript simulation/mini-game.
- Deployed on [PythonAnywhere](https://pythonanywhere.com/){:target="\_blank"}{:rel="noopener noreferrer"} (previously Heroku).

- **View this project in action:** [oopsie.ragmats.com](https://oopsie.ragmats.com/){:target="\_blank"}{:rel="noopener noreferrer"}

**Video demo:**

<iframe width="560" height="315" src="https://www.youtube.com/embed/flOwjttW78A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
