![](https://javascript30.com/images/JS3-social-share.png)

# JavaScript30

Starter Files + Completed solutions for the JavaScript 30 Day Challenge.

Sign up for course at [https://JavaScript30.com](https://JavaScript30.com)
Course at: https://courses.wesbos.com/account
Course repo: https://github.com/wesbos/JavaScript30

## Items Learned
#### 01 Drum Kit
* you can grab an audio element (document.querySelectory), then play it using a method call
  - `const audio = document.querySelector("audio");`
  - `audio.play();`
* transition end event "transitionend"
* in an event listener function, 'this' is the element that the event was called on
  - note, if using an arrow function, the behavior seems different (check this)
* sidenote, similarly animations have an animation end event as well

#### 02 JS and CSS Clock
* practice with css transition, transform, transform-origin, transform-timing-function
* can easily access an elements style property, using javascript object property access
  - e.g. minutesHand.style.transform = "rotate(90deg)";

#### 03 CSS Variables
* pretty powerful. works similar to vars in sass or less. but those are done at compile time.
  - css var, work realtime dynamically. when you change the value of a variable, all the elements get updated realtime.
* NOTE: document.querySelectorAll returns a NodeList, not an array. At a glance, it looks like an array (ie, in the console),
but notice, NodeList does not have many of the functions / methods an Array has.
  - it does have some, but less.
  - sometimes, developers convert NodeList to an array, to get access to those other useful prototype functions
* dataset - is a useful attribute / property of an element, which is an object of all the data-* attributes of an element
* scoping / cascading does apply to variables
  - e.g. if you at a lower level, assign a different value to a variable, the value will be applied just in that scope
    + `<h2 style="--base: #BADA55;">Header Text</2>`

#### 04 Array Cardio Day 1
* practice with array methods (map, reduce, sort, filter)

#### 05 Flex Panel Gallery
* flex looks very powerful, and straightfoward to use, once you know how
   - this chapter doesn't do much teaching about flex
   - it explains some capabilities, and tells you what to type
* Check out his full tutorial, that should be a good starting point (and more comprehensive)
  - "What The Flexbox"   (Wes Bos Flex tutorial) 

#### 06 Type Ahead
* Fetch API - javascript / browsers now have a built in ajax like functionality, 'fetch'
  - returns a promise 
