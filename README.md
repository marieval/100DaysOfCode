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

**Thoughts:** Iframe elements are not responsive, so we need to wrap them with an other element (div). (Web Design Blueprints - p.29)

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

**Thoughts:** Flexbox-bugs: <button> and <fieldset> don´t work as flex-containers! (Solution: use <div> or other flex-supporting-element as immediate child of the <button> or <fieldset> (info: [Flexbugs](https://github.com/philipwalton/flexbugs#flexbug-9)).

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


## Day off - 26.8.2018 (Sun)

### Day 16 - 27.8.2018 (Mon)
**Today´s Progress:** Continue with the course on [CSS](https://www.udemy.com/css-the-complete-guide-incl-flexbox-grid-sass/) - part Background Images&Images, Sizes&Units










