# Project ID: f79fd17b-a16c-4cbe-91fc-c2dc91a58a61

# Project Quizz

This application was made as part of a university course on Device-Agnostic Design.
Using the application is simple.
Just choose a topic and try to answer the randomly selected Question.

## Key challenges

1. I chose to use only riverpod for state management. Unfortunately the version used by the test system is not the latest version (>=2.0.0) but still version 1.
    Some functionality was missing regarding AsyncValue and FutureProvider.
2. Working around the course requirements that where most likely just for the automated tests was a challange. Not because it was hard but it was counter to what I believe is bad design. For example the AppBar provides a back button already, so why do we need to create a new one everywhere?
3. Responsive Design in general was a challenge, I opted to just copy all the code for the smaller layout with all the code duplication problems that entails.

## Key learning moments

Nothing really. I mean, I learned a lot about Flutter and the inner workings of an old version of riverpod, but in terms of design, I think the lack of freedom really thwarted my learning potential here.

## URL

This project is temporarily published at [quizz.basgoeze.com](http://quizz.basgoeze.com).
