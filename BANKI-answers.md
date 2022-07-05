# BANKI: All the questions to prep for interviews

- Any questions on this list are fair game for technical interviews.
- Resources where you can find most answers are at the end.
- Original list courtesy of [https://leonnoel.com/100devs/](https://leonnoel.com/100devs/)

---

## Table of Contents

1. [Behaviorial](#behavioral)
2. [Technical](#technical-questions)
    - [HTML](#html)
    - [CSS](#css)
    - [Javascript](#javascript)
    - [Javascript General](#javascript-general)
    - [Node](#node)
    - [CS Theory](#cs-theory)
3. [Questions to ask your interviewer](#questions-to-ask-your-interviewer)
4. [Whiteboard](#whiteboard)
5. [Resources](#resources)

---

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

- [x] Give me an example of a project or initiative that you started on your own. What prompted you to get started?
  - **Cause:**
  When I first started working at Professional Printers, there was no documentation at all for my role as an account manager.
  - **Action:**
  I had a lot of questions, and instead of having to go back and re-ask, I started writing down my questions and with the answers.
  - **Result:**
  As a result, I had a complete "beginner's" guide written out, which I provided to my manager who went on to use it for all future trainings. This documentation alone cut the amount of on-board time by 25%.

- [x] Tell me about a time you had to work on several projects at once. How did you handle this?
  - **Cause:**
  In my previous role, I had multiple projects at once on a daily basis.
  - **Action:**
  I learned to keep track of the ongoing projects with my own tracker. By having great communication with the customers and with department heads, I was then able to prioritize which projects to address to ensure all were done on schedule.
  - **Result:**
  As a result, I was able to break the company record for most handled projects without any spoilages.

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

---

## Technical Questions

Most of the technical questions should have a three sentence response in the EUE format:

- **Explanation**
- **Use**
- **Example**

### HTML

- [x] What does a doctype do?
  - **Explanation:**
  > DOCTYPE is an abbreviation for Document Type. A DOCTYPE is always associated to a DTD - for Document Type Definition.
  - **Use:**
  > For webpages, the DOCTYPE declaration is required. It is used to tell user agents what version of the HTML specifications your document respects.
  - **Example:**
  > The DOCTYPE declaration for the HTML5 standards is `<!DOCTYPE html>`.
  - **Source:** [FE Interview Handbook](https://www.frontendinterviewhandbook.com/html-questions/#what-does-a-doctype-do)

- [x] How do you serve a page with content in multiple languages?
  - **Explanation:**
  > By setting the lang attributes on the various elements within the page.
  - **Use:**
  > The lang attribute can be used on various elements (typically html, p, li...)
  - **Example:**
  > You can set the whole site as being english by setting the html element `<html lang="en">` Or you could set a paragraph as spanish with `<p lang="es">`
  - **Source:** [MDN]( https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/lang)

- [x] What kinds of things must you be wary of when designing or developing for multilingual sites?
  - **Explanation:**
  > There are quite a few different nuances to pay attention to including:
  >
  > - Including the lang attribute
  > - Allowing users to change the language
  > - Minimize text in raster based images
  > - Text overflow when translated
  > - How colors are perceived
  > - Date and currency formats
  > - Language reading direction
  > - Don't concatenate translated strings
  >
  - **Source:** [FE Interview Handbook](https://www.frontendinterviewhandbook.com/html-questions/#what-kind-of-things-must-you-be-wary-of-when-designing-or-developing-for-multilingual-sites)

- [x] What are `data-` attributes good for?
  - **Explanation:**
  > They allow the storage data to the page or elements within the page
  - **Use:**
  > Generally not encouraged. Users are able to modify the data attribute easily with inspect tool.
  >
  > However, one perfectly valid use of data attributes, is to add a hook for end to end testing frameworks without having to create a meaningless classes or ID attributes.
  - **Example:**
  > `data-selector='the-thing'`
  - **Source:** [FE Interview Handbook](https://www.frontendinterviewhandbook.com/html-questions/#what-are-data--attributes-good-for)

- [x] Consider HTML5 as an open web platform. What are the building blocks of HTML5?
  - **Explanation:**
  >
  > - Semantics - Allowing you to describe more precisely what your content is.
  > - Connectivity - Allowing you to communicate with the server in new and innovative ways.
  > - Offline and storage - Allowing webpages to store data on the client-side locally and operate offline more efficiently.
  > - Multimedia - Making video and audio first-class citizens in the Open Web.
  > - 2D/3D graphics and effects - Allowing a much more diverse range of presentation options.
  > - Performance and integration - Providing greater speed optimization and better usage of computer hardware.
  > - Device access - Allowing for the usage of various input and output devices.
  > - Styling - Letting authors write more sophisticated themes.
  >
  - **Source:** [FE Interview Handbook](https://www.frontendinterviewhandbook.com/html-questions#consider-html5-as-an-open-web-platform-what-are-the-building-blocks-of-html5)
  
- [x] Describe the difference between a cookie, sessionStorage and localStorage.
  - **Explanation:**
  > Cookies can be initiated by the server, have a manually set expiration date are small file size and are sent to the server with HTTP request. Local and session are both initiated by the client, are a relatively large file and aren't sent to the server. The main difference between local and session is that local storage will persist forever until cleared manually and can be accessed by any window in the browser. Session storage can only be accessed by the same tab.
  - **Use:**
  > All the above-mentioned technologies are key-value storage mechanisms on the client side and can only store values as strings.
  - **Source:** [FE Interview Handbook](https://www.frontendinterviewhandbook.com/html-questions#describe-the-difference-between-a-cookie-sessionstorage-and-localstorage)

- [x] Describe the difference between `<script>, <script async> and <script defer>`.
  - **Explanation:**
  >
  > - `<script>` - HTML parsing is blocked, the script is fetched and executed immediately, HTML parsing resumes after the script is executed.
  > - `<script async>` - The script will be fetched in parallel to HTML parsing and executed as soon as it is available (potentially before HTML parsing completes). Use async when the script is independent of any other scripts on the page, for example, analytics.
  > - `<script defer>` - The script will be fetched in parallel to HTML parsing and executed when the page has finished parsing. If there are multiple of them, each deferred script is executed in the order they were encountered in the document. If a script relies on a fully-parsed DOM, the defer attribute will be useful in ensuring that the HTML is fully parsed before executing. A deferred script must not contain document.write.
  >
  - **Use:**
  >
  > - Use `async` when the script is independent of any other scripts on the page
  >
  > - `defer` is useful when you need to make sure the HTML is fully parsed before executing.

  - **Example:**
  >
  > - `async` could be used for analytics scripts.
  >
  > - A deferred script must not contain document.write

  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/html-questions#describe-the-difference-between-script-script-async-and-script-defer)

- [x] Why is it generally a good idea to position CSS `<link>`s within `<head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
  - **Explanation:**
  > Putting `<link>`s in the `<head>` allows for quick "first meaningful paint". When a page first loads, HTML and CSS are being parsed simultaneously. If you put it at the bottom of the documnet cnan lead to bugs/issues, including users just seeing a blank page or flashes of unstyled content.
  >
  >`<script>` tags block HTML parsing while they are being downloaded and executed which can slow down your page. Placing the scripts at the bottom will allow the HTML to be parsed and displayed to the user first

  - **Exception:**
  > These days its not considered to be good practice, but if your script contains `document.write()` you would put it in the `<head>`.
  >
  >Also if you need to put `<script>`s in the `<head>`, use the `defer` attribute, which will achieve the same effect of running the script only after the HTML is parsed but the browser can download the script earlier.
  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/html-questions#why-is-it-generally-a-good-idea-to-position-css-links-between-headhead-and-js-scripts-just-before-body-do-you-know-any-exceptions)

- [x] What is progressive rendering?
  - **Explanation:**
  > Progressive rendering is the name given to techniques used to improve the performance of a webpage (in particular, improve perceived load time) to render content for display as quickly as possible.
  - **Use:**
  > To improve the perceived load time of a page/content.
  - **Example:**
  >| Type | Description |
  >| ---| --- |
  >| Lazy Loading Images | Images on the page are not loaded all at once. JavaScript will be used to load an image when the user scrolls into the part of the page that displays the image.|
  > | Prioritizing visible content (aka above the fold) | Include only the minimum CSS/content/scripts necessary for the amount of page that would be rendered in the users browser first to display as quickly as possible, you can then use deferred scripts or listen for the DOMContentLoaded/load event to load in other resources and content.|
  > | Async HTML Fragments | Flushing parts of the HTML to the browser as the page is constructed on the back end |
  >
  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/html-questions#what-is-progressive-rendering)

- [x] Why you would use a `srcset` attribute in an image tag? Explain the process the browser uses when evaluating the content of this attribute.
  - **Explanation:**
  > When you want to serve different images to users depending on their device display width
  - **Use:**
  > Serving higher quality images to devices with retina display enhances the user experience while serving lower resolution images to low-end devices increase performance and decrease data wastage
  - **Example:**
  > `<img srcset="small.jpg 500w, medium.jpg 1000w, large.jpg 2000w" src="..." alt="">` tells the browser to display the small, medium or large .jpg graphic depending on the client's resolution.
  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/html-questions#why-you-would-use-a-srcset-attribute-in-an-image-tag-explain-the-process-the-browser-uses-when-evaluating-the-content-of-this-attribute)

- [x] Have you used different HTML templating languages before?
  - Yes, I have used Markdown, and have experience with Handlebars with Python and Mustache with React. They seem to provide similar functionality of escaping content and helpful filters for manipulating the data to be displayed.

  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/html-questions#have-you-used-different-html-templating-languages-before)

---

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
- [x] How do you serve your pages for feature-constrained browsers? What techniques/processes do you use?
  - **Explanation:**
  >
  > - Graceful degradation — The practice of building an application for modern browsers while ensuring it remains functional in older browsers.
  > - Progressive enhancement — The practice of building an application for a base level of user experience, but adding functional enhancements when a browser supports it.
  >
  - **Use:**
  >
  > - Use caniuse.com to check for feature support.
  > - Autoprefixer for automatic vendor prefix insertion.
  > - Feature detection using Modernizr.
  > - Use CSS Feature queries @support
  >
  - **Example:**
  > Instead of filling the site with `<div>` using more semantically appropriate tags like `<section> <aside> <article> <header> <footer>`
  - **Source:** [Developers life](https://blog.bullgare.com/2018/02/front-end-interview-questions-with-answers/#How_do_you_serve_your_pages_for_feature-constrained_browsers_What_techniquesprocesses_do_you_use)

- [x] What are the different ways to visually hide content (and make it available only for screen readers)?
  - **Explanation:**
  >
  > - Make the element have a size of zero width: 0; height: 0
  > - Absolute position off screen position: absolute; left: -99999px
  > - Text indent off screen if within block element text-indent: -9999px
  > - aria-label which will read the string given to the attribute.
  >
  - **Use:**
  > Generally, using the Absolute positioning is the best method since it has the least caveats, works for most elements and it's an easy technique.
  - **Source:** [FE Interview Handbook](https://www.frontendinterviewhandbook.com/css-questions)

- [x] Have you ever used a grid system, and if so, what do you prefer?
  - **Explanation:**
  > Yes, in the past I've used Bootstrap (which is based on the 12 column system), but now I typically use the 12 column grid system using flex or grid. However, depending on the scale of the project, I may use a 6 column.
  - **Use:**
  > Using the grid system is my ideal way to mockup any design with visual consistency. When if comes to coding the site I find it helps speed up the layout immensely as well.
  - **Source:** [Flux Academy](https://www.flux-academy.com/blog/how-to-use-a-grid-in-web-design)

- [x] Have you used or implemented media queries or mobile specific layouts/CSS?
  - **Explanation:**
  > Yes, quite frequently
  - **Use:**
  >  I use them on every website, typically by building mobile first. The breakpoints and media queries are then used to convert the layout from mobile to ipads to desktop.
  - **Example:**
  > An example would be changing a bunch of cards from being a single column stack on mobile to a three column layout on desktop.
  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/css-questions#have-you-used-or-implemented-media-queries-or-mobile-specific-layoutscss)
  
- [x] Are you familiar with styling SVG?
  - **Explanation:**
  > Yes, there are several ways to color shapes (including specifying attributes on the object) using inline CSS, an embedded CSS section, or an external CSS file. Most SVG you'll find around the web use inline CSS, but there are advantages and disadvantages associated with each type.
  - **Use:**
  > Basic coloring can be done by setting two attributes on the node: `fill` and `stroke`
  - **Example:**
  > `<rect width="100" height="100" stroke="blue" fill="purple" />`
  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/css-questions#are-you-familiar-with-styling-svg)

- [x] Can you give an example of an `@media` property other than screen?
  - **Explanation:**
  > There are four types of `@media` propertes: all, print, speech, and screen
  - **Use:**
  >
  > - `all` is for all media type devices
  > - `print` is for printers
  > - `speech` is for screenreaders that "reads" that page out loud
  > - `screen` is for computer / table / phone screens
  >
  - **Example:**

   ```css
  @media print {
    body { 
      color: black; 
    }
  }
  ```

  - **Source:** [FE nterview handbook](https://www.frontendinterviewhandbook.com/css-questions#can-you-give-an-example-of-an-media-property-other-than-screen)

- [x] What are some of the "gotchas" for writing efficient CSS?
  - **Explanation:**
  >
  > - Browsers match selectors from rightmost (key selector) to left. The shorter the length of the chain the faster the browser can find a match. Avoid using tag and universal selectors for your key selector.
  > - Avoid using styles that trigger reflow.
  >
  - **Example:**
  >
  >| Bad | Good |
  >| ---| --- |
  >| `html body p .class a`  | `.targetedClass` |
  >
  - **Source:** [CSS Triggers](https://csstriggers.com/) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/css-questions#what-are-some-of-the-gotchas-for-writing-efficient-css)

- [x] What are the advantages/disadvantages of using CSS preprocessors?
  - **Explanation:**
  > **Advantages** would be:
  >
  > - The code is easier to maintain
  > - More efficient to write with nested selectors
  > - Mixins can be used for repeated styles
  > - Ability to split into different files
  >
  > **Disadvantages** would be:
  >
  > - Additional tooling is required
  > - You aren't able to use the most current features of standard CSS
  >

  - **Example:**
  > Sass, Less, PostCSS
  - **Source:** [MDN CSS Preprocessors](https://developer.mozilla.org/en-US/docs/Glossary/CSS_preprocessor) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/css-questions#what-are-the-advantagesdisadvantages-of-using-css-preprocessors)

- [x] Describe what you like and dislike about the CSS preprocessors you have used.
  - **Explanation:**
  > I find the nested selectors to be very handy, along with the other advantages of using a preprocessor. It's easier to maintain and update as the project grows. However, some downsides would be making it slightly more difficult to debug due to the compilation step. Also, the css file produced can become very large if you're not careful.

  - **Source:** [Adam Silver](https://adamsilver.io/blog/the-disadvantages-of-css-preprocessors/)

- [x] How would you implement a web design comp that uses non-standard fonts?
  - **Explanation:**
  > Use the `@font-face` css rule and define the `font-family` with the font you want to use. Then provide the `src` of where the font is.
  - **Use:**
  > As mentioned, you would use this to add a non-standard font to a site, either from a remote server or a locally-installed font.
  - **Example:**

  ```css
    @font-face {
      font-family: "Open Sans";
      src: 
        url("/fonts/OpenSans-Regular-webfont.woff2") format("woff2"),
        url("/fonts/OpenSans-Regular-webfont.woff") format("woff");
    }
  ```

  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/css-questions#how-would-you-implement-a-web-design-comp-that-uses-non-standard-fonts) | [MDN @font-face](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face)

- [x] Explain how a browser determines what elements match a CSS selector.
  - **Explanation:**
  > Browsers match selectors from rightmost (key selector) to left. Browsers filter out elements in the DOM according to the key selector and traverse up its parent elements to determine matches.
  - **Use:**
  > The shorter the length of the selector chain, the faster the browser can determine if that element matches the selector.
  - **Example:**
  > If the selector is `p span`, browser firstly find all the `<span>` elements and then traverse up its parents all the way to the root to find the `<p>` element. For a particular `<span>`, as soon as it finds a `<p>`, it knows that the `<span>` matches and can stop its matching.
  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/css-questions#explain-how-a-browser-determines-what-elements-match-a-css-selector)

- [x] Describe pseudo-elements and discuss what they are used for.
  - **Explanation:**
  > CSS pseudo-elemnt is a keyword added to a selector that lets you style a specific part of the selected element(s).
  - **Use:**
  > You can use only one pseudo-element in a selector. It must appear after the simple selectors in the statement.
  >
  >**NOTE** as a rule, double colons (`::`) should be used instead of a single colon (`:`). This distinguishes pseudo-classes from psuedo-elements.
  - **Example:**
  > A couple of examples would be like `::first-line` in `p::first-line` to target the first line of a paragraph to stylize
  - **Source:** [MDN Psuedo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/css-questions#describe-pseudo-elements-and-discuss-what-they-are-used-for)

- [x] Explain your understanding of the box model and how you would tell the browser, through CSS, to render your layout in different box models.
  - **Explanation:**
  > The CSS box model describes the rectangular boxes that are generated for elements in the document tree and laid out according to the visual formatting model.
  >
  > Each box has a content area (e.g. text, an image, etc.) and optional surrounding padding, border, and margin areas.
  - **Use:**
  > The CSS Box Models is responsible for calculating
  >
  > - How much space a block-level element takes up
  > - Whether or not borders and/or margins overlap/collapse
  > - The box's dimensions
  > - To a certain extent, the box's position relative to other content on the page
  >
  - **Example:**
  > The standard box model calculates box size by taking a specified height and width, then adding the padding and border. However to change to the alternative box model you would set box-sizing: border-box which allows you to set the box size with height and width.
  - **Source:** [MDN CSS Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model#what_is_the_css_box_model) | [Smashing Magazine](https://www.smashingmagazine.com/2010/06/the-principles-of-cross-browser-css-coding/#understand-the-css-box-model)

- [x] What does `* { box-sizing: border-box; }` do? What are its advantages?
  - **Explanation / Use:**
  > That is the alternative CSS Box model. Instead of calculating the width of a box then adding the border and padding to get the real size, it instead allows you set the "true" width and height of a box, including the padding and border, and sets if for all elements with the `*` selector.
  - **Source:** [MDN CSS Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model#what_is_the_css_box_model)

- [x] What is the CSS `display` property and can you give a few examples of its use?
  - **Explanation / Use:**
  > The display CSS property sets whether an element is treated as a block or inline element and the layout used for its children, such as flow layout, grid or flex.
  - **Example:**

  | `display` property | Description |
  | ------------------ | ----------- |
  | `none`             | does not display the element       |
  | `block`            | the element takes up the whole line in the block direction (default horizontal)        |
  | `inline`           | the element can be laid out beside each other       |
  | `flex`             | the elementbehaves like a block element and lays out its content according to the flexbox model        |
  - **Source:** [MDN CSS display](https://developer.mozilla.org/en-US/docs/Web/CSS/display)

- [x] What's the difference between `inline` and `inline-block`?
  - **Explanation:**
  > `inline` does not respect the width/height and only allows you to set the padding/margins for the left and right
  >
  > `inline-block` does respect the width/height and allows you to set the padding/margins on all sides.
  - **Source:** [Digital Ocean](https://www.digitalocean.com/community/tutorials/css-display-inline-vs-inline-block)

- [x] What's the difference between a `relative`, `fixed`, `absolute` and `static` positioned element?
  - **Explanation:**
  
  | `position`   | uses top, bottom, right, left, and z-index | description |
  | --------   | --- | ---|
  | `static`   | no  | DEFAULT: the element is positioned according to the normal flow of the document |
  | `relative` | yes | the element is positioned according to the normal flow of the document, and then offset relative to itself|
  | `fixed`    | yes |  the element removed from page flow and placed in spot relative to viewport. It won't move when scrolled |
  | `absolute` | yes | the element removed from page flow and positioned relative to it closest "positioned" ancestor. Original space on the page is not preserved |
  | `sticky`   | yes  | the element is positioned according to the normal flow of the document, and then offset relative to its nearest scrolling ancestor and containing block  |
  - **Use:**
  > Use the position to set how an element is positioned in a document
  - **Source:** [MDN CSS Position](https://developer.mozilla.org/en-US/docs/Web/CSS/position)

- [x] What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
  > I have used Bootstrap in the past, but I found that it makes my site look very "generic" now-in-days and takes a while to get the latest CSS features added. I have also fiddled with Material-UI/Emotion with some of my React projects, however since it is mostly a set of UI components, it doesn't offer such a great boost to the development speed as Bootstrap does

- [x] Have you played around with the new CSS Flexbox or Grid specs?
  - **Explanation:**
  > Yes, I have used both flexbox and grid and I use them often when creating a site.
  - **Use:**
  > I find grid useful for setting the outer most layout of a site (because of the ability to use the `fr` measurements) or if I have a design that has elements that "overflow" their original axes. (two-dimensional)
  >
  > Flex is very useful for setting elements in line or aligning elements compared to their siblings. (one-dimensional)
  - **Example:**
  > say you have 5 `<div>`s. If your wrapper is set to flex and wrap, the elements that wrap can be set to grow/shrink to fill in the second row. However, if you set the wrapper to grid, the elements on each row would match the respective columns width.
  - **Source:** [MDN Layout Methods](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Relationship_of_Grid_Layout)

- [x] Can you explain the difference between coding a web site to be responsive versus using a mobile-first strategy?
  - **Explanation:**
  > Note that these two 2 approaches are not exclusive. A mobile-first site always is responsive, but a responsive site isn't always mobile-first.
  >
  > A responsive website is ***reactive*** — the design moving fluidly to fit devices. A mobile-first website is when the mobile website planned and designed in tandem with the desktop site, making ***proactive*** changes to the overall design to ensure the mobile experience is just as good as the desktop experience.
  - **Use:**
  > In responsive, you adapt the elements according to screen size with media queries.
  >
  > With mobile-first, you define all the styles for mobile devices, and only add specific responsive rules to other devices with media queries later.
  - **Example:**
    - Responsive:

    ```css
      @media (min-width: 601px) {
        .my-class {
          font-size: 24px;
        }
      }

      @media (max-width: 600px) {
        .my-class {
          font-size: 12px;
        }
      }
    ```

    - Mobile-first:

    ```css
      .my-class {
        font-size: 12px;
      }

      @media (min-width: 600px) {
        .my-class {
          font-size: 24px;
        }
      }
    ```

  - **Source:** [Final Site](https://www.finalsite.com/blog/p/~board/b/post/rresponsive-vs-mobile-first-difference) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/css-questions#can-you-explain-the-difference-between-coding-a-website-to-be-responsive-versus-using-a-mobile-first-strategy)

- [x] How is responsive design different from adaptive design?
  - **Explanation:**
  > Both responsive and adaptive design attempt to optimize the user experience across different devices.
  - **Use:**
  > Responsive design works on the principle of flexibility - a single fluid website that can look good on any device. Instead of one flexible design, adaptive design detects the device then provides the appropriate feature and layout based on a predefined set of viewport sizes and other characteristics.
  - **Source:** [Adobe Xd](https://xd.adobe.com/ideas/process/ui-design/adaptive-design-vs-responsive-design/) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/css-questions#how-is-responsive-design-different-from-adaptive-design)

- [x] Have you ever worked with retina graphics? If so, when and what techniques did you use?
  - **Explanation:**
  > Retina is just a marketing term to refer to high resolution screens with a pixel ratio bigger than 1. In order to have crisp, good-looking graphics that make the best of retina displays we need to use high resolution images whenever possible. However using highest resolution images will have an impact on page load times.
  - **Use:**
  > To overcome this problem, we can use responsive images, as specified in HTML5 with the srcset attribute.
  - **Example:**

  ```html
  <img
    src="/images/test-1600.jpg"
    srcset="
      /images/test-400.jpg   400w,
      /images/test-800.jpg   800w,
      /images/test-1200.jpg 1200w
    "
  />
  ```

  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/css-questions#have-you-ever-worked-with-retina-graphics-if-so-when-and-what-techniques-did-you-use)

- [x] Is there any reason you'd want to use `translate()` instead of `absolute` positioning, or vice-versa? And why?
  - **Explanation:**
  > `translate()` is a value of CSS `transform`. `transform` causes the browser to create a GPU layer for the element but changing absolute positioning properties uses the CPU. `translate()` would be the more efficient solution with shorter paint times. If you do not want the original space of the element preserved you would want to use `absolute` positioning.
  >
  >When using `translate()`, the element still occupies its original space (sort of like `position: relative`), unlike in changing the absolute positioning.
  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/css-questions#is-there-any-reason-youd-want-to-use-translate-instead-of-absolute-positioning-or-vice-versa-and-why)

---

### Javascript

- [x] Explain event delegation
  - **Explanation:**
  > Event delegation is a technique involving adding event listeners to a parent element instead of adding them to the descendant elements. The listener will fire whenever the event is triggered on the descendant elements due to event bubbling up the DOM.
  - **Use:**
  > The benefits of this technique are:
  >
  > - Memory footprint goes down because only one single handler is needed on the parent element, rather than having to attach event handlers on each descendant.
  > - There is no need to unbind the handler from elements that are removed and to bind the event for new elements.
  >
  - **Example:**
  
  ```html
  <ul id="parent-list">
    <li id="post-1">Item 1</li>
    <li id="post-2">Item 2</li>
    <li id="post-3">Item 3</li>
    <li id="post-4">Item 4</li>
    <li id="post-5">Item 5</li>
    <li id="post-6">Item 6</li>
  </ul>
  ```

  ```javascript
  // Get the element, add a click listener...
  document.getElementById("parent-list").addEventListener("click", function(e) {
    // e.target is the clicked element!
    // If it was a list item
    if(e.target && e.target.nodeName == "LI") {
      // List item found!  Output the ID!
      console.log("List item ", e.target.id.replace("post-", ""), " was clicked!");
    }
  });
  ```

  - **Source:** [David Walsh](https://davidwalsh.name/event-delegate) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#explain-event-delegation)

- [x] Explain how `this` works in JavaScript
  - **Explanation:**
  > A property of an execution context (global, function or eval) that, in non–strict mode, is always a reference to an object and in strict mode can be any value. When inside of a constructor function or class it will reference the object on instantiation.
  - **Use:**
  > It is used to assign properties and values to an object on instantiation.
  - **Example:**
  
  ```javascript
  const test = {
    prop: 42,
    func: function() {
      return this.prop;
    },
  }; 

  console.log(test.func()); // output: 42
  ```

  - **Source:** [MDN this](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this)

- [x] Explain how prototypal inheritance works
  - **Explanation:**
  > All JavaScript objects have a `__proto__` property that is a reference to another object, which is called the object's "prototype". If a property is accessed on an object, but not found the JavaScript engine check's that object prototype. If again it's not found it checks that prototypes prototype on up the chain until it reaches the top of the chain.
  - **Use:**
  > Using it can help reduce redundant code.
  - **Example:**
  > "Calling grandma to borrow her car if you don't have one".
  
  ```javascript
  function Parent() {
    this.name = 'Parent';
  }

  Parent.prototype.greet = function () {
    console.log('Hello from ' + this.name);
  };

  const child = Object.create(Parent.prototype);

  child.cry = function () {
    console.log('waaaaaahhhh!');
  };

  child.cry();
  // waaaaaahhhh!

  child.greet();
  // hello from Parent

  child.constructor;
  // ƒ Parent() {
  //   this.name = 'Parent';
  // }

  child.constructor.name;
  // 'Parent'
  ```

  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#explain-how-prototypal-inheritance-works)

- [x] What do you think of AMD vs CommonJS?
  - **Explanation:**
  > I would actually prefer to use ESM (ECMAScript Modules) due to it's simple syntax and async nature. Historically CommonJS was used in the back end and runs synchronous and AMD was used in the front end and runs asynchronous
  - **Use:**
  >  CJS has been used in node.js for a while, but the current version of node now allows the use of EMS.
  - **Example:**
    - CJS

      ```javascript
      //importing 
      const doSomething = require('./doSomething.js'); 

      //exporting
      module.exports = function doSomething(n) {
        // do something
      }
      ```

    - AMD

    ```javascript
    define(['dep1', 'dep2'], function (dep1, dep2) {
      //Define the module value by returning a value.
      return function () {};
    });
    ```

    -ESM

    ```javascript
    import React from 'react';
    //or
    import {foo, bar} from './myLib';
    ```

  - **Source:** [dev.to](https://dev.to/iggredible/what-the-heck-are-cjs-amd-umd-and-esm-ikm)

- [x] Explain why the following doesn't work as an IIFE: `function foo(){ }();`. What needs to be changed to properly make it an IIFE?
  - **Explanation:**
  > IIFE are Immediately Invoked Function Expressions. The code provided doesn't work because the function is not wrapped in parenthesis.
  >
  >The JavaScript parser reads `function foo(){ }();` as `function foo(){ }` and `();`, where the former is a function declaration and the latter (a pair of parentheses) is an attempt at calling a function but there is no name specified, hence it throws `Uncaught SyntaxError: Unexpected token`
  - **Use:**
  > Using IIFE can help avaoid polluting the global namespace
  - **Example:**

  ```javascript
  (() => {
    // some initiation code
    let firstVariable;
    let secondVariable;
  })();
  ```

  - **Source:** [MDN IIFE](https://developer.mozilla.org/en-US/docs/Glossary/IIFE) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#explain-why-the-following-doesnt-work-as-an-iife-function-foo--what-needs-to-be-changed-to-properly-make-it-an-iife)

- [x] What's the difference between a variable that is: `null`, `undefined` or undeclared? How would you go about checking for any of these states?
  - **Explanation:**
  >
  > - Undeclared variables are created when you assign a value to an identifier that is not previously created using `var`, `let`, or `const`.
  > - `null` have to be explicitly assigned with a `null` value which represets no value.
  > - `undefined` are variables that were declared, but not assigned a value.
  >
  - **Use:**

  > `null` and `undefined` can be checked using strict equality `===.` Undeclared will throw it's own error so you could use try...catch

  - **Example:**
  
    - Undeclared variables

  ```javascript
  function foo() {
    x = 1; // Throws a ReferenceError in strict mode
  }

  foo();
  console.log(x); // 1
  ```

  - `null`

  ```javascript
  let empty = null
  ```

  - `undefined`

  ```javascript
  let empty;
  ```
  >
  - **Source:** [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/null) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#whats-the-difference-between-a-variable-that-is-null-undefined-or-undeclared-how-would-you-go-about-checking-for-any-of-these-states)

- [x] What is a closure, and how/why would you use one?
  - **Explanation:**
  > Closure allows you to use an outer function’s scope (go into a parent, grandparent function, etc.) from within an inner function. In JavaScript a closure is created every time a function is created.
  - **Use:**
  > It allows you to combine data with the function that will operate on that data. It is similar to OOP.
  - **Example:**
  
  ```javascript
  function init() {
  var name = 'Mozilla'; // name is a local variable created by init
  function displayName() {
      // displayName() is the inner function, a closure
      alert(name); // use variable declared in the parent function
    }
    displayName();
  }
  init();
  ```
  
  ```javascript
  function makeAdder(x) {
    return function(y) {
      return x + y;
    };
  }

  var add5 = makeAdder(5);
  var add10 = makeAdder(10);

  console.log(add5(2));  // 7 (y is the 2)
  console.log(add10(2)); // 12 (y is the 2)
  ```

  - **Source:** [MDN Closures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)

- [x] Can you describe the main difference between a `.forEach()` loop and a `.map()` loop and why you would pick one versus the other?
  - **Explanation:**
  > The map method returns a new array by applying the callback function on each element of an array, while the forEach method doesn't return anything
  - **Use:**
  > If you need the result and don't want to mutate the original array, use map. If you only need to iterate over the array then forEach can be used
  - **Example:**

  ```javascript
  let arr = [1, 2, 3, 4, 5];

  //forEach()
  arr.forEach((num, index) => {
      return arr[index] = num * 2;
  });
  console.log(arr) // arr = [2, 4, 6, 8, 10]

  //map()
  let doubled = arr.map(num => {
    return num * 2;
  });
  console.log(doubled) // doubled = [2, 4, 6, 8, 10]
  ```

  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#can-you-describe-the-main-difference-between-a-foreach-loop-and-a-map-loop-and-why-you-would-pick-one-versus-the-other)

- [x] What's a typical use case for anonymous functions?
  - **Explanation / Use:**
  > Anonymous functions are functions without a name. I generally use them for callback functions that do not need to used anywhere else.
  - **Example:**
  > Like inside of an array.map( (num) => num *2) function or with setTimeout.
  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#whats-a-typical-use-case-for-anonymous-functions)

- [x] How do you organize your code? (module pattern, classical inheritance?)
  - **Explanation:**
  > My preference is to use ES6 Modules to organize my code for the following reasons:
  >
  > - Easier to reuse code
  > - Easier to keep code separated leading to...
  > - Easier to maintain
  >
  - **Source:** [Odin Project](https://www.theodinproject.com/lessons/node-path-javascript-es6-modules)

- [x] What's the difference between host objects and native objects?
  - **Explanation:**
  > Native objects are part of the language as defined by ECMAScript specification. Host objects are those provided by the runtime (browser or Node).
  - **Example:**
  > Some native objects are `String`, `Math`, `RegExp`, and `Object`. A couple of host objects are `window` and `console`
  - **Source:** [Stack Overflow](https://stackoverflow.com/questions/7614317/what-is-the-difference-between-native-objects-and-host-objects) | [FE Interview Handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#whats-the-difference-between-host-objects-and-native-objects)

- [x] What is the difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
  - **Explanation:**
    - `function Person(){}` is likely being used as a constructor.
    - `var person = new Person()` is instantiated a new Person object as person.
    - `var person = Person()` is not correct and would likely return undefined. To create a new instance you would need to use the new operator as above.

  - **Example:**

  ```javascript
  function Person(name) {
    this.name = name;
  }

  var person = Person('John');
  console.log(person); // undefined
  console.log(person.name); // Uncaught TypeError: Cannot read property 'name' of undefined

  var person = new Person('John');
  console.log(person); // Person { name: "John" }
  console.log(person.name); // "john"
  ```

  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#difference-between-function-person-var-person--person-and-var-person--new-person)

- [x] What's the difference between `.call()` and `.apply()`?
  - **Explanation:**
  > They are both used to invoke functions the difference is in how they take arguments. .call() takes them as comma-separated values and .apply() takes them as an array.
  - **Example:**

  ```javascript
  function add(a, b) {
    return a + b;
  }

  console.log(add.call(null, 1, 2)); // 3
  console.log(add.apply(null, [1, 2])); // 3
  ```

  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#whats-the-difference-between-call-and-apply)

- [x] Explain `Function.prototype.bind`.
  - **Explanation:**
  > The `bind()` method creates a new function that, when called, has its `this` keyword set to the provided value, with a given sequence of arguments preceding any provided when the new function is called
  - **Use:**
  > For binding the value of `this` in methods of classes that you want to pass into other functions. This is frequently done in React components.
  - **Example:**

  ```javascript
  const module = {
    x: 42,
    getX: function() {
      return this.x;
    }
  };

  const unboundGetX = module.getX;
  console.log(unboundGetX()); // The function gets invoked at the global scope
  // expected output: undefined

  const boundGetX = unboundGetX.bind(module);
  console.log(boundGetX());
  // expected output: 42
  ```

  - **Source:**[MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_objects/Function/bind)

- [x] When would you use `document.write()`?
  - **Explanation:**
  > Use of `document.write()` is strongly discouraged as it's prone to misuse. In the past, some developers used it to add the current year to the footer for the copyright, but I would not use it in a modern day website.
  - **Source:** [MDN](https://developer.mozilla.org/en-US/docs/Web/API/Document/write)

- [x] What's the difference between feature detection, feature inference, and using the UA string?
  - **Explanation:**
    - *Feature Detection*:
    Working out whether a browser supports a certain block of code, and running different code depending on whether it does, so that the browser can provide a working experience rather crashing/erroring in some browsers.
    - *Feature Inference*:
    Checks for a feature just like feature detection, but uses another function because it assumes it will also exist. Not recommended, Feature Detection is the better approach.
    - *UA String*:
    A browser-reported string that allows the network protocol peers to identify various properties of the system. It's tricky to parse and can be spoofed so it's best to avoid this method.

  - **Use:**
  - **Example:**
    - Detection

    ```javascript
    if ('geolocation' in navigator) {
    // Can use navigator.geolocation
    } else {
      // Handle lack of feature
    }
    ```

    - Inference

    ```javascript
    if (document.getElementsByTagName) {
      element = document.getElementById(id);
    }
    ```

    - UA

    ```javascript
    //in console run
    navigator.userAgent
    ```

  - **Source:** [Medium](https://rlynjb.medium.com/js-interview-question-what-s-the-difference-between-feature-detection-feature-inference-and-76d2e4956a9b) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#whats-the-difference-between-feature-detection-feature-inference-and-using-the-ua-string)

- [x] Explain Ajax in as much detail as possible.
  - **Explanation:**
  > Ajax (asynchronous JavaScript and XML) is a set of web development techniques using many web technologies on the client side to create asynchronous web applications. With Ajax, web applications can send data to and retrieve from a server asynchronously (in the background) without interfering with the display and behavior of the existing page.
  - **Use:**
  > By decoupling the data interchange layer from the presentation layer, Ajax allows for web pages, and by extension web applications, to change content dynamically without the need to reload the entire page. In practice, modern implementations commonly use JSON instead of XML, due to the advantages of JSON being native to JavaScript.
  - **Example:**
  > The `XMLHttpRequest` API is frequently used for the asynchronous communication or these days, the `fetch` API.
  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#explain-ajax-in-as-much-detail-as-possible)

- [x] What are the advantages and disadvantages of using Ajax?
  - **Advantages**
    - Better interactivity. New content from the server can be changed dynamically without the need to reload the entire page.
    - Reduce connections to the server since scripts and stylesheets only have to be requested once.
    - State can be maintained on a page. JavaScript variables and DOM state will persist because the main container page was not reloaded.

  - **Disadvantages**
    - Dynamic webpages are harder to bookmark.
    - Does not work if JavaScript has been disabled in the browser.
    - Some webcrawlers do not execute JavaScript and would not see content that has been loaded by JavaScript.
    - JavaScript will have to be parsed and executed on the browser, and low-end mobile devices might struggle with this.

  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#what-are-the-advantages-and-disadvantages-of-using-ajax)

- [x] Explain how JSONP works (and how it's not really Ajax).
  - **Explanation:**
  >JSONP (JSON with Padding) is a method commonly used to bypass the cross-domain policies in web browsers because Ajax requests from the current page to a cross-origin domain is not allowed.
  >
  >When used to describe a data format, "ajax" typically means "xml". JSONP is simply JSON-formatted data wrapped in a callback function.
  - **Use:**
  > JSONP can be unsafe as it can do everything else JavaScript can so you need to trust the provider of data. These days, CORS is the recommended approach and JSONP is seen as a hack.
  - **Example:**

  ```javascript
  <!-- https://mydomain.com -->
  <script>
    function printData(data) {
      console.log(`My name is ${data.name}!`);
    }
  </script>

  <script src="https://example.com?callback=printData"></script>
  ```

  - **Source:** [Stack Overflow](https://stackoverflow.com/questions/7115940/what-is-the-difference-between-ajax-restful-rest-json-and-jsonp) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#explain-how-jsonp-works-and-how-its-not-really-ajax)

- [x] Have you ever used JavaScript templating? If so, what libraries have you used?
  - **Explanation:**
  > Yes, I have used EJS with Node and I'm familiar with the mustache / handlebar libraries.
  - **Example:**
  
  ```ejs
  //ejs
  <% if (user) { %>
    <h2><%= user.name %></h2>
  <% } %>
  ```

  - **Source:** [EJS](https://ejs.co/#docs)

- [x] Explain "hoisting".
  - **Explanation:**
  > Hoisting refers to the process whereby the interpreter appears to move the *declaration* of functions, variables or classes to the top of their scope, prior to execution of the code (NOT initializations).
  - **Use:**
  > This allows functions to be safely used in code before they are declared.
  - **Example:**

  ```javascript
  catName("Tiger");

  function catName(name) {
    console.log("My cat's name is " + name);
  } //output: "My cat's name is Tiger"

  
  console.log(num); // Throws ReferenceError exception as the variable value is uninitialized
  let num = 6; // Initialization
  ```

  - **Source:** [MDN](https://developer.mozilla.org/en-US/docs/Glossary/Hoisting) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions#explain-hoisting)

- [x] Describe event bubbling.
  - **Explanation / Use:**
  > When an event happens on an element, it first runs the handlers on it, then on its parent, then all the way up on other ancestors. The most deeply nested element that caused the event is called a target element, accessible as event.target.
  - **Example:**

  ```html
  <form onclick="alert('form')">FORM
    <div onclick="alert('div')">DIV
      <p onclick="alert('p')">P</p>
    </div>
  </form>
  ```

  A click on the inner `<p>` first runs onclick:

    1. On that `<p>`.
    1. Then on the outer `<div>`.
    1. Then on the outer `<form>`.
    1. And so on upwards till the document object.

  - **Source:** [Javascript Info](https://javascript.info/bubbling-and-capturing)

- [x] What's the difference between an "attribute" and a "property"?
  - **Explanation / Use:**
  > Attributes are defined on the HTML markup but properties are defined on the DOM. An attribute is the initial state when rendered in the DOM. A property is the current state.
  - **Example:**

  ```html
  <input type="text" value="Hello">
  ```

  ```javascript
  const input = document.querySelector('input');
  console.log(input.getAttribute('value')); // Hello
  console.log(input.value); // Hello

  //after changing the value of the text field to 'World!'
  console.log(input.getAttribute('value')); // Hello
  console.log(input.value); // World!
  ```

  - **Source:** [MDN](https://javascript.info/dom-attributes-and-properties) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#whats-the-difference-between-an-attribute-and-a-property)
  
- [x] Why is extending built-in JavaScript objects not a good idea?
  - **Explanation:**
  > Extending a built-in javascript objec means adding properties/functions to its prototype. This is dangerous because if you use multiple libraries who may extend an object with the same method, they could overwrite each other and your code would break.
  - **Use:**
  > The only time you should really extend a javascript object is implementing polyfills, which are your implmenetation for a method that may not be originally available on older browsers.
  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#why-is-extending-built-in-javascript-objects-not-a-good-idea) | [MDN Polyfills](https://developer.mozilla.org/en-US/docs/Glossary/Polyfill)

- [x] Difference between document `load` event and document `DOMContentLoaded` event?
  - **Explanation:**
  > `window`'s `load` event is only fired after the DOM and all dependent resources and assets have loaded.
  >
  > `DOMContentLoaded` event is fired when the initial HTML document has been completely loaded and parsed, without waiting for stylesheets, images, and subframes to finish loading.
  - **Source:** [MDN DOMContentLoaded](https://developer.mozilla.org/en-US/docs/Web/API/Window/DOMContentLoaded_event) | [MDN load](https://developer.mozilla.org/en-US/docs/Web/API/Window/load_event) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#difference-between-document-load-event-and-document-domcontentloaded-event)

- [x] What is the difference between `==` and `===`?
  - **Explanation:**
  > `==` checks for value equality while `===` checks for value and data type equality
  - **Use:**
  > `==` should generally be avoided unless for null or undefined
  - **Example:**
  
  ```javascript
  1 == '1'; // true
  1 == [1]; // true
  1 == true; // true
  0 == ''; // true
  0 == '0'; // true
  0 == false; // true
  ```

  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#what-is-the-difference-between--and-)

- [x] Explain the same-origin policy with regards to JavaScript.
  - **Explanation:**
  > The same-origin policy prevents JavaScript from making requests across domain boundaries.
  - **Use:**
  > An origin is defined as a combination of URI scheme, hostname, and port number. This policy prevents a malicious script on one page from obtaining access to sensitive data on another web page through that page's Document Object Model.
  - **Example:**
  > For example, it prevents a malicious website on the Internet from running JS in a browser to read data from a third-party webmail service
  - **Source:** [MDN](https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#explain-the-same-origin-policy-with-regards-to-javascript)

- [x] Make this work: `duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]`
  - **Explanation:**
  Thanks to ES6, we can use the spread operator.

  ```javascript
  const duplicate = arr => [...arr,...arr]
  ```

  But we can also use the .concat() array method

  ```javascript
  const dupliacte = arr => arr.concat(arr)
  ```

  Both return a new array

  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions/#make-this-work)

- [x] Why is it called a ternary expression, what does the word "ternary" indicate?
  - **Explanation:**
  > "Ternary" indicates three, and it's the only javascript operator that takes 3 operands: The condition, followed by a `?`, the expression if truthy followed by a `:`, and then the expression if falsy.
  - **Use:**
  > Generally used to simplify code instead of an `if...else` statement.
  - **Example:**

  ```javascript
  condition ? exprIfTrue : exprIfFalse
  ```

  - **Source:** [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator)

- [x] What is "use strict";? what are the advantages and disadvantages to using it?
  - **Explanation:**
  > "use strict" is a statement that looks like a string at the top of your script, and is a way to opt into a restricted variant of JavaScript.

  - **Use:**
  > The advantages of using 'use strict' includes making it impossible to accidentally create global variables, requires function parameter names be unique, and catching some common coding bloopers, throwing exceptions. However, by using it some feature are removed that developers might be used to using (like function.caller or function.arguments) and concating multiple scripts written in different script modes may cause issues.
  - **Example:**

  ```javascript
    "use strict";

    // this code works the modern way
    ...
  ```

  - **Source:** [javascript.info](https://javascript.info/strict-mode) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions#what-is-use-strict-what-are-the-advantages-and-disadvantages-to-using-it)

- [x] Create a for loop that iterates up to 100 while outputting "fizz" at multiples of 3, "buzz" at multiples of 5 and "fizzbuzz" at multiples of 3 and 5
  
  ```javascript
    for (let i = 1; i <= 100; i++) {
      let string = '';
      if(!(i%3)) string += 'Fizz'
      if(!(i%5)) string += 'Buzz'

      console.log( string ? string : i)
    }
  ```
  
  - **Source:** Me

- [x] Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?

  - **Explanation:**
  > Every script has access to the global scope, and if everyone uses the global namespace to define their variables, collisions will likely occur. Use the module pattern (IIFEs) to encapsulate your variables within a local namespace.

  - **Source:** [Lucy Bain](https://lucybain.com/blog/2014/js-dont-touch-global-scope/)

- [x] Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?
  - **Explanation:**
  >  `load` fires when the entire page is finished loading (HTML, CSS, images, etc.).
  > `DOMContentLoaded` fires when the DOM is fully loaded, but before external resources like stylesheets are loaded.
  - **Use:**
  > `load` can be useful if you want to appply styling, like image sizes
  > `DOMContentLoaded` can be useful to work with the DOM nodes
  - **Example:**

  ```javascript
  function ready() {
    alert('DOM is ready');

    // image is in the DOM, but not yet loaded (unless it was cached), so the size is 0x0
    alert(`Image size: ${img.offsetWidth}x${img.offsetHeight}`);
  }

  document.addEventListener("DOMContentLoaded", ready);
  ```

  ```html
  <img id="img" src="https://en.js.cx/clipart/train.gif?speed=1&cache=0">
  ```

  - **Source:** [javascript.info](https://javascript.info/onload-ondomcontentloaded)
  
- [x] Explain what a single page app is and how to make one SEO-friendly.
  - **Explanation:**
  > SPA's are a single website that relates with users by updating the existing page with new data, but subsequent changes to the page do not initiate a page refresh. Due to this, SEO web crawlers have a hard time traversing the data since the url does not change. However, recently Google started indexing active pages, so developers need to make sure the javascript files can be indexed for the crawlers to traverse.
  - **Source:** [Monocubed](https://www.monocubed.com/blog/what-is-single-page-application/) | [Geekflare](https://geekflare.com/single-page-applications/)

- [x] What is the extent of your experience with Promises and/or their polyfills?
  - **Explanation:**
  > I've used Promises extensively as they are a main component in modern asynchronous JavaScript.
  > A promise is an object that may produce a single value sometime in the future: either a resolved value or a reason that it's not resolved (e.g., a network error occurred). A promise may be in one of 3 possible states: fulfilled, rejected, or pending.
  > I haven't used polyfills much as they aren't required much these days.

  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions#what-is-the-extent-of-your-experience-with-promises-andor-their-polyfills)

- [x] What are the pros and cons of using Promises instead of callbacks?
  - **Pros:**

    - Avoid callback hell which can be unreadable.
    - Makes it easy to write sequential asynchronous code that is readable with .then().
    - Makes it easy to write parallel asynchronous code with Promise.all().
    - With promises, these scenarios which are present in callbacks-only coding, will not happen:
      - Call the callback too early
      - Call the callback too late (or never)
      - Call the callback too few or too many times
      - Fail to pass along any necessary environment/parameters
      - Swallow any errors/exceptions that may happen
  - **Cons:**

    - Slightly more complex code (debatable).
    - In older browsers where ES2015 is not supported, you need to load a polyfill in order to use it.

  - **Source:** [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions#what-are-the-pros-and-cons-of-using-promises-instead-of-callbacks)

- [x] What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
  - **Explanation:**
  > Using a language like TypeScript to compile to Javascript has a couple of advantages and disadvantages
  - **Pros:**
  > Adding strict types and other elements that make the code more self-expressive (so-called syntactic sugar). This leads to better predictablility - if a variable is defined as a string, it won't change to a boolean. There is also large amounts of support
  - **Cons:**
  >
  > - Another level of javascript to learn types and some TS-specific constructs.
  > - The enhanced code leads to needing to write more code and has the potential of slowing down the development process.
  >
  - **Source:** [altexsoft](https://www.altexsoft.com/blog/typescript-pros-and-cons/) | [FE Interview handbook](https://www.frontendinterviewhandbook.com/javascript-questions#what-are-some-of-the-advantagesdisadvantages-of-writing-javascript-code-in-a-language-that-compiles-to-javascript)
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

---

### Javascript General

- [x] Can you name two programming paradigms important for JavaScript app developers?
  - **Explanation:**
  > The two most common are OOP or Object Oriented Programming (aka Imperative programming) and Functional Programming (aka declarative programming)
  - **Use:**
  > OOP allows prototypal inheritance via different "classes". Functional is pure-functions without side effects.
  - **Example:**

  OOP

  ```javascript
    const John = {
    skills: ["Python", "Javascript", "SQL"],
    age: 22,
    language: "English",
    skilled: function skilled() {
      if (this.skills.length > 2) {
        return "He's got some skills";
      } else {
        return "Fair Enough";
      }
    },
  };
  ```

  Functional

  ```javascript
  function closure() {
    const name = "Carl";
    return function greeting() {
      return "Hello" + name;
    };
  } // return [function greeting]

  ```

  - **Source:** [Medium](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95) | [dev.to](https://dev.to/alamin__yusuf/paradigms-in-javascript-1m31)

- [x] What is functional programming?
  - **Explanation:**
  > Functional programming AKA Declarative programming is a programming pattern centered around writing pure functions, involving closures and lambdas (or fat-arrow functions), to execute some certain task without any side-effects
  - **Use:**
  >  You avoid mutable data and shared states and instead make use of simple functions. It makes the code more predictable.
  - **Example:**

  ```javascript
  // Declarative Programming Example: Using Arrow Function
  const arraySum = array => array.reduce((a, b) => a + b, 0);
  ```

  - **Source:** [Medium](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95) | [dev.to](https://dev.to/alamin__yusuf/paradigms-in-javascript-1m31)

- [x] What is the difference between classical inheritance and prototypal inheritance?
  - **Explanation:**
  > In classical object-oriented programming, there are two types of abstractions: objects and classes. An object is an abstractions of an entity, while a class is either an abstraction of an object or another class.
  >
  > In prototypal object-oriented programming, there's only one type of abstraction: objects. Objects are either abstractions of entities or other objects, in which case they're called prototypes. Hence a prototype is a generalization.Objects can be created out of nothing or from another object, which in turn becomes the prototype of the newly created object.
  - **Example:**
  Classical

  ```javascript
  class Shoe { ... }
  class Boot extends Shoe { ... }
  let hikingShoe = new Boot()
  ```

  Prototypal
  
  ```javascript
  const shoe = {};
  const boot = Object.create(shoe);
  const hikingShoe = Object.create(boot);
  ```

  - **Source:** [30 secs of code](https://www.30secondsofcode.org/articles/s/javascript-classical-vs-prototypal-inheritance) | [Stack Overflow](https://stackoverflow.com/questions/19633762/classical-inheritance-vs-prototypal-inheritance-in-javascript) | [dev.to](https://dev.to/crishanks/classical-vs-prototypal-inheritance-2o5a)

- [x] What are the pros and cons of functional programming vs object-oriented programming?
  - **OOP Pros:**
    - It's easy to understand
    - Uses an imperative style, in which the code is read like a simple set of instructions, just like a computer would read it.
    - Uses loops for iteration
  - **OOP Cons:**
    - hard to maintain objects while increasing the levels of inheritance.
    - Its methods can have side effects and may put an impact on processors.
    - Depends on a shared state, aka objects and behaviours are typically tacked together on the same entity.
    - May lead to unspecified and unexpected results in the sense that a parallel code that would have access to a common resource could do so in a way that produces unspecified results.
  - **Functional Pros:**
    - Using clean/pure and transparent functions leads to reliable results without side effects that deliver and return exactly what you expect.
    - Using clean and transparent functions leads to reliable results without side effects that deliver and return exactly what you expect.
    - Tend to be radically simplified and can easily recompose for improved reusability.
    - Computation that makes use of pure functions can be easy to scale across multiple processors
  - **Functional Cons:**
    - Iterates with recursion
    - Always requires a new object to execute functions, and it takes a lot of memory for executing the applications.
    - Sometimes it may  become illegible due to a very large number of functions compared to OOP.
    - Not as many people are familiar with FP vs OOP.
    - Has a steeper learning curve

  - **Source:** [Medium](https://farida-alv04.medium.com/functional-vs-object-oriented-programming-pros-and-cons-cecfbb4054ca) | [Medium](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95) | [educba](https://www.educba.com/functional-programming-vs-oop/)

- [x] What are two-way data binding and one-way data flow, and how are they different?
  - **Explanation / Use:**
    > One-way data binding (React/Flux) is a situation where information flows in only one direction, so that whenever the data changes in a component, it also updates the view with new data. This makes the variable read-only from the user's perspective
    >
    >Two-way data binding (Angular) is when information flows in both directions, it means any change happens in the view updates the data and any change happens in the data updates the view. This allows the variable to be updated by the user.
  - **Source:** [ReactGo](https://reactgo.com/angular-oneway-vs-twoway-binding/)
  
- [x] What is asynchronous programming, and why is it important in JavaScript?
  - **Explanation:**
  > Asynchronous programming is a type of parallel computer programming that lets functions act separately from the main application, or thread, and it then notifies the thread when the task finishes or potentially fails. Javascript is a single thread
  - **Use:**
  > Often helps reduce or prevent wait times. You would typically choose async programming with loading/downloading data, running longer programs, minimizing idle time, or to show action visually
  - **Example:**
  > A customer making an online purchase might visually see a graphic, logo or message on the screen after entering their credit card information. The logo or screen visual happens while the credit card data corresponds to the database and processes payment.
  - **Source:** [Indeed](https://www.indeed.com/career-advice/career-development/asynchronous-programming) | [BMC](https://www.bmc.com/blogs/asynchronous-programming/)

---

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

---

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

---

## Questions to ask your interviewer

1. How does Bob’s Burgers measure the success of their engineers?
2. What challenges can an engineer come across while working at Bob’s Burgers?
3. Can you explain "thing you read on their engineering blog" and how it affects Bob’s Burgers Engineers?
4. What traits are hard to find in an engineer that Bob’s Burgers would like to have?
5. How is critique given to engineers at Bob’s Burgers?
6. Do you have any questions or concerns about my qualifications?

Here is a helpful list of other reverse interview questions: [https://github.com/viraptor/reverse-interview](https://github.com/viraptor/reverse-interview)

---

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

---

## Resources

- [https://eloquentjavascript.net/](https://eloquentjavascript.net/)
- [https://github.com/getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS)
- [https://github.com/yangshun/front-end-interview-handbook](https://github.com/yangshun/front-end-interview-handbook)
- [https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)
- [https://www.simplilearn.com/node-js-interview-questions-and-answers-article](https://www.simplilearn.com/node-js-interview-questions-and-answers-article)
- [https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678](https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678)
