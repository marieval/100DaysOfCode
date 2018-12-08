# 100DaysOfCode #

The log of my #100DaysOfCode challenge.

## Log

### Day 01 - 11.8.2018 (Sat)
**Today´s Progress:** Continue working on my Product Landing Page project from FCC - it´s css (nav-bar, background, text-colors, paddings, margins,...)

**Thoughts:** For not repeating background used "fixed". 

Can´t manage to center the text in "Tips". :-(

**Link:** [Product Landing Page](https://codepen.io/mmajam/pen/PBBoeg?editors=1100)

### Day 02 - 12.8.2018 (Sun)
**Today´s Progress:** Continue working on my Product Landing Page project from FCC - responsivity (video, map), media queries. Finially finished it! ;-) 

**Thoughts:** ```<iframe>``` elements are not responsive, so we need to wrap them with an other element (```<div>```). (Web Design Blueprints - p.29)

**Link:** [Product Landing Page](https://codepen.io/mmajam/pen/PBBoeg?editors=1100)

### Day 03 - 13.8.2018 (Mon)
**Today´s Progress:** Began the project Technical Documentation (basic html, basic structure)

**Link:** [Technical Documentation Page](https://codepen.io/mmajam/full/VBRyma/)

### Day 04 - 14.8.2018 (Tue)
**Today´s Progress:** Went through materials to Gulp, NPM, SCSS. Done small responsive website using these. 

**Thoughts:** All those things are great!!!

### Day 05 - 15.8.2018 (Wed)
**Today´s Progress:** Continue with the project Technical Documentation Page (content, basic css)

**Link:** [Technical Documentation Page](https://codepen.io/mmajam/full/VBRyma/)

### Day 06 - 16.8.2018 (Thu)
**Today´s Progress:** Finished the project Technical Documentation Page (layout, media queries)

**Link:** [Technical Documentation Page](https://codepen.io/mmajam/full/VBRyma/)

### Day 07 - 17.8.2018 (Fri)
**Today´s Progress:** Read the documentation of _Bootstrap_ [(link)](https://getbootstrap.com/docs/4.1/getting-started/introduction/), which I want to use for my Personal Portfolio Page.

**Thoughts:** Flexbox-bugs: ```<button>``` and ```<fieldset>``` don´t work as flex-containers! (Solution: use ```<div>``` or other flex-supporting-element as immediate child of the ```<button>``` or ```<fieldset>``` (info: [Flexbugs](https://github.com/philipwalton/flexbugs#flexbug-9)).

### Day 08 - 18.8.2018 (Sat)
**Today´s Progress:** Continue reading the documentation of Bootstrap [(link)](https://getbootstrap.com/docs/4.1/getting-started/introduction/). Done part of the Basic JavaScript Challenges from FCC. 

### Day 09 - 19.8.2018 (Sun)
**Today´s Progress:** Finished _Basic JavaScript Challenges_ from FCC.

### Day 10 - 20.8.2018 (Mon)
**Today´s Progress:** Did _ES6-JS Challenges_ from FCC

**Thoughts:** 

*Destructuring assignment to assign variables from objects* challenge - didn´t understand at first, but helped me especially explanation from randelldawson [here](https://forum.freecodecamp.org/t/es6-use-destructuring-assignment-to-assign-variables-from-objects-question/206730/6):  ```const { length : len } = str; ```  can be understood as ```const {objectPropertyName : newDelcaredVariableName } = object; ```

*IIFE (Immediately Invoked Function Expression)* - nice explanation [here](https://stackoverflow.com/questions/8228281/what-is-the-function-construct-in-javascript)

*Destructuring assignment to pass an object as a function´s parameters* - the explanation of alhazen1 [here](https://forum.freecodecamp.org/t/use-destructuring-assignment-to-pass-an-object-as-a-functions-parameters/194816/14) was nice: ```const person = {name:"Bob", age:23, occupation:"Defender of the Universe"};

// destructing assignment in function arguments
function whoIsThisDude({name,occupation:job}){
  console.log(`Hi! I'm ${name}. I'm a ${job}`);
}
whoIsThisDude(person);

// destructuring assignment inside function
function whoIsThisDude2(someDude){
  const {name, occupation:job} = someDude;
  console.log(`Hi! I'm ${name}. I'm a ${job}`);
}
whoIsThisDude2(person);```

and also explanation of vytautas-pilk was great: ```function half({min, max}) return (min + max) / 2.0;``` is the same as writing ```const {min, max} = stats;
console.log((min + max) / 2.0);```

### Day 11 - 21.8.2018 (Tue)
**Today´s Progress:** Finished the section of _ES6 Challenges_ from FCC

**Thoughts:** 
*Use getters and setters to access to an object* challenge - for understanding helped explanation of JM-Mendez [here](https://forum.freecodecamp.org/t/es6-use-getters-and-setters-to-control-access-to-an-object/195489/11): 
```class SomeClass {
  constructor() {
      this.value = 'my initial value'
  }
  
  get value() {
      return this.value
  }
  
  set value(val) {
      this.value = val
   }
}
```
Then later you can use it like a regular object:

```console.log(SomeClass.value) // 'my initial value'
SomeClass.value = 'new value'
console.log(SomeClass.value)  // 'new value' 
```

If it was regular object, it would look like this:
```const SomeClass = {
   value: 'my initial value'
}

console.log(SomeClass.value) // 'my initial value'
SomeClass.value = 'new value'
console.log(SomeClass.value)  // 'new value'
```

### Day 12 - 22.8.2018 (Wed)
**Today´s Progress:** Started [CSS: The Complete Guide](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) course on Udemy. Had a meeting with an IT-professional to consult some techniques, practical uses,... - it boosted my eagerness for learning. 

### Day 13 - 23.8.2018 (Thu)
**Today´s Progress:** Learned about the real project workflow on my in-person course (processes with npm, gulp, sass...) and how to create a collapsible menu using only css ([basics](https://css-tricks.com/the-checkbox-hack/)).

### Day 14 - 24.8.2018 (Fri)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/)

### Day 15 - 25.8.2018 (Sat)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part Positioning.

**Thoughts:** 
*Percentages:* are related to "containing block" - it´s dependent on the position of our element (fixed: context is viewport / absolute: context is ancestor with position other than static (its content+padding) / relative: context is block-ancestor (only content)

### -- Day off - 26.8.2018 (Sun) --

### Day 16 - 27.8.2018 (Mon)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part Background Images&Images, Sizes&Units

### Day 17 - 28.8.2018 (Tue)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part JavaScript&CSS

### Day 18 - 29.8.2018 (Wed)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part _Responsive Web_

**Thoughts:** RWD - converting "hardware pixels" to "software pixels": ```<meta name="viewport" content="width=device-width, initial-scale=1.0">```

Conversion: 1 inch = 96px.

### Day 19 - 30.8.2018 (Thu)
**Today´s Progress:** Practiced working with Git on my in-person course.

### Day 20 - 31.8.2018 (Fri)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part Adding & Styling Forms.

**Thoughts:** *Outcome:* after border, not part of block-size. 

*Input, select:* They use default settings (e.g. font) of the browser. To change this and set it same as our "normally set" style, we must use ```font: inherit```. 

*:valid / :invalid pseudo-selectors:* can have other styling (e.g. ```.signup-form :invalid {....}```

*Disabled button:* Example styling: ```.button[disabled] {cursor: not-allowed; border: #a1a1a1; background: #ccc; color: #a1a1a1; }```

### Day 21 - 1.9.2018 (Sat)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part Text & Fonts. 

**Thoughts:** For importing a font-family to our project it´s better to use @import directly to our .css file. (```@import url("https://fonts.googleapis.com/css?family=Roboto");```

### Day 22 - 2.9.2018 (Sun)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part _Flexbox_. 

**Thoughts:** *Flex-basis:* if the ```flex-basis``` is set to ```auto``` and at the same moment the element´s ```width/height``` is set, the ```auto``` is used. If the ```flex-basis``` is set in ```px or %```, the ```width/height``` is overwritten by the ```flex-basis``` value.

### Day 23 - 3.9.2018 (Mon)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part _CSS Grid_. Started the Portfolio Page. 

**Thoughts:** *CSS Grid:* used for 2-D positioning xxx *Flexbox:* used for 1-D positioning. 

*Wrapper of the whole content:* for better positioning of all elements use wrapper with ```min-height: 100%; position: relative;```. 

### Day 24 - 4.9.2018 (Tue)
**Today´s Progress:** Worked on my Portfolio Website (decided NOT to use Bootstrap) - header, welcome part.

### Day 25 - 5.9.2018 (Wed)
**Today´s Progress:** Continue working on my Portfolio Website - parts About me, Portfolio, Contacts, Footer (just the drafts).  Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part CSS Transforms. 

**Thoughts:** Source for CSS-3D-Transforms: [https://3dtransforms.desandro.com/](https://3dtransforms.desandro.com/)

### Day 26 - 6.9.2018 (Thu)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part _Transitions, Animations_. Learned to work with _StyleLint_ and _Autoprefixer_ on my in-person course.

### Day 27 - 7.9.2018 (Fri)
**Today´s Progress:** Finished the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part _Sass_.


### Day 28 - 8.9.2018 (Sat)
**Today´s Progress:** Started the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/).

### Day 29 - 9.9.2018 (Sun) 
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with section _JS Basics_.

### Day 30 - 10.9.2018 (Mon) 
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Finished the section _JS Basics_.

**Thoughts:**  *JS-Expressions:* pieces of code which always produce a value.   *JS-Statements:* they perform an action (they don´t produce immediate results).

### Day 31 - 11.9.2018 (Tue)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Finished the section _JS Behind The Scenes_.

**Thoughts:** 

*Hoisting of functions:* - works only with *function declarations*:
```calculateAge(1965);
function calculateAge(year) {console.log(2018-year); }     // =====> It works!
```
*Function expressions* are NOT hoisted!! It causes a TypeError!!!
```retirement(1996);
var retirement = function(year) {console.log(65-(2018-year));}     // =====> Causes a TypeError.
```

*Scope and **this**:* the default object of *regular functions* is the *window object* (so *this* points to the *window object*). It´s true even when the regular function is written inside of a method!!!! **this** in a *method of an object* refers to the *object* itself.

### Day 32 - 12.9.2018 (Wed)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Finished the section _JS DOM Manipulation and Events_.

### Day 33 - 13.9.2018 (Thu)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Finished the section _Advanced JS: Objects and Functions_.

### Day 34 - 14.9.2018 (Fri)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - First part of The _Budget App_ Project.

**Thoughts:** 

*Event Listener on the Enter keypress:*  
```
document.addEventListener("keypress", function(event) {
      if (event.keyCode === 13 || event.which === 13) {
      ctrlAddItem();
      }
   })
```

### Day 35 - 15.9.2018 (Sat)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with The Budget App Project.

**Thoughts:** 

*Changing two classes (represented by "DOMstrings.....") in the DOM:* 
```
var fields = document.querySelectorAll(DOMstring.inputDescription + ", " + DOMstrings.inputValue);
// This returns a List. To be able to use an Array-method on the List, we need to use the call method:
var fieldsArray = Array.prototype.slice.call(fields);
```

### Day 36 - 16.9.2018 (Sun)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with The Budget App Project.

**Thoughts:** 

*DOM Manipulation examples and explanation:* [blog.garstasio](https://blog.garstasio.com/you-dont-need-jquery/)

*Splice x slice:* ```splice``` - used to remove elements (from what index, how many) x ```slice``` - used to create a copy

*Event bubbling, event delegation:* used in 2 cases: 1. When we have an element with lots of child elements that we are interested in; 2. When we want an event handler attached to an element that is not yet in the DOM when our page is loaded.

### Day 37 - 17.9.2018 (Mon)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Finished The _Budget App_ Project section.

**Thoughts:** 

*Map method:* returns something and stores it in a variable. *ForEach method:* only loops through the array and does something with it (but doesn´t return anything)

### Day 38 - 18.9.2018 (Tue)
**Today´s Progress:** Revised the _Budget App_ Project in detail. 

### Day 39 - 19.9.2018 (Wed)
**Today´s Progress:** Added responsivity to my previous projects at FCC: [Tribute page](https://codepen.io/mmajam/full/xJPeXq/), [Build a Survey Form](https://codepen.io/mmajam/full/QBxyBQ/), [Product Landing Page](https://codepen.io/mmajam/full/PBBoeg/), [Technical Documentation Page](https://codepen.io/mmajam/full/VBRyma/). 

**Thoughts:** I see that I moved forward a lot in one month - when I looked at those project, I can see my not-so-good-solutions, I would do these better now. First I thought that I will re-do them, but then I decided not to do so now, but to continue with other things instead - future projects will be better (as I hope). :-D

### Day 40 - 20.9.2018 (Thu)
**Today´s Progress:** Went back to the [Portfolio Website projects](https://codepen.io/mmajam/full/BOyNdN/) (until Day25 I did draft of parts About me, Portfolio, Contacts, Footer) and did small changes regarding things I learned in the meantime. Learned about the Keep-Aspect-Ratio for photogallery (resources: [Aspect Ratio Boxes - CSS-Tricks](https://css-tricks.com/aspect-ratio-boxes/), [Keith Grant´s explanation](https://keithjgrant.com/posts/2017/03/aspect-ratios/) and [MadeMyDay.de examples and explanation](http://www.mademyday.de/css-height-equals-width-with-pure-css.html).

### Day 41 - 21.9.2018 (Fri)
**Today´s Progress:** Finished my [Portfolio Website project](https://codepen.io/mmajam/full/BOyNdN/). 

**Thoughts:** Struggled with implementing of the toggle-menu for mobile-version (used the solution from [codeburst](https://codeburst.io/how-to-make-a-collapsible-menu-using-only-css-a1cd805b1390)). 

### Day 42 - 22.9.2018 (Sat)
**Today´s Progress:** Fixed some bugs on mobile-version of my [Portfolio Website project](https://codepen.io/mmajam/full/BOyNdN/). Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Part of the _ES6/ES2015_ section. 

**Thoughts:** 

Variables declared with ```var``` are *function-scoped*. Variables declared with ```let``` or ```const``` are *block-scoped*.

*Template literals:* to use them, we must use backticks (not single/double quotes)!

### Day 43 - 23.9.2018 (Sun)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - ES6/ES2015 section (arrow functions, destructuring, spread operator, rest parameters, maps.

### Day 44 - 24.9.2018 (Mon)
**Today´s Progress:** Finished the section _ES6/ES2015_ of the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - classes + subclasses. Did the final challenge (trees/streets).

### Day 45 - 25.9.2018 (Tue)
**Today´s Progress:** Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - section _Asynchronous JavaScript_ (Event loop, Promises, Async/await). 

### Day 46 - 26.9.2018 (Wed)
**Today´s Progress:** Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - finished section _Asynchronous JavaScript_ (Fetch), started section _Modern JavaScript_ (node.js, webpack - installing and configuring (webpack, webpack-cli, webpack-dev-server, html-webpack-plugin). 

**Thoughts:** I find the shown processes similar to those which we used in my in-person course with Gulp (at least for this moment; I look forward for learning more and for working with it!

### Day 47 - 27.9.2018 (Thu)
**Today´s Progress:**  Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - installing and configuring _Babel_. Started the final project "Forkify" (planning using MVC architecture, modules).

### Day 48 - 28.9.2018 (Fri)
**Today´s Progress:**  Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with "Forkify" project (start working with API, installing Axios)

### Day 49 - 29.9.2018 (Sat)
**Today´s Progress:** Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with "Forkify" project (working on the Search model, Search controller)

### Day 50 - 30.9.2018 (Sun)
**Today´s Progress:** Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with _"Forkify" project_ (part Search view, loading spinner)

### Day 51 - 1.10.2018 (Mon)
**Today´s Progress:**  Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with _"Forkify" project_ (part Recipe model, Recipe controller)

**Thoughts:** I came across the book _Maintainable JavaScript_ by Nicholas C. Zakas several days ago and I am reading it in free moments during the day. The concepts there are exactly those which used Maximilian in his projects (the CSS course on Udemy, which I took recently). I really like it! (I wish I had more time for coding and learning!)

### Day 52 - 2.10.2018 (Tue)
**Today´s Progress:**  Continue with the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with _"Forkify" project_ (changing the amount of servings and ingredients)

**Thoughts:** I look forward to my own programming! But I decided to finish the JS-course first (hopefully tomorrow) and than I´ll continue with the projects of FCC. 

### Day 53 - 3.10.2018 (Wed)
**Today´s Progress:**  Finished the course on  [JavaScript](https://www.udemy.com/the-complete-javascript-course/). Did the challenges on _Regular Expressions_ at FCC. 

**Thoughts:** _LocalStorage API:_ stores only strings (To store data: ```localStorage.setItem("likes", JSON.strigify(this.likes));```, to get back data: ```const storage = JSON.parse(localStorage.getItem("likes"));``` 

### Day 54 - 4.10.2018 (Thu)
**Today´s Progress:** Did the challenges on _Debugging_ at FCC, began the challenges on _Basic Data Structures_ at FCC (processing of arrays).

**Thoughts:** _Greedy matching (default):_ on string "titanic" matches "titani" using ```/t[a-z]*i/```. 
_Lazy matching:_ on string "titanic" matches "ti" using ```/t[a-z]*?i/```

### Day 55 - 5.10.2018 (Fri)
**Today´s Progress:** Did the challenges on _Object Oriented JavaScript_ at FCC.

**Thoughts:** If we set a prototype of an object, we must set also its constructor (otherwise is undefined!) - 
```
Bird.prototype = {
  constructor: Bird,
  numLegs: 4,
  eat: function() {
    console.log("nom nom")
  }
};
```

### Day 56 - 6.10.2018 (Sat)
**Today´s Progress:** Did the challenges on _Functional Programming in JavaScript_ at FCC.

**Thoughts:** When we don´t know all the arguments at once:
```
function impartial(x,y,z) {
   return x + y + z;
}

var partialFn = impartial.bind(this, 1, 2);

partialFn(10);    => 13
```

### Day 57 - 7.10.2018 (Sun)
**Today´s Progress:** I want to get the overview of the connection between front-end, back-end, databases, and so on. So I bought the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). Since the first parts are just repeating, I went through these quickly: today I did the sections _How the Internet Works, History of Web, HTML, CSS_. 

**Thoughts:** Some resources: https://unsplash.com/ (free images), http://paletton.com/ (color palette), https://css-tricks.com/ (overview of css properties and values), https://specificity.keegan.st/ (specificity calculator), https://robots.thoughtbot.com/transitions-and-transforms (transitions and transforms overview), https://philipwalton.github.io/solved-by-flexbox/ and www.flexboxpatterns.com/ (flexbox).

Resources for the course: https://zero-to-mastery.github.io/resources/, and one other: https://github.com/zero-to-mastery/complete-web-developer-manual

### Day 58 - 8.10.2018 (Mon)
**Today´s Progress:** I went through the parts _Bootstrap, Career of Web Dev., JavaScript_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). 

**Thoughts:** Resources: https://mailchimp.com/ (email marketing and similar), animate.css (animating of elements), templates of websites (www.creative-tim.com, https://mdbootstrap.com/freebies/ (!!!), http://www.mashup-template.com/templates.html, https://startbootstrap.com/template-categories/all/).

### Day 59 - 9.10.2018 (Tue)
**Today´s Progress:** I went through the parts _DOM Manipulation, Advanced JS_ (part) of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). 

**Thoughts:** _Conversion of ES6_ to ES5 (online): https://babeljs.io/repl/

_Currying:_ 
```
const multiply = (a,b) => a * b;
const curriedMultiply = (a) => (b) => a*b;
const multiplyBy5 = curriedMultiply(5);
```

_Compose:_
```
const compose = (f,g) => (a) => f(g(a));
const sum = (num) => num + 1;
compose(sum,sum)(5);     =====> 7
```

### Day 60 - 10.10.2018 (Wed)
**Today´s Progress:** I continued with sections _Advanced JS_ (second part - reduce, classes, ES7, ES8, Asynchronous JS), Command Line, Dev.-Environment of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/).

**Thoughts:** Some links: [You don´t know JS](https://github.com/getify/You-Dont-Know-JS), [javascript.info](http://javascript.info/), [JavaScript: The Core, 2nd Ed.](http://dmitrysoshnikov.com/ecmascript/javascript-the-core-2nd-edition/), [How To Think Like A Programmer](https://medium.freecodecamp.org/how-to-think-like-a-programmer-lessons-in-problem-solving-d1d8bf1de7d2), [ES Modules: A cartoon deep dive](https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/).

### Day 61 - 11.10.2018 (Thu)
**Today´s Progress:** I continued with the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/) - sections _Git and GitHub, A day of a Web Developer, NPM_. 

**Thoughts:** Some useful links: Commands for Cmd for Windows (https://www.thomas-krenn.com/en/wiki/Cmd_commands_under_Windows). Some useful _npm packages:_ live-server, lodash. 

Check _A developer´s morning routine_ (in the section A day of Web-Dev.)!!!! Good tips!!!

### Day 62 - 12.10.2018 (Fri)
**Today´s Progress:** I started the section _React.js_ in the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). Began with the React application "Robofriends".

**Thoughts:** I´m totally excited about React! :D

### Day 63 - 13.10.2018 (Sat)
**Today´s Progress:** I continued with the section _React.js_ in the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). Began the part of Redux and applied some of the principles to "RoboFriends" app. 

### Day 64 - 14.10.2018 (Sun)
**Today´s Progress:** I finished the section _React.js + Redux_ in the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). 

**Thoughts:** I got lost in the Redux part. :( I´ll go back later to this part (or perhaps read/watch more about Redux from other sources too and then come back). 

### Day 65 - 15.10.2018 (Mon)
**Today´s Progress:** I did the section _HTTP / JSON / AJAX / Asynchronous JS_ in the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). 

**Thoughts:** I like Promises more than Async-Await. 

### Day 66 - 16.10.2018 (Tue)
**Today´s Progress:** I did the sections _Backend Basics and APIs_ in the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). 

**Thoughts:** Sources for various APIs: https://apilist.fun/ 

### Day 67 - 17.10.2018 (Wed)
**Today´s Progress:** I started the main project (code-along) _Face Recognition App_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/) - setting the parts using React.

**Thoughts:** I like React. ;-) Some other useful resources: _tilt.js_ (```npm install --save react-tilt```), _particles.js_ (```npm install react-particles-js```). 

### Day 68 - 18.10.2018 (Thu)
**Today´s Progress:** I finished the front-end part (coded along) of the main project _Face Recognition App_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/).

**Thoughts:** Interesting API (recognition of faces, colors, things,...): https://clarifai.com/

### Day 69 - 19.10.2018 (Fri)
**Today´s Progress:** I started the part _Node.js & Express.js_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/).

### Day 70 - 20.10.2018 (Sat)
**Today´s Progress:** Today I coudn´t do anything on my PC, so instead I started reading the book _The Road To Learn React_ by Robin Wieruch. I find it great in connection to the topic of the course Complete Web Dev...

### -- Day off - 21.10.2018 (Sun) --

### Day 71 - 22.10.2018 (Mon)
**Today´s Progress:** I finished the part _Node.js & Express.js_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/). Challenge Santa´s node helper ([puzzle](https://adventofcode.com/2015/day/1)). 

**Thoughts:** Nice [article](https://medium.freecodecamp.org/how-to-think-like-a-programmer-lessons-in-problem-solving-d1d8bf1de7d2) about _problem solving._ 

### Day 72 - 23.10.2018 (Tue)
**Today´s Progress:** I started the back-end (server) part of the main project _Face Recognition App_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/).

**Thoughts:** _Postman:_ (www.getpostman.com) - great for testing my server before I connect it to the front-end. 

_Body-parser:_ used for accessing the body of the request (```npm install body-parser```).

_Timer:_ For testing how long did some task take: ```console.time("myTask");``` on the beginning, and then ```console.timeEnd("myTask");``` on the end.

### Day 73 - 24.10.2018 (Wed)
**Today´s Progress:** I did the section _Databases_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/).

**Thoughts:** I already learned about databases before (CodeCademy and two one-day in-person courses), but now (with this course) it goes sooo clearly together with the other parts as a puzzle! I really missed this junction!! 

_Training the database-commands:_ https://www.khanacademy.org/computing/computer-programming/sql

### Day 74 - 25.10.2018 (Thu)
**Today´s Progress:** I went through the section about _Production & Deployment_ of the course [Complete Web Developer in 2018: Zero To Mastery](https://www.udemy.com/the-complete-web-developer-in-2018/).

**Thoughts:** The course was great! I really like the way, how all the pieces click together! Now I look forward to my own code! My plan is to use plain HTML/CSS/JavaScript first, and after some time to study React in more detail and use this. 

Some resources: [Environment Variables in windows](http://www.dowdandassociates.com/blog/content/howto-set-an-environment-variable-in-windows-command-line-and-registry/), [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)...

 ### Day 75 - 26.10.2018 (Fri)
**Today´s Progress:** I made a wireframe for a small app for showing only selected videos suitable for kids. Made the basic structure.

**Thoughts:** When starting from scratch, I´m really very unsure and forgot so much things which I already knew before! I´m totally demotivated. :-( 

### -- Day off - 27.10.2018 (Sat) --

 ### Day 76 - 28.10.2018 (Sun)
**Today´s Progress:** I started re-building of the main page of the uHost (project from the CSS-course, which I did earlier) just according the result html-page. 

**Thoughts:** The start was not easy, but as I went further, it was much better. ;-)

### Day 77 - 29.10.2018 (Mon)
**Today´s Progress:** I continued with re-building of the main page of the uHost (project from the CSS-course, which I did earlier) just according the result html-page. Got stuck at mobile-version. :-/

### Day 78 - 30.10.2018 (Tue)
**Today´s Progress:** I continued with re-building of the uHost website - the Package-page. 

### Day 79 - 31.10.2018 (Wed)
**Today´s Progress:** I re-builded the Customers-page of the uHost website. 

### Day 80 - 1.11.2018 (Thu)
**Today´s Progress:** I continued with re-building of the uHost website. I rewatched some parts of the CSS-course. 

### Day 81 - 2.11.2018 (Fri)
**Today´s Progress:** I continued with re-building of the uHost website. I repeated some parts of the CSS-course. 

### Day 82 - 3.11.2018 (Sat)
**Today´s Progress:** I went again through the positioning- and background-topics of the CSS-Course on Udemy. 

**Thoughts:** If an img is inside of an _inline element_: it´s 100%-width refers to the 100%-width of the image itself. I an img is inside of an _inline-block element_: it´s 100%-width-size refers to the size of the surrounding element. 

### Day 83 - 4.11.2018 (Sun)
**Today´s Progress:** I went again through the Sizes & Dimensions-topics of the CSS-Course on Udemy. 

### Day 84 - 5.11.2018 (Mon)
**Today´s Progress:** I started again from the beginning (just with html-template) with re-creating the main page of the uHost (from the CSS-course).

**Thoughts:** It´s much better now after revising some parts of the course! I achieve the output using different features in the css than they did in the course, but I´m happy about having solved it! However, I have to solve some minor issues and improve responsivity.

### Day 85 - 6.11.2018 (Tue)
**Today´s Progress:** I continued with re-creating the customer-page and plan-page of the uHost (from the CSS-course).

**Thoughts:** I´m excited, that I make progress with the site really much better now! Last week the stuff I wrote didn´t work and I felt deprived, but now after refreshing the material from the course it´s much more easy!!! I like this CSS-course because Max mentions there various dependencies and under which conditions a feature doesn´t work. It´s really useful!

### Day 86 - 7.11.2018 (Wed)
**Today´s Progress:** I continued with re-creating the uHost-project (from the CSS-course).

### Day 87 - 8.11.2018 (Thu)
**Today´s Progress:** I continued with re-creating the uHost-project (from the CSS-course) - changed the units to responsive ones (rem, %), did the Start-Hosting-page.

**Thoughts:** I didn´t succeed with designing the hamburger-menu using css. :-( I will come to it tomorrow again. 

### Day 88 - 9.11.2018 (Fri)
**Today´s Progress:** I continued with re-creating the uHost-project (from the CSS-course) - styled the modal, backdrop, added eventListeners  to the buttons on the main-page. 

### -- Day off - 10.11.2018 (Sat) --

### Day 89 - 11.11.2018 (Sun)
**Today´s Progress:** I continued with re-creating the uHost-project (from the CSS-course) - added mobile-nav-menu, improving responsivity.

### Day 90 - 12.11.2018 (Mon)
**Today´s Progress:** I continued with re-creating the uHost-project (from the CSS-course) - eventListeners, added responsivity.

### Day 91 - 13.11.2018 (Tue)
**Today´s Progress:** I wanted to learn more about transforms and animations, so I started the course which I bought already more than month ago at Udemy - [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/).

**Thoughts:** __Clip-path:__ for clipping background or image to different shapes (using polygon() ). __Centering:__ Using ```position: absolute; top: 50%; left: 50%;``` (% is relative to the positioned ancestor) in combination with ```transform: translate(-50%, -50%);``` (% is relative to the element itself).

### Day 92 - 14.11.2018 (Wed)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - using ```::after``` pseudoclass, using _animation_, _transition_, _transform (translate, scale)_.

**Thoughts:** I don´t do the code-along, but instead I watch the whole video on a topic first and after finishing it I try to re-do it (so that I must try to remember and recall the things from the video). I find this approach much better! 

### Day 93 - 15.11.2018 (Thu)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - section How CSS Works: A Look Behind The Scenes. 

**Thoughts:** 
_percentage of lengths:_ (height/padding/margin/... expressed in %) - the reference is always the parent-element´s _width_!!!

_em for fonts:_ the reference is the parent-element font-size. _em for lengths:_ the reference is the current element´s computed font-size!

_Inheritance:_ Inherited are the _computed values_ in px (not the declared values - e.g. in %)!

### Day 94 - 16.11.2018 (Fri)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - started with Sass / SCSS, auto-compiling and auto-reload of the page. Created _fluid-grid_. Began using _Emmet_. Learned about _utility-classes_ and started using them in the project.

**Thoughts:** _auto-compiling:_ used node-sass together with nodemon, for _auto-reload:_ used live-server.

### Day 95 - 17.11.2018 (Sat)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - created another section (with images reacting on hover).

**Thoughts:** _Line around an image:_ using _outline_: ```outline: 1rem solid rgb(0,0,0,);``` on element:hover; and ```outline-offset: 1rem;``` on element itself. 

_Icons:_ [linea.io](linea.io) - for downloading and free to use.

_Skew the background-image:_ use ```transform: skew(-7deg);``` on the section; and ```transform: skew(7deg);``` on all the section´s direct children (using ```>```). 

### Day 96 - 18.11.2018 (Sun)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - beginning creating another section (with cards flipping on hover).

**Thoughts:** When I make all element´s children to ```position: absolute;```, the element itself collapses (as with floats) => We must set the same height to element itself and to the child.

_linear-gradient:_ works with ```background-image:....``` (not ```background-color```!!)

_perspective:_ when higher numbers (as 150rem) - looks more natural as flipping. For mozzilla needed the prefix! (```-moz-perspective:...```)

### Day 97 - 19.11.2018 (Mon)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - finished the section from yesterday, made the section Stories. Used ```background-blend-mode, box-decoration-break, shape-outside, filter, object-fit...```

**Thoughts:** 

_Background-blend-mode: screen;_ - used for adjusting the colors/hues of an image (adjusting the color to a specific color). (Not supported in some browsers!)

_Box-decoration-break: clone;_ - used for maintaining of the padding even after splitting of the row.

_Flexible images in responsive web sites:_ must have always specified _width_!

_Shape-outside: circle(50% at 50% 50%);_ - surrounding text is in the shape of the circle (the element must be floated and must have specified width and height!)

_Video in the background:_ for fitting: ```height: 100%; width: 100%; object-fit: cover;```

### Day 98 - 20.11.2018 (Tue)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - made the form-section. Used solid-color gradients, general ```~``` and adjacent ```+``` sibling selectors, ```:invalid, :focus, :checked```.

**Thoughts:**

_Radiobuttons:_ To be considered as the same group, the input must have the same ```name="..."``` attribute. Radiobuttons can´t be styled in CSS - we must build our own instead (and the original make ```display: none;```.

_Forms:_ We must use ```button``` (not the ```a```) - because the form understands the button as the submit. 

_Button:_ By default have a border. They have ```focus``` - we can remove this by adding ```outline: none;``` to the ```button:focus``` (but there must be some other way how it´s clear that it´s active!).

### Day 99 - 21.11.2018 (Wed)
**Today´s Progress:** I continue with the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) - Finished the section Natours-project: Using advanced CSS and Sass. Learned how to use _checkbox-hack_ and _popup-window_. Using ```radial-gradient, :target, display: table-cell, column-count, hyphens```.

**Thoughts:**

_cubic-bezier helping-tools:_ cubic-bezier.com, easings.net

### Day 100 - 22.11.2018 (Thu)
**Today´s Progress:** I finished the Natours project in the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/) (last sections: _Responsive Web.-Design_ (esp. _responsive images_), _Browser-support, npm_ and _automation._ Used ```backdrop-filter, ::selection,...```

**Thoughts:** _To influence only touch-devices + mobile-phones:_ ```
@media only screen and (max-width: 56.25em),
       only screen and (hover: none) {........}```


### **********************************************************************
### ******************* !!! WOWWW !!!  It´s Day 100!!! *******************

**Let´s sum up:** During those 100 days I did some coding or I learned some new stuff (approximately 3 hours a day - sometimes just 1-2 hours, sometimes 5-6 hours, as much as was possible). I missed just 4 days (after days 15, 70, 75, 88 - but of course I didn´t count those skipped days, so it took me 4-days longer than planned.)

**I feel much more confident in:** _CSS, Sass (SCSS), Responsive websites, JavaScript, Command-line, Git, npm, connection of the page with a database,..._

**My plans:** 
// - Create a website (using BEM, Sass, Resp. design,...). -
// - Recreate my projects at FCC. -
// - Participate in the monthly-challenges of Zero-To-Mastery. -
// - Contribute to non-profit (probably through Zero-To-Mastery). -
// - Push my projects to GitHub (or elsewhere). -
// - Learn React in more detail. -
// - Learn Node.js in more detail. -

### ********************************************************************** 

### Day 101 - 23.11.2018 (Fri)
**Today´s Progress:** I started a new project Quotes For Every Day (functionally similar to the one at FCC, which I did more than 1 year ago).  I decided to use Sass+BEM, so I did the basic setup for the project. I used the command line for creating the project folders/files. 

**Thoughts:** For creating a new file in Git Bash (in Windows): ```> base.scss```.

### Day 102 - 24.11.2018 (Sat)
**Today´s Progress:** I continued with the project Quotes For Every Day - finished the layout, added responsivity. 

**Thoughts:** I had problem animating the button (releasing the pressed button) - it helped to make it an ```a``` element (instead of ```button``` element). 
Again, I have a problem with positioning the footer - so that it sticks to the bottom of the viewport if there is not enough content, but when making the viewport smaller (and so the content can´t fit to the viewport anymore), I want the footer to be completely at the bottom.  I know that I can solve it using flexbox, but I wanted to try some other solution. 

### Day 103 - 25.11.2018 (Sun)
**Today´s Progress:** I finished the project _Quotes For Every Day_ (except JS which I want to do later). I searched and tried several solutions for the footer-issue, but I wasn´t really satisfied with any of them (I wanted to have it really responsive - without fixed height of the footer), so I finally decided to use flexbox for it. ;-)

### Day 104 - 26.11.2018 (Mon)
**Today´s Progress:** I did some improvements in the project _Quotes For Every Day_. I started a new project (similar to the one which I did more than 1 year ago as a FCC project) - Local Weather App. I did the setup and basic layout of the project. I want some refresher about the details regarding Flexbox, so I started the Flexbox-section in the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/). 

### Day 105 - 27.11.2018 (Tue)
**Today´s Progress:** I continued with the Flexbox-section in the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/). Learned about _CSS variables_, using _SVG icons_ and using ```fill: currentElement;``` to change the color to the same as the parent, and about changing the color/font-weight/... of the _placeholder text_ (using ```&::-webkit-input-placeholder { ..... };```

### Day 106 - 28.11.2018 (Wed)
**Today´s Progress:** I finished the Flexbox-section (Trillo project) in the course [Advanced CSS and Sass](https://www.udemy.com/advanced-css-and-sass/). Learned how to put _SVG into CSS_ and how to change its color using ```mask-image```, how to do an _infinite animation_, _multicolumn list_,... and added responsivity to the whole project using @media queries.

**Thoughts:** To find all the _npm packages which are installed globally:_ ``` npm list -g --depth 0```

### Day 107 - 29.11.2018 (Thu)
**Today´s Progress:** I revised the new features of JavaScript - I went through my notes and some parts of [The Complete JavaScript Course](https://www.udemy.com/the-complete-javascript-course/), and then I did the section A Quick Refresher: JavaScript in the [Node.js: the Complete Guide course](https://www.udemy.com/nodejs-the-complete-guide/).

**Thoughts:** I understood better the _arrow functions_, _spread_ and _rest operator_, _destructuring_ and _asynchronous JS (promises)_.

### Day 108 - 30.11.2018 (Fri)
**Today´s Progress:** I added the JavaScript functionality to the project _Quotes For Every Day_ - display a random quote from API (used _async JS - fetch_) after pressing the new-button,  _tweet the quote_ after pressing the tweet-button.

**Thoughts:** I´m excited that I was able to do it quite quickly and it works as intended! I like the ES6 syntax! 

### -- Day off - 1.12.2018 (Sat) --

### Day 109 - 2.12.2018 (Sun)
**Today´s Progress:** I did the _Node.js Crash Course_ at the [The Complete JavaScript Course](https://www.udemy.com/the-complete-javascript-course/) - I learned more about _Node.js_, _server creating_, _routing_, and creating _HTML using templates_. 

### Day 110 - 3.12.2018 (Mon)
**Today´s Progress:** I learned about the _Basics of Node.js_ at the course Node.js: The Complete Guide. (In more detail: _Starting a server, routing, redirecting,..._

### Day 111 - 4.12.2018 (Tue)
**Today´s Progress:** I did the challenge of the _Node.js_ course, Section Basics of Node.js - I started my own server and processed two scenarios/routings. I learned about _reading and writing files_ in an app using Node.js.

### Day 112 - 5.12.2018 (Wed)
**Today´s Progress:** I learned using the _Express.js_ in the course Node.js: _adding middleware, routing, creating and serving html files, serving files statically._ I did the challenge No2 - create an app with two routes and serving a file statically. 


### Day 113 - 6.12.2018 (Thu)
**Today´s Progress:** I learned about _adding dynamic content_ and using _templating engines: EJS, Pug, Handlebars_ (with EJS I worked more). Learned how to _loop in ejs_, how to use _partials/include_ in ejs and using _conditional adding of a class to an element_.

**Today´s Progress:** I got stuck with the challenge - I need more practice... I wish I had more time to learn and practice during the day! :-(

### Day 114 - 7.12.2018 (Fri)
**Today´s Progress:** I did the challenge from yesterday - I feel I understand more of the topic now! I learned about using _MVC_ (_modules-views-controls_). Also, I learned how to _load data from a file_ and _save data to a file_. 

### Day 115 - 8.12.2018 (Sat)
**Today´s Progress:** I finished the section _Dynamic Routes & Advanced Models_ of the _Node.js_ course. Learned how to use _dynamic parameters_ (using _:name_ -  ```router.get("/products/:productId");```, extracting it using _req.params_ - ```const prodId = req.params.productId;``` ). Read [The Node.js Handbook](https://nodehandbook.com/) for better understanding. 
