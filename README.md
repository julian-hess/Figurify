## Explanation

Figurify is a Python library that allows you to perform various calculations related to geometric figures. With Figurify, you can quickly and easily calculate properties such as perimeter, area, angles, and more for various geometric shapes.

## Installation

You can easily install Figurify using pip:

    pip install figurify

## Supported Calculations

    material_properties
    units

Geometric Solids

    Cube
    Cuboid
    Cylinder
    Cone
    Sphere
    Torus
    Prism
    Pyramid

Plane Metrics

    Circle
    Rectangle
    Triangle
    Square
    Trapezoid
    Polygon
    Ellipse
    Parallelogram
    Quadrilateral

Figure Physics

    Dynamics
    Forces
    Energy
    Gravity
    Kinematics
    Momentum  

And there are many functions in every Python file.<br>
For more information about the available functions and figures, see the documentation.

## Bugs

We welcome contributions from other developers! If you've found a bug or want to add a new feature, feel free to create an issue or submit a pull request.<br>

## License

This project is licensed under the MIT License. See the license file for more information.


## Usage

Here's a simple example of how to use Figurify in your Python project:

```python
import figurify

print(figurify.material_properties.volume(20, 1.4),
      figurify.units.cubic_centimetres)

print(figurify.plane_metrics.circle.area(5))
print(figurify.plane_metrics.circle.radius(2.5))

print(figurify.plane_metrics.trapezoid.area(2, 4, 8))
print(figurify.plane_metrics.trapezoid.height(20, 2, 4))

print(figurify.geometric_solids.cube.volume(5), figurify.units.cubic_centimetres)

area = figurify.plane_metrics.parallelogram.area(5, 10)

print(figurify.units.square_cm_to_square_dm(area), figurify.units.square_decimetres)

# And there's much more, see above.