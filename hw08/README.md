# HW08 - Teachable interface
Go ahead into `lessons/10-learning/teachable-machine-app` and run `npm install`. Then go into `app.js` and make sure that `heartHands/heartHandsApp` is the source of the `setup` function. Now `npm run watch` and navigate to `localhost:3000`. Hopefully, when you make a heart with your hands, you'll see a flurry of pink hearts. What I'd like you to do in this assignment is to think about how Teachable Machine can be used as an interface.

### Description
Simply put, make something with Teachable Machine. Check out this https://experiments.withgoogle.com/interplay-mode/view/

Here, we basically have something not significantly more complicated than what we already made in class. The UI is a lot prettier, and it's playing with a nice video, but we already saw how to make something like this just the other day. What else can you imagine that might make use of some of what we saw how to do in class?

- A drawing canvas, where the things that you draw emerge from the page when they are recognized
- An adventure game, where you make hand signs to determine what action you take
- Something like Berghain Trainer https://berghaintrainer.com/
- A "conversation" with an animated character that can recognize certain words
- An instagram filter (would combine nicely with the head tracker from two lessons ago)
- A sonifier that analyzes your face and tries to play music that matches your mood

### Requirements
You must use an original model, not one of the ones that we used in class. You may either upload the model to Google, or include it as part of your repo. You don't have to use p5, you don't even have to do any drawing at all. The important part is that you use an original model in your own code. Other than that, you have a lot of freedom on this assignment.
