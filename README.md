Download Link: https://assignmentchef.com/product/solved-itse-2317-program-2-twodimensionalshape
<br>
Implement the Shape hierarchy shown in the diagram below.  Each TwoDimensionalShape should contain method getArea to calculate the area of the two-dimensional shape. Each ThreeDimensionalShape should have methods getArea and getVolume to calculate the surface area and volume, respectively, of the three-dimensional shape. Create a program that uses an array of Shape references to objects of each concrete class in the hierarchy.

The program should print a text description of the object to which each array element refers. Also, in the loop that processes all the shapes in the array, determine whether each shape is a TwoDimensionalShape or a ThreeDimensionalShape. If it’s a TwoDimensionalShape, display its area.  If it’s a ThreeDimensionalShape, display its area and volume.




Run your program and copy and paste the output to a file.  Create a folder named, <strong>fullname_program2</strong>.  Copy your source code and the output file to the folder.  Zip the folder and upload it to Blackboard.




<strong>Test Data </strong>

Edge      ..     2.5

Length   ..     2.5

Radius   ..     5.75

Base      ..     7.95

Height    ..    10.33










<strong>Shape Hierarchy </strong>




This hierarchy begins with the superclass, <strong>Shape</strong>, which is extended by two subclasses, <strong>TwoDimensionalShape</strong> and <strong>ThreeDimensionalShape</strong>.  In geometry, Shapes are either two dimensional or three dimensional. The third level of this hierarchy contains specific types of two dimensional shapes and three dimensional shapes.  You can follow the arrows from the bottom of the diagram to the topmost superclass in this class hierarchy to identify several <em>is-a</em> relationships. For instance, a Triangle <em>is a</em> TwoDimensionalShape and <em>is a</em> Shape, while a Sphere is a ThreeDimensionalShape and is a Shape.