# Image Stitching

This code is used to stitch images with overlapping features together. `match.ipynb` uses or and sift feature matching while `stitch.ipynb` uses opencv image stitcher which we used in our pe

## Description

The `match.ipynb` notebook stitches multiple images together to create a single panoramic image. To use this notebook:
1. Place the images you want to stitch in the `unstitchedImages` directory.
2. Run the cells in the `match.ipynb` notebook.
3. The stitched image will be saved in the outputs folder

The `stitch.ipynb` notebook stitches multiple images together to create a single panoramic image. To use this notebook:

1. Place the images you want to stitch in the `unstitchedImages` directory.
2. Run the cells in the `stitch.ipynb` notebook.
3. The stitched image will be saved as `stitchedOutput.png` and `stitchedOutputProcessed.png`.

## Installation

```bash
git clone https://github.com/AadityaGole/VRassignment
```

## Usage

Add the  images with matching features in the unstiched images folder and then run each block 
After running the code, windows will open for confirmation. Press Enter to continue with the code.
