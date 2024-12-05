# GJK Algorithm for Convex Shape Intersection and Distance Calculation

This project implements the GJK (Gilbert-Johnson-Keerthi) algorithm for detecting intersections and calculating distances between convex shapes such as polygons and circles. Two Jupyter notebooks are included: gjk_2D.ipynb for intersection detection and gjk_distance.ipynb for distance calculation.

## HOW TO USE gjk_2D.ipynb:

This notebook allows you to check intersections between convex shapes. Supported shape pairs include:

Two polygons
1. A circle and a square
2. A circle and a polygon
3. A square and a polygon

Steps:
 - Run the notebook.
 - Follow the on-screen prompts to input the required shape parameters.

### Input
```bash
Enter the x and y coordinates of the circle's center: 100 100
Enter the radius of the circle: 50
Enter the number of points in the polygon: 4

Enter x and y coordinates separated by space: 
0 0
150 0
150 200
0 200
```
### Output
```bash
Circle and Polygon intersect
```

## HOW TO USE gjk_distance.ipynb:

This notebook calculates the minimum distance between two convex shapes using the GJK algorithm.

Steps:
 - Run the notebook.
 - Enter the coordinates of the shapes as prompted.

### Input
```bash
Triangle Points:
(1, 1)
(2, 3)
(3, 1)

Square Points:
(4, 1)
(6, 1)
(6, 3)
(4, 3)
```
### Output
```bash
The distance between the triangle and the square is 3.16 units.
```

## Features
 - Supports multiple convex shape pairs.
 - Easy-to-follow user prompts.
 - Visualization of shape interactions and distances.
 - Accurate calculations using the robust GJK algorithm.

## Contribution

Feel free to contribute by:
  - Reporting issues.
  - Suggesting new features.
  - Submitting pull requests.
For significant changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

Special thanks to the open-source community for inspiring and providing the tools needed to develop this project.
