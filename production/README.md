## Website Performance Optimization portfolio project

####Part 1: Optimize PageSpeed Insights score for index.html
1. Minified images
2. Load google analytics and google font script asynchronously
3. Inline CSS


####Part 2: Optimize Frames per Second in pizza.html
#####Changes made to achieve 60 fps
1.	Renamed misnamed adjectives noise to noisy
2.	Use getelementsbyclassname instead of queryselector for mover
3.	Cache the current y-axis value of the top position of the page
4.	Create new variable to calculate half of window width
5.	Cache constant number - number of pizzas on screen
6.	Change for loop count in updateposition function to decrement
7.	Bring document.body.scrolltop; out of for loop and caching it
8.	Create a variable to calculate how much to move left
9.	Applied translate3d() transform functions to for loop within the updatePositions function.
10.	Reduced the amount of background pizzas to display on screen from 200 down to 35 to fill the sufficiently screen
11.	Change for loop count in function that generates the sliding pizzas when page loads to decrement
	

#####Changes made to reduce time to resize pizza
1.	Moved dx and newwidth variables out of for loop -  giving constant number
2.	Created a new variable to  select all divs with randompizzacontainer divs
3.	Created a new variable for the number of randompizzacontainer  
4.	Decrement count in for loop inside changepizzasizes function
 
Time to resize pizzas: 1.0100000000093132ms

