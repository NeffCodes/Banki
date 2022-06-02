# BANKI: All the questions to prep for interviews

- Any questions on this list are fair game for technical interviews.
- Resources where you can find most answers are at the end.
- Original list courtesy of [https://leonnoel.com/100devs/](https://leonnoel.com/100devs/)

## Behavioral

Most of the behavioral questions should be answered in the CAR format. At least three sentences for each question (one for cause, one for action and one for result). When answering begin with "At my last opportunity..." or "At my last company". Don't sell yourself out and say "bootcamp" or "school".

### CAR

- **Cause**
  - Why did you need to take action?
- **Action**
  - Steps you took so solve problem
  - Be positive
  - Don't be humble
- **Result**
  - How are you better?

### Questions

- [ ] Give me an example of a project or initiative that you started on your own. What prompted you to get started?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a time you had to work on several projects at once. How did you handle this?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation in which you felt you had not communicated well enough. What did you do? How did you handle it?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about when you had to deal with conflict within your team. How was the conflict solved? How did you handle that? How would you deal with it now?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Give me an example of a time you had to take a creative and unusual approach to solve coding problem. How did this idea come to your mind? Why do you think it was unusual?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation in which you worked diligently on a project and it did not produce the desired results. Why didn't you get the desired results? What did you learn from the experience?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Give an example of an important project goal you reached and how you achieved it.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation in which you experienced difficulty in getting others to accept your ideas? What was your approach? How did this work? Were you able to successfully persuade someone to see things your way
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a situation when you were responsible for project planning. Did everything go according to your plan? If not, then why and what kind of counteractions did you have to take?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a situation when you made a mistake at work. What happened exactly and how did you deal with it? What steps did you take to improve the situation?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a time when you worked with someone who was not completing his or her share of the work. How did you handle the situation? Did you discuss your concern with your coworker? With your manager? If yes, how did your coworker respond to your concern? What was your manager's response?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation when you worked effectively under pressure. How did you feel when working under pressure? What was going on, and how did you get through it?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about yourself.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about your experience at 100Devs.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] What do you know about our company?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Why do you want to work for us?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Why are you interested in this opportunity?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about your dream job?  What do you really want to do with your career?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me a time when you failed.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] What do you read on a regular basis?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] What's some critical feedback you've gotten recently?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Do you have any questions?
  - **Cause:**
  - **Action:**
  - **Result:**

## Technical Questions

Most of the technical questions should have a three sentence response in the EUE format:

- **Explanation**
- **Use**
- **Example**

### HTML

- [ ] What does a doctype do?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How do you serve a page with content in multiple languages?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What kinds of things must you be wary of when designing or developing for multilingual sites?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are `data-` attributes good for?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Consider HTML5 as an open web platform. What are the building blocks of HTML5?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Describe the difference between a cookie, sessionStorage and localStorage.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Describe the difference between `<script>, <script async> and <script defer>`.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is it generally a good idea to position CSS `<link>`s within `<head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is progressive rendering?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why you would use a `srcset` attribute in an image tag? Explain the process the browser uses when evaluating the content of this attribute.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Have you used different HTML templating languages before?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### CSS

- [x] What is CSS selector specificity and how does it work?
  - **Explanation:**
    > The means by which browsers decide which CSS property values are the most relevant to an element and, therefore, will be applied.
  - **Use:**
    > Specificity is a weight that is applied to a given CSS declaration, determined by the number of each selector type in the matching selector.
  - **Example:**
    >
    > - !important has a value of 1000
    > - #id has a value of 100
    > - .class has a value of 10
    > - tag has a value of 1
    >  
    > So a selector of #id .class tag would have 111 points

  - **Source:** [MDN - CSS Specificity](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity)

- [x] What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
  - **Explanation:**
    > "normalizing" preserves useful deafults to be consistent across browsers, while "resetting" aims to remove all default styling.
  - **Use:**
    > Applying one or the other is a prefence to the developer, however going full on reset leads to more bugs and time needed to restyle everything.
  - **Example:**

    *Normalize*

    ```css
    /**
    * Correct the font size and margin on `h1` elements within `section` and 
    * `article` contexts in Chrome, Firefox, and Safari.
    **/

    h1 {
      font-size: 2em;
      margin: 0.67em 0;
    }
    ```

    *Resetting*

    ```css
    html, body, h1, h2, h3, h4, h5, h6 {
      margin: 0;
      padding: 0;
    }
    ```

  - **Source:** [Medium - Elad Shechter](https://elad.medium.com/normalize-css-or-css-reset-9d75175c5d1e)

- [x] Describe floats and how they work.
  - **Explanation:**
    > The float CSS property places an element on the left or right side of its   container, allowing text and inline elements to wrap around it. The element is removed from the normal flow of the page, though still remaining a part of the flow (in contrast to absolute positioning). The CSS clear property can be used to be positioned below left/right/both floated elements.
    >
    > **NOTE:** A parent element will collapse to zero height if it contains only floated elements, to fix this it was common to use a .clearfix hack.
  - **Use:**
    > It was a precursor to flex and grid to allow elements on a screen to be able to be layed out next to each other.
  - **Example:**
    > If you wanted three boxes to be next to each other, you would set all three in a parent container with a class of .clearfix, and set all 3 boxes to float left (or right) and have a width of 33.3333%
  - **Source:** [MDN - Floats](https://developer.mozilla.org/en-US/docs/Web/CSS/float) | [FE Interview Handbook](https://www.frontendinterviewhandbook.com/css-questions#describe-floats-and-how-they-work)

- [x] Describe z-index and how stacking context is formed.
  - **Explanation:**
    > The z-index property in CSS controls the vertical stacking order of elements that overlap. z-index only affects elements that have a position value which is not static.
  - **Use:**
    > Allows you to put elements on top of others
  - **Example:**
    > Say if you have a navigation that is fixed at the top or bottom of the screen, you can set the container with a z-index of 1 to have it placed on top of all the other elements.
  - **Source:** [FE Interview Handbook](https://www.frontendinterviewhandbook.com/css-questions#describe-floats-and-how-they-work)

- [x] Describe BFC (Block Formatting Context) and how it works.
  - **Explanation:**
  > A block formatting context (BFC) is a part of a visual CSS rendering of a web page. It's the region in which the layout of block boxes occurs and in which floats interact with other elements.
  - **Use:**
  > A BFC is an HTML box that satisfies at least one of the following conditions:
  >
  > - The value of float is not none.
  > - The value of position is neither static nor relative.
  > - The value of display is table-cell, table-caption, inline-block, flex, or inline-flex, grid, or inline-grid.
  > - The value of overflow is not visible.
  >
  > In a BFC, each box's left outer edge touches the left edge of the containing block (for right-to-left formatting, right edges touch).
  - **Example:**
  > A absolute positioned element on a page. 
  - **Source:** [MDN - Floats](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Block_formatting_context) | [FE Interview Handbook](https://www.frontendinterviewhandbook.com/css-questions#describe-block-formatting-context-bfc-and-how-it-works)

- [x] What are the various clearing techniques and which is appropriate for what context?
  - **Explanation:**
  >
  > - Clear method: clear property which sets whether an element must be moved below floating elements.
  > - Clearfix method: refers to the .clearfix class
  > - Overflow method: Using `overflow: hidden` or `overflow: auto` on a perent to establish a new block formatting context and epand to contain its floated children.
  >
  - **Use:**
  >
  > - Clear: used in float layouts. Use this if you want to have adjacent floated elements to stack instead
  > - Clearfix: used in float layouts on a parent element that contains floated children. Will expand the parent to contain the children, otherwise will collapse, just as if it's floated childen had been positioned absolutely. 
  >
  >   .clearfix utility class is probably the best method to use in general as it doesn't take long to construct and doesn't suffer from clipping issues like the overflow methods.
  > - Overflow: overflow hidden can cause children to be hidden if taller than parent
  >
  - **Source:** [Educative](https://www.educative.io/edpresso/what-is-a-clearfix-in-css) | [FE Interview Handbook](https://www.frontendinterviewhandbook.com/css-questions)

- [x] Explain CSS sprites, and how you would implement them on a page or site.
  - **Explanation:**
  > CSS sprites are multiple images combined together into a single larger image. Commonly use for icons.
  - **Use:**
  > You can use a sprite generator to create it. Once made, each image would  have a corresponding CSS class with `background-image`, `background-position`, and `background-size` properties definded.
  >
  > This is usefule because it reduces the number of HTTP requests a browser may need to do which would increase load speed.
  - **Example:** 
  > An example would be combining press logo's for Wired, NY Times and The Washington Post into a single image file. Then on the site, with CSS, placing the file three times and moving/cropping it to display the applicable logo.
  - **Source:** [css-tricks](https://css-tricks.com/css-sprites/)

- [x] How would you approach fixing browser-specific styling issues?
  - **Explanation:**
  > There are a couple of ways to solve the issue such as browser specific stylesheets, using a library like bootstrap, or using css Normalize/Reset.  I'd rather use a combination as going full nuke with a reset isn't necessary and makes it a little harder to debug and using libraries can b.
  - **Use:**
  > I prefer to use the normalize/reset style sheet method. Using libraries can be "heavy" depending on the project and takes time to learn all the different classes, and trying to pinpoint a specific issue to a browser can be time consuming.
  - **Source:** [FE Interview Handbook](https://www.frontendinterviewhandbook.com/css-questions)
- [ ] How do you serve your pages for feature-constrained browsers? What techniques/processes do you use?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the different ways to visually hide content (and make it available only for screen readers)?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Have you ever used a grid system, and if so, what do you prefer?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Have you used or implemented media queries or mobile specific layouts/CSS?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Are you familiar with styling SVG?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Can you give an example of an `@media` property other than screen?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are some of the "gotchas" for writing efficient CSS?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the advantages/disadvantages of using CSS preprocessors?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Describe what you like and dislike about the CSS preprocessors you have used.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How would you implement a web design comp that uses non-standard fonts?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain how a browser determines what elements match a CSS selector.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Describe pseudo-elements and discuss what they are used for.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain your understanding of the box model and how you would tell the browser, through CSS, to render your layout in different box models.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What does `* { box-sizing: border-box; }` do? What are its advantages?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the CSS `display` property and can you give a few examples of its use?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What's the difference between `inline` and `inline-block`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What's the difference between a `relative`, `fixed`, `absolute` and `static` positioned element?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Have you played around with the new CSS Flexbox or Grid specs?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Can you explain the difference between coding a web site to be responsive versus using a mobile-first strategy?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How is responsive design different from adaptive design?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Have you ever worked with retina graphics? If so, when and what techniques did you use?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Is there any reason you'd want to use `translate()` instead of `absolute` positioning, or vice-versa? And why?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### Javascript

- [ ] Explain event delegation
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain how `this` works in JavaScript
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain how prototypal inheritance works
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What do you think of AMD vs CommonJS?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain why the following doesn't work as an IIFE: `function foo(){ }();`. What needs to be changed to properly make it an IIFE?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What's the difference between a variable that is: `null`, `undefined` or undeclared? How would you go about checking for any of these states?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a closure, and how/why would you use one?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Can you describe the main difference between a `.forEach()` loop and a `.map()` loop and why you would pick one versus the other?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What's a typical use case for anonymous functions?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How do you organize your code? (module pattern, classical inheritance?)
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What's the difference between host objects and native objects?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What's the difference between `.call()` and `.apply()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain `Function.prototype.bind`.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] When would you use `document.write()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What's the difference between feature detection, feature inference, and using the UA string?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain Ajax in as much detail as possible.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the advantages and disadvantages of using Ajax?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain how JSONP works (and how it's not really Ajax).
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Have you ever used JavaScript templating? If so, what libraries have you used?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain "hoisting".
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Describe event bubbling.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What's the difference between an "attribute" and a "property"?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is extending built-in JavaScript objects not a good idea?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Difference between document `load` event and document `DOMContentLoaded` event?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the difference between `==` and `===`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain the same-origin policy with regards to JavaScript.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Make this work: `duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]`
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is it called a ternary expression, what does the word "ternary" indicate?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is "use strict";? what are the advantages and disadvantages to using it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Create a for loop that iterates up to 100 while outputting "fizz" at multiples of 3, "buzz" at multiples of 5 and "fizzbuzz" at multiples of 3 and 5
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain what a single page app is and how to make one SEO-friendly.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the extent of your experience with Promises and/or their polyfills?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the pros and cons of using Promises instead of callbacks?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What tools and techniques do you use debugging JavaScript code?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What language constructions do you use for iterating over object properties and array items?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain the difference between mutable and immutable objects.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain the difference between synchronous and asynchronous functions.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is event loop? What is the difference between call stack and task queue?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain the differences on the usage of foo between `function foo() {}` and `var foo = function() {}`
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the differences between variables created using `let`, `var` or `const`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the differences between ES6 class and ES5 function constructors?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Can you offer a use case for the new arrow => function syntax? How does this new syntax differ from other functions?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What advantage is there for using the arrow syntax for a method in a constructor?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the definition of a higher-order function?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Can you give an example for destructuring an object or an array?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] ES6 Template Literals offer a lot of flexibility in generating strings, can you give an example?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Can you give an example of a curry function and why this syntax offers an advantage?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the benefits of using spread syntax and how is it different from rest syntax?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How can you share code between files?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why you might want to create static class members?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### Javascript General

- [ ] Can you name two programming paradigms important for JavaScript app developers?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is functional programming?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the difference between classical inheritance and prototypal inheritance?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the pros and cons of functional programming vs object-oriented programming?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are two-way data binding and one-way data flow, and how are they different?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is asynchronous programming, and why is it important in JavaScript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### Node

- [ ] What is Node.js? Where can you use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why use Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the features of Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How do you update NPM to a new version in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is Node.js Single-threaded?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain callback in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is callback hell in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How do you prevent/fix callback hell?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain the role of REPL in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Name the types of API functions in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are the functionalities of NPM in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the difference between Node.js and Ajax?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are “streams” in Node.js? Explain the different types of streams present in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain chaining in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are Globals in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is Event-driven programming?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is Event loop in Node.js work? And How does it work?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the purpose of `module.exports` in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the difference between Asynchronous and Non-blocking?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is Tracing in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] How will you debug an application in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Difference between `setImmediate()` and `setTimeout()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is `process.nextTick()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is package.json? What is it used for?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is libuv?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are some of the most popular modules of Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is `EventEmitter` in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### CS Theory

- [ ] What is recursion and give an example using javascript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are types?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What are data structures?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is an algorithm?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is scope / lexical scope in javascript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is polymorphism?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is encapsulation?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Linked List?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Doubly Linked List?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Queue?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Stack?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Hash Table?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Heap?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Trie?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Tree?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Binary Search Tree?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Disjoint Set?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is a Bloom Filter?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Bubble Sort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Insertion Sort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Merge Sort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Demonstrate Quicksort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

## Questions to ask your interviewer

1. How does Bob’s Burgers measure the success of their engineers?
2. What challenges can an engineer come across while working at Bob’s Burgers?
3. Can you explain "thing you read on their engineering blog" and how it affects Bob’s Burgers Engineers?
4. What traits are hard to find in an engineer that Bob’s Burgers would like to have?
5. How is critique given to engineers at Bob’s Burgers?
6. Do you have any questions or concerns about my qualifications?

Here is a helpful list of other reverse interview questions: [https://github.com/viraptor/reverse-interview](https://github.com/viraptor/reverse-interview)

## Whiteboard

When talking through a whiteboard problem or a coding challenge with an interviewer you should use the PREP method. (Don't write PREP in the actual interview, but use it now while doing codewars/leetcode). Going through this will help you engage with the interviewer (and possibly burn up some time 😉)

- **Parameters**
  - Inputs
  - Ask questions
    - Will it always be a number?
    - Will it ever be negative?
    - Any gotchas?
- **Returns**
  - Ask questions
    - Do you want it returned or is a console.log better?
    - Should I pass a whole array of solutions back or just a single solution?
- **Examples**
  - Show a couple black box examples, aka test cases
    - I pass in these arguments and get these results, is that correct?
  - Examples are a good idea because "you have the receipts" if the interviewer decides to change things.
- **Pseudocode**
  - Write pseudocode of each of the steps

## Resources

- [https://eloquentjavascript.net/](https://eloquentjavascript.net/)
- [https://github.com/getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS)
- [https://github.com/yangshun/front-end-interview-handbook](https://github.com/yangshun/front-end-interview-handbook)
- [https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)
- [https://www.simplilearn.com/node-js-interview-questions-and-answers-article](https://www.simplilearn.com/node-js-interview-questions-and-answers-article)
- [https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678](https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678)
