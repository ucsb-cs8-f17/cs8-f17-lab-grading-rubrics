# Rubrics
* Correct syntax(autograded): (10 pts)
* Code is correctly structured:(10 pts)
	* contains import statements (5 pts)
	* contains "if __name__ == "__main__":" statement (5 pts)
		* If they don't call functions from main function, deduct 2 points
* Produced expected output for trees (20 pts, partial credit 10 points)
* Produced expected output for hut  (20 pts, partial credit 10 points)

* Function specific rubrics:
	* drawTree():  (20 pts, 5 pts for each specification)
		* Draws the tree of the right size(width and height not hardcoded) 
		* Specifies the color of the rectangle in tree as brown
		* Draws the top with three triangles
		* The color of triangles is correct(color is same as the parameter and not hard coded)
	* drawForest():  (15 pts, 5 pts for each specification)
		* Draws more or less 10 trees instead of a single tree
		* Used random numbers to draw a row of trees with different shades of green (random numbers are generated  by package instead of being selected by hand and hard-coded)
		* Used random numbers to draw a row of trees placed randomly along a row (random numbers are generated  by package instead of being selected by hand and hard-coded)
	* drawHut():  (20 pts, 5 pts for each specification)
		* Draws huts only using rectangles
		* Sets the color of huts as brown
		* Sets the size of huts fixed
		* Uses random package to introduce randomness in the number of rectangles in each huts
	* drawVillage(): (15 pts, 5 pts for each specification)
		* Draws village using drawHut()
		* Draws a sequence of five huts
		* Places huts randomly along a horizontal line
	* drawScene(): (10 pts)
		* This is extra work. Any non-trivial work would be fine. The standard of non-trivial is totally up to whoever grades homework


* Coding style: Just feedback
