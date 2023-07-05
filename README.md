# Horizontal-Velocity-Using-MPU6050_Accelerometers
Formula to Get Horizontal Velocity Using Acceleration Sensor MPU 6050 Arduino IDE

In Formula Horizontal Velocity using example for kinematic equations of motion and graphical methods. then compare the value of the initial horizontal velocity to the expected value by measuring its speed directly.

where in theory :

1. Using the kinematic equations derive an expression for the range R of the projectile in terms of Vo (initial horizontal velocity), g (acceleration of gravity), and h (height of launch of ball).  Have instructor check equation before continuing.
2. The derived equation for the range R should be directly proportional to the square root of the heighth.  That is hkR= where k is the proportionality constant which you can deduce from the derived equation for R. The constant k involves the initial velocity Vo and g.
3. If you graph the equation hkR= with R on the vertical axis and hon the horizontal axis you will obtain a linear curve where the slope of the curve equals k.

----------------------------------->

<h1>Acceleration with Motion</h1>

To determine the acceleration in a given motion scenario, typically need to know at least two of the following quantities:

Initial velocity (u): The velocity of the object at the start of the motion.
Final velocity (v): The velocity of the object at the end of the motion.
Time taken (t): The duration of the motion.
Once have two of these values, can use the appropriate formula to calculate the acceleration:

If know the initial velocity (u), final velocity (v), and time taken (t):

Acceleration (a) = (v - u) / t

If the initial velocity (u), final velocity (v), and distance (s) covered:

Acceleration (a) = (v^2 - u^2) / (2s)

If the initial velocity (u), acceleration (a), and time taken (t):

Final velocity (v) = u + (a * t)

If the final velocity (v), acceleration (a), and time taken (t):

Initial velocity (u) = v - (a * t)

----------->
<h2>Theory for Acceleration with Motion</h2>

Acceleration is defined as the rate of change of velocity with respect to time. In other words, it measures how quickly an object's velocity is changing over a given time interval. Acceleration is a vector quantity, which means it has both magnitude and direction.

The standard unit of acceleration is meters per second squared (m/s²) in the International System of Units (SI). When an object undergoes acceleration, its velocity changes either by increasing or decreasing in magnitude or by changing its direction.

There are three main types of acceleration:

Positive Acceleration: When the velocity of an object increases over time, the acceleration is positive. For example, when a car speeds up or a bicycle gains momentum, their accelerations are positive.

Negative Acceleration (Deceleration): When the velocity of an object decreases over time, the acceleration is negative. Negative acceleration is often referred to as deceleration or retardation. It represents slowing down or going in the opposite direction. For example, when a car slows down or a train comes to a stop, their accelerations are negative.

Changing Direction: Acceleration can also occur when the velocity of an object changes its direction while maintaining a constant speed. In this case, the acceleration is perpendicular to the direction of motion, towards the center of the circular path. This type of acceleration is called centripetal acceleration and is responsible for keeping objects in circular motion.

When dealing with uniform acceleration, where the acceleration remains constant, the equations of motion can be applied. The four primary equations of motion that relate acceleration, velocity, displacement, and time are:

v = u + at
This equation relates the final velocity (v) of an object to its initial velocity (u), acceleration (a), and time (t) taken. It shows how the velocity changes over time when the acceleration is constant.

s = ut + (1/2)at²
This equation relates the displacement (s) of an object to its initial velocity (u), acceleration (a), and time (t) taken. It calculates the distance traveled by the object under constant acceleration.

v² = u² + 2as
This equation relates the final velocity (v) squared to the initial velocity (u) squared, acceleration (a), and displacement (s) of an object. It provides a relationship between velocity, displacement, and acceleration.

s = ((u + v)/2) * t
This equation relates the displacement (s) of an object to its initial velocity (u), final velocity (v), and time (t) taken. It calculates the average displacement over time based on the initial and final velocities.

These equations can be rearranged and combined to solve for different unknowns in various motion problems involving acceleration.

Source by :
1. OpenStax College Physics: This free, open-access physics textbook offers a comprehensive introduction to various physics topics, including motion, acceleration, and the equations of motion. You can access it online at: https://openstax.org/details/books/college-physics
2. Khan Academy Physics: Khan Academy offers an extensive collection of video lessons, practice exercises, and articles covering physics topics, including motion, acceleration, and the equations of motion. You can access their physics resources at: https://www.khanacademy.org/science/physics
