# Module 4 Intermission Assignments

To prepare for Module 4 we'd like for you to complete the following before 9 AM Monday (the first day of M4).

## 1. Reflection on Learning Experiences

Complete this [exercise](https://gist.github.com/case-eee/c70bef26c5f71286d70fe6b379342b95) to reflect on your learning experience thus far here at Turing.

## 2. Debugging JavaScript

You've all had some experience with JavaScript thus far. We'd like to prepare you for M4 by diving deep into how we debug with JavaScript (since we're going to be diving deeper into writing JavaScript). Work through this [lesson](https://github.com/turingschool/backend-curriculum-site/blob/gh-pages/module4/lessons/debugging_javascript.markdown) (you may already know most of this information, but we encourage you to use this as a refresher).

## 3. Quantified Self Head Start

Quantified self will be your project week 1. You'll be building a calorie tracker. We wanted you to use your time over intermission week to get a head start.

### Getting started

Clone down the [Quantified Self Starter Kit](https://github.com/turingschool-examples/quantified-self-os). And take a quick gander at the readme.

### Requirements

You'll be building out the "Manage Foods" portion of the site.

![(Manage Foods)](http://backend.turing.io/module4/projects/quantified-self-resource-management.png)

- When I visit foods.html, I can enter a name and calorie amount, and create a new food by clicking "Add Food"
- When I click "Add Food", and all fields are filled, the food will appear at the top of the table below
- When I click "Add Food" and the Name field is blank, a food will not be created, but I will see an error message below the Name field: "Please enter a food name"
- When I click "Add Food" and the Calories field is blank, a food will not be created, but I will see an error message below the Calories field: "Please enter a calorie amount"
- When I attempt to create a food, any error messages should be cleared to make room for new error messages
- When I successfully create a food, text fields should be cleared
- When I click the "Delete" icon next to a food, it will be removed from the list.
- I can filter the table of foods by typing into the "Filter by Name" box above the table. Show only foods that match the text typed. Filter the list on each key press. Should be case insensitive.

### Next Steps

You are not required to TDD these features. We will have a lesson on testing in JS. If you want to try testing before the lesson, a couple tests have been written, and you can experiment with writing your own tests.

The next step is persisting your changes after a refresh, but we'll have a lesson to help you with that, so no need to start.

## Optional Work

### Introduction to JavaScript Topics Reading

**Read** the following selections from [Speaking JavaScript](http://speakingjs.com/es5/) & [Eloquent JavaScript](http://eloquentjavascript.net//):

* [Chapter 3 (Speaking): The Nature of JavaScript](http://speakingjs.com/es5/ch03.html)
* [Chapter 3 (Eloquent): Functions](http://eloquentjavascript.net//03_functions.html)
* [Chapter 5 (Eloquent): Higher Order Functions](http://eloquentjavascript.net//05_higher_order.html)
* [Chapter 6: (Eloquent) The Secret Life of Objects](http://eloquentjavascript.net//06_object.html)
* [Chapter 17: Objects and Inheritance (Speaking JavaScript)](http://speakingjs.com/es5/ch17.html)

Then finish it all with [JavaScript Garden](http://bonsaiden.github.io/JavaScript-Garden/).

### Exercisms

* Complete *5* of your own completed [exercism.io][exer] exercises in JavaScript
* Review solutions by 5 other people for the same exercises, and compare your solution to theirs

If you have trouble with the exercism UI, you can find other versions of exercisms you submitted at this link:http://exercism.io/tracks/javascript/exercises

[exer]: http://exercism.io/


## Extensions

Then select and complete *one* of the sections below.

### NodeSchool.io

Work through _at least two_ of the following courses:

* [javascripting](https://github.com/sethvincent/javascripting)
* [lololodash](https://github.com/mdunisch/lololodash)
* [ExpressWorks](https://github.com/azat-co/expressworks)

### jQuery Fundamentals

Work through Bocoup's [jQuery Fundamentals](http://jqfundamentals.com).

### CSS Fundamentals

* Work Through This [Introductory Static Site](https://github.com/turingschool-examples/introductory-static-site)
* Work Through These [CSS Layout Challenges](https://github.com/turingschool-examples/css-layout-challenges)

### Scaling Up as a Developer

As we move into the final module of Turing, we're getting fairly competent at producing useful software. But rather than being the end of the journey, this really just opens the door to even deeper rabbit holes—now that I can get something done, what other ways might there be to accomplish the same thing? The same observable effects could be accomplished via numerous different combinations of code. What are the underlying opinions and ideas embodied by each choice?

**Read**: [Sandi Metz' Rules For Developers][sandi] (10 minutes)
* Which of Sandi's rules do you feel like might be the hardest to follow—why?

**Listen**: [Shop Talk: Tom Dale](http://shoptalkshow.com/episodes/147-tom-dale/) (1.5 hours)
* Do you agree with Tom? What parts of his argument are compelling? What parts do you disagree with?

Here are are a few more "philosophical" materials to hopefully help us contemplate this side of the issue:

* [Execution in the Kingdom of Nouns by Steve Yegge](http://steve-yegge.blogspot.ca/2006/03/execution-in-kingdom-of-nouns.html) - You've been doing object-oriented programming for almost 6 months now. What are some of the limitations imposed by this approach? How do Ruby and/or Javascript capture the benefits of OO while avoiding some of the pitfalls?
* [Simplicity Matters by Rich Hickey](https://www.youtube.com/watch?v=rI8tNMsozo0) - As we move into working on larger and more sophisticated systems, some of the approaches that have worked on smaller projects may no longer be so effective. What does Rich Hickey say about the common pitfalls of Ruby and Rails applications?
* [The Birth and Death of Javascript by Gary Bernhardt](https://www.destroyallsoftware.com/talks/the-birth-and-death-of-javascript) - This talk takes a tongue-in-cheek tone, but the concepts discussed are very topical. What does Bernhardt suggest about the role of Javascript in shaping the modern web?
* [Real Software Engineering by Glenn Vanderburg](https://www.youtube.com/watch?v=NP9AIUT9nos) - What does Glenn have to say about Software Engineering as a discipline? How does Software Engineering differ fundamentally from other Engineering disciplines? What can we as Software Engineers take away from other disciplines?

[sandi]: http://robots.thoughtbot.com/sandi-metz-rules-for-developers
[tbruby]: https://github.com/thoughtbot/guides/tree/master/style/ruby
[airbnbjs]: https://github.com/airbnb/javascript
[hound]: http://robots.thoughtbot.com/introducing-hound
[tomdale]: http://shoptalkshow.com/episodes/147-tom-dale/
[speakingjs]: http://speakingjs.com/es5/
[allonge]: https://leanpub.com/javascript-allonge/read
