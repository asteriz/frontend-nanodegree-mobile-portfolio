## Website Performance Optimization portfolio project

#### How to run
Using a browser to open the index.html. That's all.

#### Part 1: Optimize PageSpeed Insights score for index.html
- Add media property to print.css
- Load analytics.js async
- Change pizzeria.jpg to pizzeria_c.jpg which is only 100px width
- Delete inlined style which inside tag
- Inline the content of style.css
- Move google font css to the bottom and it will not block any other content from rendering

#### Part 2: Optimize Frames per Second in pizza.html
- Set randomPizzaContainer width directly by using percentage
- Change documnent.querySelectorAll(".randomPizzaContainer") to document.getElementsByClassName("randomPizzaContainer") and move them outside the loop
- Change documnent.querySelectorAll(".mover") to document.getElementsByClassName("mover")
- Generate all phase values before loop mover
- Change the listener of document content loaded to the listener of window load
- Move document.querySelector("#movingPizzas1") outside the loop
- Generate sliding pizzas depends on the height of the screen, insdead of the fixed 200 ones

[Optimized Website](https://asteriz.github.io/frontend-nanodegree-mobile-portfolio/)