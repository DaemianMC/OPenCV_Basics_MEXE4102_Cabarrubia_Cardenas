# OPenCV_Basics_MEXE4102_Cabarrubia_Cardenas

# Sorting Objects by Colors

## Introduction
This project demonstrates a method to sort objects by color using the OpenCV library. The program processes images, isolates specific colors, and highlights them for analysis or further processing.

---

## Abstract
The project explores a step-by-step procedure for programming a system to sort objects based on their color. It utilizes the HSV (Hue, Saturation, Value) color space, which simplifies the detection and isolation of specific colors in images compared to the RGB model. The results are displayed visually, showcasing the original image, the mask for the target color, and the final processed result.

---

## Project Methods
Follow the step-by-step procedure below to implement the project:

- **Choose a Dataset**:
   - Select a dataset suitable for the OpenCV task (e.g., images with distinguishable color objects).

- **Set Up the Environment**:
   - Open Google Colab or your preferred Python IDE.

- **Import Required Libraries**:
   - Import essential libraries: `cv2`, `os`, `numpy`, and `matplotlib.pyplot`.

- **Clone the Repository**:
   - Clone the GitHub repository containing the dataset and supporting files.

- **Define the Dataset Folder**:
   - Use the path method to specify the dataset folder location.

- **Define Color Range**:
   - Specify the HSV range for the target color.

- **Kernel for Morphological Operations**:
   - Define a kernel to apply noise reduction techniques.

- **Process Images**:
   - Iterate through all images in the dataset folder:
     - **Check File Extensions**: Ensure the files are valid image formats (e.g., `.jpg`, `.png`).
     - **Resize and Blur**: Adjust image size and apply Gaussian blur for preprocessing.
     - **Convert to HSV**: Transform the image from RGB to HSV color space.
     - **Create a Mask**: Generate a mask based on the defined HSV color range.
     - **Highlight Colors**: Combine the mask with the original image to isolate the target color.

- **Display Results**:
   - Visualize intermediate steps and final outputs using `matplotlib`:
     - **Step 1:** Original Image.
     - **Step 2:** Mask (Grayscale).
     - **Step 3:** Final Processed Result.

---

## Conclusion

### Findings
- The code effectively detects specific colors in images by converting them to the HSV color space. This approach makes it easier to isolate colors compared to RGB.
- Preprocessing steps like resizing and applying a Gaussian blur significantly improve the quality of the results by reducing noise and ensuring consistency across images.
- The pipeline generates clear visual outputs, making the detection process transparent and easy to follow.

### Challenges
- **Tuning the Color Range:** Adjusting the HSV range for different lighting conditions or datasets can be tricky and time-intensive.
- **Dataset Variations:** Variability in image quality, resolution, and lighting can impact detection accuracy.
- **Performance:** Processing high-resolution images or large datasets can be computationally expensive.
- **Mask Precision:** Noise in the generated mask can lead to inaccuracies, especially when colors in the object and background overlap.

### Outcome
- The code successfully isolates and highlights specific colors in images, making it a powerful tool for tasks like object detection or segmentation.
- The visual outputs (original image, mask, and final result) provide an intuitive way to verify that the color detection is working as intended.
- Overall, this code is a solid foundation for building more advanced color detection systems and can be easily adapted to other use cases with minor adjustments.

---
