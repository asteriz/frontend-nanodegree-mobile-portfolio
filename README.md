## Website Performance Optimization portfolio project

#### Part 1: Optimize PageSpeed Insights score for index.html
- Add media property to print.css
- Load analytics.js async
- Change pizzeria.jpg to pizzeria_c.jpg which is only 100px width
- Delete inlined style

#### Part 2: Optimize Frames per Second in pizza.html
- Set randomPizzaContainer width directly by using percentage
- Change documnent.querySelectorAll(".randomPizzaContainer") to document.getElementsByClassName("randomPizzaContainer") and move them outside the loop
- Change documnent.querySelectorAll(".mover") to document.getElementsByClassName("mover")
- Generate all phase values before loop mover
- Change the listener of document content loaded to the listener of window load
- Move document.querySelector("#movingPizzas1") outside the loop
- Generate only 48 sliding pizzas insdead of 200 ones

[Optimized Website](https://asteriz.github.io/frontend-nanodegree-mobile-portfolio/)