# Robotic Arm Simulator
This project is an interactive robotic arm simulator that allows you to visualize and control a three-link robotic arm using Python, Numpy, Matplotlib, and IPyWidgets. The simulator displays the position of the robotic arm's joints and the end effector in a 2D plot based on input angles, and provides an interactive way to move the robotic arm by clicking on the plot.

 ### Features:

 * 2D visualization of a robotic arm with three joints (A, B, C) and an end effector (D).
* User interaction: click on the plot to move the end effector (D) to the desired position, simulating robotic arm movement.
* Real-time update of the robotic arm positions as you click on the plot.
* Calculates and displays a table of detailed information about the angles, positions, and the changes in angles for each click.

### Libraries:

* Numpy: Used for array manipulations, mathematical calculations, and angle conversions.
* Matplotlib: Used for generating the 2D plot and visualizing the robotic arm.
* IPyWidgets: Provides an interactive output widget to display a table of information about the angles, positions, and angle changes.
* IPython.display: Used to display the table widget in the notebook.

### How it works:

1. The code initializes the 2D plot and the table widget for displaying information.
2. It sets up the initial positions of the joints and the end effector using the given angles.
3. The plot_robotic_arm() function is used to draw the robotic arm based on input angles.
4. The on_click() function handles click events on the plot and calculates the new positions of the joints and the end effector.
5. The new angles, positions, and angle changes are added to the table widget for each click.
6. The on_click() function also updates the plot in real-time, showing the new positions of the joints and the end effector.

Use this project to learn more about robotics, inverse kinematics, and visualization using Python.
