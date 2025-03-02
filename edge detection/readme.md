# Coin Counting Using Edge Detection

## Project Overview
This project demonstrates a workflow for detecting and counting coins in an image using OpenCV. The project includes two Jupyter notebooks: one for stitching multiple images together and another for detecting and counting coins in a single image.

## Installation
To run the notebooks, you need to install the following dependencies:

```sh
pip install numpy
pip install opencv-python
pip install imutils
```

Clone the repository:

```sh
git clone https://github.com/AadityaGole/VRassignment
```

## Counting Coins
The `counting.ipynb` notebook detects and counts coins in a single image. To use this notebook:

1. Place the image you want to analyze as `coin.jpg`.
2. Run the cells in the `counting.ipynb` notebook.
3. The notebook will display the detected coins and save each segmented coin as `coin_1.png`, `coin_2.png`, etc.
4. The total number of detected coins will be printed in the terminal.

## Usage
add the image in the same root folder as the notebook and then replace coin.jpg with the name of your pic
After running the code, a window will open for confirmation. Press Enter to continue with the code.
