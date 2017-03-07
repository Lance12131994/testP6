#Website Optimization
You can broswer the page <code>pizza.html</code> at less than 60fps and the page  <code>index.html</code>  has get not less tha 90 scores on the PageSpeedInsights.
  
#Installation
Open the file <code>index.html</code> in the browser,and then click the link <code>Cam's Pizzeria</code> to broswer <code>pizza.html</code>.

#Optimization
In <code>index.html</code> ,I made some changes like these:
- use local resources to instead the web fonts resources
- add media quries to the CSS file <code>print.css</code> 
- inline critical CSS files <code>style.css</code> 
- Compress the orginal images and update them
In <code>main.js</code> ,I made some changes like these:
- use variable to restore some results of repeated caculation
- reduce circulation times by reducing the number controlling the circulation
- use getElementByClassName() to get elements whose classname is <code>.move</code>
- restore the array document.getElementsByClassName("randomPizzaContainer") returns in the variable  <code>randomPizzaContainer</code>
- restore the element document.getElementById("movingPizzas1") returns in the variable  <code>movingPizzas1</code>
- move the variable <code>pissasDiv</code> out the for statements
- adjust the value of cols by screen height and width
