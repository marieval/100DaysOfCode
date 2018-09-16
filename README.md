# 100DaysOfCode

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
**Today´s Progress:** Read the documentation of Bootstrap [(link)](https://getbootstrap.com/docs/4.1/getting-started/introduction/), which I want to use for my Personal Portfolio Page.

**Thoughts:** Flexbox-bugs: ```<button>``` and ```<fieldset>``` don´t work as flex-containers! (Solution: use ```<div>``` or other flex-supporting-element as immediate child of the ```<button>``` or ```<fieldset>``` (info: [Flexbugs](https://github.com/philipwalton/flexbugs#flexbug-9)).

### Day 08 - 18.8.2018 (Sat)
**Today´s Progress:** Continue reading the documentation of Bootstrap [(link)](https://getbootstrap.com/docs/4.1/getting-started/introduction/). Done part of the Basic JavaScript Challenges from FCC. 

### Day 09 - 19.8.2018 (Sun)
**Today´s Progress:** Finished Basic JavaScript Challenges from FCC.

### Day 10 - 20.8.2018 (Mon)
**Today´s Progress:** Did ES6-JS Challenges from FCC

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
**Today´s Progress:** Finished the section of ES6 Challenges from FCC

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
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part Responsive Web

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
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part Flexbox. 

**Thoughts:** *Flex-basis:* if the ```flex-basis``` is set to ```auto``` and at the same moment the element´s ```width/height``` is set, the ```auto``` is used. If the ```flex-basis``` is set in ```px or %```, the ```width/height``` is overwritten by the ```flex-basis``` value.

### Day 23 - 3.9.2018 (Mon)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part CSS Grid. Started the Portfolio Page. 

**Thoughts:** *CSS Grid:* used for 2-D positioning xxx *Flexbox:* used for 1-D positioning. 

*Wrapper of the whole content:* for better positioning of all elements use wrapper with ```min-height: 100%; position: relative;```. 

### Day 24 - 4.9.2018 (Tue)
**Today´s Progress:** Worked on my Portfolio Website (decided NOT to use Bootstrap) - header, welcome part.

### Day 25 - 5.9.2018 (Wed)
**Today´s Progress:** Continue working on my Portfolio Website - parts About me, Portfolio, Contacts, Footer (just the drafts).  Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part CSS Transforms. 

**Thoughts:** Source for CSS-3D-Transforms: [https://3dtransforms.desandro.com/](https://3dtransforms.desandro.com/)

### Day 26 - 6.9.2018 (Thu)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part Transitions, Animations. Learned to work with StyleLint and Autoprefixer on my in-person course.

### Day 27 - 7.9.2018 (Fri)
**Today´s Progress:** Finished the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part Sass.


### Day 28 - 8.9.2018 (Sat)
**Today´s Progress:** Started the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/).

### Day 29 - 9.9.2018 (Sun) 
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Continue with section JS Basics.

### Day 30 - 10.9.2018 (Mon) 
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Finished the section JS Basics.

**Thoughts:**  *JS-Expressions:* pieces of code which always produce a value.   *JS-Statements:* they perform an action (they don´t produce immediate results).

### Day 31 - 11.9.2018 (Tue)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Finished the section JS Behind The Scenes.

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
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Finished the section JS DOM Manipulation and Events.

### Day 33 - 13.9.2018 (Thu)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - Finished the section Advanced JS: Objects and Functions.

### Day 34 - 14.9.2018 (Fri)
**Today´s Progress:** Continue with the course on [JavaScript](https://www.udemy.com/the-complete-javascript-course/) - First part of The Budget App Project.

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
*DOM Manipulation examples and explanation:* [blog.garstasio](blog.garstasio.com/you-dont-need-jquery/dom_manipulation)

*Splice x slice:* ```splice``` - used to remove elements (from what index, how many) x ```slice``` - used to create a copy

*Event bubbling, event delegation:* used in 2 cases: 1. When we have an element with lots of child elements that we are interested in; 2. When we want an event handler attached to an element that is not yet in the DOM when our page is loaded.

### Day 37 - 17.9.2018 (Mon)
**Today´s Progress:** 




