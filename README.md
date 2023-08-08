# Trilateration Position Estimation with Random Perturbations

This repository contains a Python script that demonstrates trilateration-based position estimation using random perturbations. Trilateration is a technique used to estimate a point's position in a two-dimensional space based on its distances from three reference points.

## Overview

Trilateration is a common technique used in positioning systems, such as GPS. This script illustrates how trilateration works in a simplified scenario. It uses four measurement points located in a 2D plane, where each measurement point has a known position and is associated with a distance value plus a random perturbation. The script then estimates the user's clicked position based on the distances and reference points.

## Usage

1. **Clone or Download**: Clone or download this repository to your local machine.

2. **Install Dependencies**: Make sure you have Python and the required packages installed. You can install the necessary packages using the following command:

pip install numpy matplotlib


3. **Run the Script**: Run the `trilateration.py` script using the following command:

python trilateration.py


4. **Follow Instructions**: Follow the on-screen instructions. Click on the plot to specify the position you want to estimate. You can exit the loop by right-clicking or pressing 'q'.

## Dependencies

- [NumPy](https://numpy.org/): A library for numerical computations in Python.
- [Matplotlib](https://matplotlib.org/): A 2D plotting library for Python.

## How It Works

1. The script sets up the measurement points' coordinates and plots them.

2. The user clicks on the plot to specify the position they want to estimate.

3. Random perturbations are added to the distances between the clicked position and the measurement points.

4. Trilateration is performed four times using different combinations of three reference points and their associated distances.

5. The estimated positions and distances from the clicked position are displayed for each trilateration calculation.

6. The plot is updated to show the reference points, estimated positions, clicked position, and circles representing the distances.

7. The loop continues until the user exits.

## License

This project is licensed under the [MIT License](LICENSE).

