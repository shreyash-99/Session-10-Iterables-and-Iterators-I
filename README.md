### Task
To convert the polygon sequence into an iterable.

### How did i do?
1. Added an iter function to the class polygons in the [file](polygons.py) which returns an object of class PolygonIterator
2. create a PolygonIterator class inside it which defines iter and next functions inside to the next element in the polygons sequence.
3. Stop Iteration error is raised when the iterator has done iterating over all the elements in the polygons list.