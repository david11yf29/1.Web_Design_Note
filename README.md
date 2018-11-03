# Web Design Basics

## 0. Web Design Elements
This is the Jonas' udemy course that I had took for the beginner, and the instructor already listed all the items and resources we will use throught the process.

[Everything you need for web](http://codingheroes.io/resources/ )

[Build Responsive Real World Websites with HTML5 and CSS3](https://www.udemy.com/design-and-develop-a-killer-website-with-html5-and-css3/)


## 1. CSS Position Properties
1. static: <br/>
Is the default value.
Div's are block elements by default.

2. relative: <br/>
An element's new position relative to its normal position.
P.S. It doesn't affect other elements' positions.

3. absolute: <br/>
Absolute positioned element is relative to its parent. Is removed from the normal document flow. It is positioned automatically to the starting point(top-left corner) of its parent element. If it doesn't have any parent elements, <html> will be its parent. Other elements are affected and behave as the element is removed completely from the webpage.

4. fixed: <br/>
Like postion: absolute, fixed positioned elements are also removed from the normal document flow.
They are only relative to the <html> document, not any other parents.
They are not affected by scrolling.

5. Sticky: <br/>
Sticky can be explained as a mix of position: relative and position: fixed.
It behaves until a declated point like position: relative, after that is changes its behavior to position: fixed. 
P.S. Tool bar for the website usually uses sticky, and is not supported in Internet Explorer and earlier version of Edge.

[Article from Medium](https://medium.freecodecamp.org/how-to-use-the-position-property-in-css-to-align-elements-d8f49c403a26)

## 2. Counterpart of the float
.clearfix:after {
  content: "";
  display: table;
  clear: both;
}

[CSS-clear](https://css-tricks.com/almanac/properties/c/clear/)

## 3. normalize.css
- Preserves useful defaults, unlike many CSS resets.
- Normalizes styles for a wide range of elements.
- Corrects bugs and common browser inconsistencies.
- Improves usability with subtle modifications.
- Explains what code does using detailed comments.

[normalize.css](https://github.com/necolas/normalize.css)

## 4. border-sizing

[w3s](https://www.w3schools.com/cssref/css3_pr_box-sizing.asp)

## 5. text-rendering

提昇易讀性
<br/>
[MDN](https://developer.mozilla.org/zh-CN/docs/Web/CSS/text-rendering)

## 6. grid

Split columns up to 12.
<br/>
P.S. Just download through this folder
<br/>
[Responsive Grid System](http://www.responsivegridsystem.com/)

## 7. transform

The translate() method moves an element from its current position (according to the parameters given for the X-axis and the Y-axis).
<br/>
[w3s](https://www.w3schools.com/css/css3_2dtransforms.asp)

## 8. Color Palettes
Color examples
<br/>
[Flat UI Colors](https://flatuicolors.com/)
<br/>
[0to255](http://www.0to255.com/)








