# Train-Problems
Python Trains Problems test. 


You must picture a graph. Use the following links for ideas. https://www.tutorialspoint.com/python/python_graphs.htm  or https://www.python-course.eu/graphs_python.php


Many towns in Kiwiland use a railroad service and they need information about the routes. 

The edge represent the distance between 2 towns.
A node respresents a town. 

When there is no such route exists from input 1 through 5, the output should be "NO SUCH Route."



Things to keep in mind:
1. The distance of the route A-B-C.
2. The distance of the route A-D.
3. The distance of the route A-D-C.
4. The distance of the route A-E-B-C-D.
5. The distance of the route A-E-D.
6. The number of trips starting at C and ending at C with a maximum of 3
stops.  In the sample data below, there are two such trips: C-D-C (2
stops). and C-E-B-C (3 stops).
7. The number of trips starting at A and ending at C with exactly 4 stops.
In the sample data below, there are three such trips: A to C (via B,C,D); A
to C (via D,C,D); and A to C (via D,E,B).
8. The length of the shortest route (in terms of distance to travel) from A
to C.
9. The length of the shortest route (in terms of distance to travel) from B
to B.
10. The number of different routes from C to C with a distance of less than 30.
In the sample data, the trips are: CDC, CEBC, CEBCDC, CDCEBC, CDEBC,
CEBCEBC, CEBCEBCEBC.

Test Input:

For the test input, the towns are named using the first few letters of the alphabet from A to D.  A route between two towns (A to B) with a distance of 5 is represented as AB5.

Graph: AB5, BC4, CD8, DC8, DE6, AD5, CE2, EB3, AE7
