# javascript-30-days-challenge
30 day Vanilla JavaScript coding challenge

## Project List

### 1. JavaScript Drum Kit
![drum-kit](https://user-images.githubusercontent.com/40417828/116617206-6e3d5f80-a8f2-11eb-97f2-d12e47530064.jpg)
[JS Drum Kit](https://jjessicacho.github.io/javascript-30-days-challenge/drum-kit/)

#### Things I learned:
- key events
    - `data attributes`: allow us to store extra information on standard
- audio
- transition end event / animation end event


### 2. CSS JavaScript Clock 
![clock](https://user-images.githubusercontent.com/40417828/116766547-e59ced00-a9df-11eb-8c7f-6a6e389c195a.jpg)
[CSS JS Clock](https://jjessicacho.github.io/javascript-30-days-challenge/css-js-clock/)
#### Things I learned:
- current time:
    - `getHours()`
    - `getMinutes()`
    - `getSeconds()`
- degree: `((seconds / 60) * 360) + 90`;
- `transition-timing-function: ease-in-out`
- style height property 

### 3. CSS Variable
![css-variables](https://user-images.githubusercontent.com/40417828/116798518-1004ae00-aaa5-11eb-8829-0fdbbacd1686.jpg)
[CSS Variables](https://jjessicacho.github.io/javascript-30-days-challenge/css-variables/)

#### Things I learned:
- mouse event
- forEach
- `style.setProperty(propertyName, value, priority);`
    - `propertyName` is a `DOMString` representing the CSS property name (hyphen case) to be modified.
    - `value` (Optional) is a `DOMString` containing the new property value. If not specified, treated as the empty string.
    *Note*: value must not contain "!important" -- that should be set using the priority parameter.

### 4. Array Cardio Day 1
[Array Cardio Day 1](https://jjessicacho.github.io/javascript-30-days-challenge/array-cardio-day-01/)
#### Things I learned:
- `console.table`: shows a table in the console 
- array filter
- array map
- array sort
- array reduce
- arrow function

### 5. Flex Panel Gallery
![flex-panel-gallery](https://user-images.githubusercontent.com/40417828/117208316-d7691b00-ada9-11eb-90f6-abfa8b3143b7.jpg)
[Flex Panel Gallery](https://jjessicacho.github.io/javascript-30-days-challenge/flex-panel-gallery/)

#### Things I learned:
- Advanced css flexbox
- Transition
- toggleOpen
- toggleActive
- transition"end" not transtioned


### 6. Type Ahead
![type-ahead](https://user-images.githubusercontent.com/40417828/117385483-14acd600-ae9a-11eb-8787-837792e6bea5.jpg)
[Type Ahead](https://jjessicacho.github.io/javascript-30-days-challenge/type-ahead/)

#### Things I learned:
- Fetch API 
- Promises 


### 7. Array Cardio Day 2
[Array Cardio Day 2](https://jjessicacho.github.io/javascript-30-days-challenge/array-cardio-day-02/)

#### Things I learned:
- `Array.prototype.some()`
- `Array.prototype.every()`
- `Array.prototype.find()`
- `Array.prototype.findIndex()`
- How to delete the comment without using `splice` (very popular in Redux): create a new array of the updated comments
```js
  const index = comments.findIndex(comment => comment.id === 823423);
  
  //comments.splice(index, 1);

  const newComments = [
    ...comments.slice(0, index),
    ...comments.slice(index + 1)
  ];
```

### 8. HTML5 Canvas
![canvas](https://user-images.githubusercontent.com/40417828/117739042-48e20880-b1b2-11eb-9c2f-b72ac4def9c1.jpg)
[HTML5 Canvas](https://jjessicacho.github.io/javascript-30-days-challenge/canvas/)

#### Things I learned:
- Change width and height to 100% screen in JavaScript
- lineJoin, lineCap: "bevel" || "round" || "miter"
- Blend mode
- Stroke Style: `hsl(${hue}, 100%, 50%)`
- How to make it more simple: 
```js
[lastX, lastY] = [e.offsetX, e.offsetY];
  // this is same as following:
  // lastX = e.offsetX;
  // lastY = e.offsetY;
```


### 9. Dev Tools Domination
[Dev Tools Domination](https://jjessicacho.github.io/javascript-30-days-challenge/dev-tools-domination/)

#### Things I learned:
console
- log
- interpolated ('')
- styled (css)
- warning: warn
- error 
- testing
- clear
- viewing DOM Elements: dir
- grouping together: group
- counting: count
- timing (how long it takes): time, timeEnd, fetch


### 10. Hold Shift to Check Checkbox
![checkbox](https://user-images.githubusercontent.com/40417828/118047152-36410e00-b32f-11eb-9945-db2e6d641121.jpg)
[Hold Shift to Check Checkbox](https://jjessicacho.github.io/javascript-30-days-challenge/checkbox/)

#### Things I learned:
- choose multiple checkbox
  - loop 
  - forEach
- flag variable


### 11. Custom Video Player
![custom-video-player](https://user-images.githubusercontent.com/40417828/118204882-13d4f080-b414-11eb-946d-fa498c6a4245.jpg)
[Custom Video Player](https://jjessicacho.github.io/javascript-30-days-challenge/custom-video-player/)

#### Things I learned:
- play video
- pause video
- drag video bar
- update bar
- volume up and down
- skip before (-10 seconds) and after (25 seconds) 


### 12. Key Sequence Detection (KONAMI CODE)
![key-sequence-detection](https://user-images.githubusercontent.com/40417828/118204884-15061d80-b414-11eb-8455-7fd750a500e7.jpg)
[Key Sequence Detection](https://jjessicacho.github.io/javascript-30-days-challenge/key-sequence-detection/)

#### Things I learned:
- key sequencing detection
- store them in an array
- check every single time that they key up if it matches what you're looking for



### 13. Slide In on Scroll
![slide](https://user-images.githubusercontent.com/40417828/118336838-54da0d00-b4c7-11eb-9926-29e79cfd57d4.jpg)
[Slide In on Scroll](https://jjessicacho.github.io/javascript-30-days-challenge/slide-in-on-scroll/)

#### Things I learned:
- console.count()
- Calculate half way through the image and bottom of the image
  - window.scrollY
  - offsetTop



### 14. JavaScript References VS Copy
[JavaScript References VS Copy](https://jjessicacho.github.io/javascript-30-days-challenge/js-references-vs-copying/)

#### Things I learned:
- array concat
- object assign
- JSON parse (not really recommended)



### 15. LocalStorage
[LocalStorage](https://jjessicacho.github.io/javascript-30-days-challenge/local-storage/)

#### Things I learned:
- preserve log
- save items to local storage 



















## Source
[JavaScript 30 by Wes Bros](https://javascript30.com/)

Photo by <a href="https://unsplash.com/@gopack?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Alexander Yemchenko</a> on <a href="https://unsplash.com/s/photos/drum?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  
[keycode](http://keycode.info/)

[Using data attributes MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Howto/Use_data_attributes)

[Style Height Property w3school](https://www.w3schools.com/jsref/prop_style_height.asp)

[CSS Style Declaration MDN](https://developer.mozilla.org/en-US/docs/Web/API/CSSStyleDeclaration/setProperty)

[Array.prototype.filter() MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)

[Array.prototype.map() MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

[Array.prototype.sort() MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)

[Array.prototype.reduce() MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)

[10 Classical Music Composers to Know](https://www.britannica.com/list/10-classical-music-composers-to-know)

[Learn Fetch API In 6 Minutes by Web Dev Simplified](https://www.youtube.com/watch?v=cuEtnrL9-H0)

[CanvasRenderingContext2D.lineJoin](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/lineJoin)

[How to select only one DIV from multiple divs using javascript](https://stackoverflow.com/questions/31531461/how-to-select-only-one-div-from-multiple-divs-using-javascript/31533039)