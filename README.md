Birefringence Calculation from Image

This repository contains a Python script that extracts RGB values from selected points in an image and calculates birefringence values using interpolation based on the Michel-Levy chart.

Features

Load an image and manually select three points.

Extract RGB values from the selected points.

Interpolate birefringence values based on a predefined Michel-Levy chart dataset.

Displays calculated birefringence values.


Installation

Ensure you have the following dependencies installed:

pip install opencv-python numpy scikit-image scipy

Usage

1. Update the image_path variable in the script with the path to your image.


2. Run the script:

python Birefringence_code.py


3. Click on three points in the image to select color regions.


4. The script will display the RGB values and their corresponding birefringence values.



Example Output

Selected RGB Values: [(235, 77, 9), (187, 58, 4), (118, 95, 56)]
Calculated Birefringence Values: [0.0549, 0.0428, 0.0406]
Point 1: RGB: (235, 77, 9), Birefringence: 0.0549
Point 2: RGB: (187, 58, 4), Birefringence: 0.0428
Point 3: RGB: (118, 95, 56), Birefringence: 0.0406

License

This project is licensed under the Apache-2.0 License. See the LICENSE file for details.

Author: BhupendraNNU
If you use this work, please credit the author.
