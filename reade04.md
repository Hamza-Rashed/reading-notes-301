# CSS Grid Layout 
excels at dividing a page into major regions or defining the relationship in terms of size, 
position, and layer, between parts of a control built from HTML primitives.

Like tables, grid layout enables an author to align elements into columns and rows. However, many more layouts
are either possible or easier with CSS grid than they were with tables. For example, a grid container's child 
elements could position themselves so they actually overlap and layer, similar to CSS positioned elements.
Basic example

The example below shows a three-column track grid with new rows created at a minimum of 100 pixels and a maximum of auto. 
Items have been placed onto the grid using line-based placement.
HTML
```
<div class="wrapper">
  <div class="one">One</div>
  <div class="two">Two</div>
  <div class="three">Three</div>
  <div class="four">Four</div>
  <div class="five">Five</div>
  <div class="six">Six</div>
</div>

CSS

.wrapper {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 10px;
  grid-auto-rows: minmax(100px, auto);
}
.one {
  grid-column: 1 / 3;
  grid-row: 1;
}
.two { 
  grid-column: 2 / 4;
  grid-row: 1 / 3;
}
.three {
  grid-column: 1;
  grid-row: 2 / 5;
}
.four {
  grid-column: 3;
  grid-row: 3;
}
.five {
  grid-column: 2;
  grid-row: 4;
}
.six {
  grid-column: 3;
  grid-row: 4;
}
```
![](https://cdn.mos.cms.futurecdn.net/7vpUPMSbPfhxiUNYj5XnE6.jpg)

# RegEx :
A regular expression (shortened as regex or regexp;[1] also referred to as rational expression[2][3]) is a sequence of characters that define a search pattern. Usually such patterns are used by string-searching algorithms for "find" or "find and replace" operations on strings, or for input validation. It is a technique developed in theoretical computer science and formal language theory. 

Using a regular expression literal, which consists of a pattern enclosed between slashes, as follows:

``` let re = /ab+c/; ```

Regular expression literals provide compilation of the regular expression when the script is loaded. If the regular expression remains constant, using this can improve performance.

Or calling the constructor function of the RegExp object, as follows:

  ``` let re = new RegExp('ab+c'); ```

Using the constructor function provides runtime compilation of the regular expression. Use the constructor function when you know the regular expression pattern will be changing, or you don't know the pattern and are getting it from another source, such as user input.

![](https://i.ytimg.com/vi/paOPoZyjzdg/maxresdefault.jpg)

# Responsive Web Design ;

Responsive web design (RWD) is a website design approach that recommends building a single website that adapts to all devices and platforms. This avoids the duplication of effort involved in building separate desktop and mobile websites. A website built to RWD principles uses floating content elements, an adjustable page layout, and dynamically resized images to accommodate various viewport sizes and device capabilities. In other words, the site responds to the user's requirements.

The Magnolia Standard Templating Kit (STK) implements the RWD principles. A website built with the STK can deliver a browsing experience that works well on desktop browsers, smartphones, tablets and other types of clients. In this article we look at how the RWD technology is built into the system.

![](https://miro.medium.com/max/3468/1*qF8LfAwUhl57g9T0BVvVdg.jpeg)
