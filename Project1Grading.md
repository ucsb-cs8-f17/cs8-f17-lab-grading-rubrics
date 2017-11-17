# Rubrics
* Correct syntax(autograded): (10 pts)
* Overall style and structure:(5 pts)  

        * Top down design approach - modular implementation 2
        * Values are not hardcoded (2 pts)
	
	* contains "if __name__ == "__main__":" statement (1 pt)
		* If they don't call functions from main function
		* If they didn't call drawScene() from main function
Based on drawing uploaded to gauchospace
* Produced expected output for trees (20 pts, partial credit 10 points)
* Produced expected output for hut  (20 pts, partial credit 10 points)
* Drawing is cluttered (5pts)
* Used the random module appropriately (10)  ( 5 pts for tree and 5 pts for hut)

* Function specific rubrics:
	* drawTree(height, color):  (5 pts)
		* Draws the tree of the right size(width and height not hardcoded) 
		* Specifies the color of the rectangle in tree as brown. At least the color of rectangle should be hard-coded.
		* The color of triangles is correct(color is same as the parameter and not hard coded)
	* drawForest():  (5 pts )
		* Used random numbers to draw a row of trees placed randomly along a row (random numbers are generated  by package instead of being selected by hand and hard-coded)
	* drawHut():  ( 5 pts )
		* Draws huts only using rectangles
		* Sets the size of huts fixed
		* Uses random number to randomize the bottom of the hut, by changing the number of rectangles or the spacing between each rectangle.
		* Uses random number to randomize the top of the hut, by changing the length of each rectangle
	* drawVillage(): (5 pts)
		* Draws village using drawHut()
		* Draws a sequence of five huts
		* Places huts randomly along a horizontal line


* Extra credit: (10pts)
	* This is extra work. Any non-trivial work would be fine. The standard of non-trivial is totally up to whoever grades homework
	Trivial : 2 pts
	Medium:     5 pts
	Spectacular: 10 ots



