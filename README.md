# Fall2025.Topics
Topics we are going to cover in class each day. Links to [example student videos ](https://www.youtube.com/playlist?list=PLH9qo0GKu2iSlchbSeksN18S87gMIjHOg) and [slides from class](https://uofnebraska-my.sharepoint.com/:f:/g/personal/17816140_nebraska_edu/EktuKJi3m_9Khf6sZLG_lrkBc46ZoPAOI6gCk86_xmf0sQ?e=sRqveC)

# Day 03, September 3 (Lecture)

## Announcements
- Sprints start in 10 days

## Review
- What is a game loop?
- What is a vector?


# Day 02, August 27 (Lecture)
## Announcements
- No class on Monday due to Labor Day

## Review
- What is the difference between the Box Model, SVG, and Canvas?
- What is the difference between the JS keyword `let` and `const`?

## Syllabus

## What is a computer game?
- In this class, a game is an enjoyable, interactive, visual simulation.
- How are we going to learn game programming?
  - Learn the math
  - Learn the architecture
  - Practice

## Repeated rendering (Visual)
- requestAnimationFrame
  - Additional information at https://developer.mozilla.org/en-US/docs/Web/API/Window/requestAnimationFrame, https://www.w3schools.com/jsref/met_win_requestanimationframe.asp

## Updating our game (Interactive)
- MVC (Architecture)
- gameLoop formalization (Architecture)
  - Additional information at https://m-abdullah-ramees0916.medium.com/the-game-loop-f6f5cb68c00, 




## Vectors (Math)
- What is a vector
  - Additional information at https://en.wikipedia.org/wiki/Vector_(mathematics_and_physics)
- Adding Vectors
  - Additional information at https://mathworld.wolfram.com/VectorAddition.html

## Physics (Math/Simulation)
- Velocity
  - Additional information https://en.wikipedia.org/wiki/Velocity


## Classes in JS
- classes in JS
  - Additional information at https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes, https://www.w3schools.com/js/js_classes.asp
- constructors in JS
  - Additional information at https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/constructor, https://www.w3schools.com/jsref/jsref_constructor_class.asp
- class functions in JS
- field in JS
  - Additional information at https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/Public_class_fields

## To Think About
- Why is creative mode in Minecraft considered a game while a painting app is not?

## Final Code
- Combining classes, vectors, and our original code, we arrive at our [Day 02 Code](https://github.com/CS2510/Fall2025.Day02.GameLoop).

## Ideas to explore on your own
- Can you change the code to make all the vertices of the triangle to have their own independent velocity?
  - Can you make the above change using arrays so that you don't need new variables for each vertex?

# Day 01, August 25th (Lecture)
## Macro view of methods of drawing 

- Box Model
    - ![NY Times Cover for Pearl Harbor](https://www.nypl.org/scout/_next/image?url=https%3A%2F%2Fdrupal.nypl.org%2Fsites-drupal%2Fdefault%2Ffiles%2Fstyles%2Fmax_width_960%2Fpublic%2Fblogs%2Ff55b9a989d12b3c172d3510da17478ad.png%3Fitok%3DB3nyQ1YD&w=1920&q=90)
    - Addition information at https://www.w3schools.com/css/css_boxmodel.asp, https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Box_model
- SVG
    - Additional information at https://developer.mozilla.org/en-US/docs/Web/SVG/Guides/SVG_in_HTML, https://www.w3schools.com/graphics/svg_intro.asp
- Canvas
    - Additional information at https://www.w3schools.com/html/html5_canvas.asp, https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API

## What we won't be doing in class
- Images (Including emoji)
- Sounds

## New JS concepts

- Structure of an HTML document
  - doctype
  - html
  - head
  - body
  - script
  - Example code at https://github.com/CS2510/Fall2025.Day01.Introduction/blob/main/00_html_structure.html
  - Additional information at https://www.w3schools.com/html/html_intro.asp

- Access elements in JS
  - Additional information at https://www.w3schools.com/jsref/met_document_queryselector.asp

- Declaring variables in JS
  - let and const
  - Example code in [this file](./JS.html)
  - Additional information at https://www.geeksforgeeks.org/javascript/difference-between-var-let-and-const-keywords-in-javascript/

## Methods of drawing specific to canvas
- Showing color
  - See slides: 3 Ways to show Color
  - Additional information at https://www.w3schools.com/html/html_colors.asp
- Paths
  - Additional information at https://www.w3resource.com/html5-canvas/html5-canvas-path.php
- Polygons
- Rectangles
- Arcs
    - Introduction to radians
- Text
  - See slides: Fonts
  - Additional information at https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text, https://www.w3schools.com/graphics/canvas_text.asp
- Example code at https://github.com/CS2510/Fall2025.Day01.Introduction/blob/main/01_basic_drawing.html



## In class work
- Take what we have learned about drawing and draw something more advanced.
- ![Mickey Mouse Head](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRb5ejW-uLTRXHprPAMrWZUOFD1nWv7xpnvYw&s)
- [Batman Logos](https://flowingdata.com/2012/12/24/evolution-of-batman-logo-1940-2012/)

## Ideas to explore on your own
- Block out a game you enjoy using the basic drawing tools we use in class
- Example code at https://github.com/CS2510/Fall2025.Day01.Introduction/blob/main/02_blocking_a_game.html, https://github.com/CS2510/Fall2025.Day01.Introduction/blob/main/03_blocking_a_game_2.html

