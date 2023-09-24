# Skin Color Extraction and Dominant Color Detection

This Python project focuses on extracting skin color from an image using color thresholding techniques and identifying the dominant colors present in the skin region. It can be a valuable tool for various applications, such as skin tone analysis, image processing, and more.

![Example Image](https://github.com/abdul-rehman18/Skin-Color-Extraction-and-Dominant-Color-Detection-Using-K-Means-Clustering-and-opencv/blob/master/download.png)

## How it Works

1. **Face Detection**: The project begins by detecting faces in the input image using a Haar Cascade Classifier.

2. **Skin Color Extraction**: After detecting faces, the skin color is extracted from each face region using the HSV color space and predefined color thresholds. This step isolates the skin pixels.

3. **Dominant Color Detection**: The dominant colors in the skin region are detected using K-Means clustering. You can specify the number of dominant colors to extract.

4. **Color Presentation**: The project provides information about the dominant colors, including their RGB values and the percentage of their occurrence in the skin region. It also displays a color bar representing the dominant colors.

## Usage

- You can use this project to analyze skin tones in images for various applications, such as beauty and skincare products, makeup color matching, and dermatological research.

- Customize the number of dominant colors to extract based on your specific requirements.

## Installation

1. Clone the repository to your local machine.

   ```shell
   git clone https://github.com/your-username/skin-color-extraction.git
   ```

2. Navigate to the project directory.

   ```shell
   cd skin-color-extraction
   ```



3. Run the notebook.

   ```shell
   python Skin_Color_Detection.ipynb
   ```

## Configuration

- You can modify the color threshold values and other parameters in the `extractSkin` function to fine-tune skin color extraction.


## Acknowledgments

- This project uses the OpenCV library for image processing.
- K-Means clustering is implemented using scikit-learn.
- Color information is extracted using the webcolors library.

## Author

- [Abdul Rehman Nadeem](https://github.com/abdul-rehman18)
