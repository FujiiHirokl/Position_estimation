Trilateration Position Estimation with Random Perturbations
This repository contains a Python script that demonstrates trilateration-based position estimation using random perturbations. Trilateration is a technique used to estimate a point's position in a two-dimensional space based on its distances from three reference points.

Overview
Trilateration is a common technique used in positioning systems, such as GPS. This script illustrates how trilateration works in a simplified scenario. It uses four measurement points located in a 2D plane, where each measurement point has a known position and is associated with a distance value plus a random perturbation. The script then estimates the user's clicked position based on the distances and reference points.

Usage
Clone or download this repository to your local machine.

Make sure you have Python and the required packages installed. You can install the necessary packages using the following command:

Copy code
pip install numpy matplotlib
Run the trilateration.py script using the following command:

Copy code
python trilateration.py
Follow the on-screen instructions. Click on the plot to specify the position you want to estimate. You can exit the loop by right-clicking or pressing 'q'.

Dependencies
NumPy: A library for numerical computations in Python.
Matplotlib: A 2D plotting library for Python.
How It Works
The script sets up the measurement points' coordinates and plots them.

The user clicks on the plot to specify the position they want to estimate.

Random perturbations are added to the distances between the clicked position and the measurement points.

Trilateration is performed four times using different combinations of three reference points and their associated distances.

The estimated positions and distances from the clicked position are displayed for each trilateration calculation.

The plot is updated to show the reference points, estimated positions, clicked position, and circles representing the distances.

The loop continues until the user exits.

License
This project is licensed under the MIT License.

Feel free to customize this README according to your preferences, adding more details or sections if needed.
