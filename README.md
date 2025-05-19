This project focuses on performing kinematic analysis to simulate realistic finger movements of a humanoid robot hand. 
By applying concepts from forward kinematics and using homogeneous transformation matrices, 
the project models the motion of finger joints, particularly analyzing the movement of the MCP (Metacarpophalangeal) joint.
🗓️ Project Timeline
Completed in: May 2024

✨ Features
Mathematical modeling of finger joint rotation using homogeneous transformation matrices.
Simulation of end-effector (fingertip) positions based on input joint angles.
Visual representation of fingertip position in the X-Z plane.
User-friendly input and visualization using Python and Matplotlib.

📌 Technologies Used
Python – For simulation, visualization, and user interaction.
MATLAB – For initial kinematic model prototyping and verification.

📐 Kinematics Concept
This project uses forward kinematics to compute the position of a fingertip given an input angle for the MCP joint. 
The transformation is based on rotation about the Y-axis using a homogeneous transformation matrix.

🧮 Code Overview
def calculate_fingertip_position(theta1_deg):
    # Converts the MCP joint angle into a transformation matrix and computes the fingertip position

Takes user input for MCP joint angle between 0° and 90°.
Computes the homogeneous transformation matrix for rotation about the Y-axis.
Calculates the 3D coordinates of the fingertip.
Visualizes the fingertip position in the X-Z plane

📸 Sample Output
A plot is generated showing the position of the fingertip (end effector) in the X-Z plane based on the input rotation angle.

▶️ Getting Started
Run the Code
python joe.ipynb
