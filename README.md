# OPenCV_Basics_MEXE4102_Cabarrubia_Cardenas

# Sorting Objects by Colors
#### The chosen [dataset](https://github.com/DaemianMC/OPenCV_Basics_MEXE4102_Cabarrubia_Cardenas/tree/main/Dataset) contains images of cubes in a conveyor belt.

## Introduction
<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This project focuses on Isolating Objects by Color, particularly by applying the HSV thresholding code to extract and display objects of specific colors from an image. With that, the members have narrowed down the problem into Detecting/Isolating all Yellow-Colored Cubes on Conveyer Belt. This topic is highly relevant in computer vision applications such as automated sorting systems, quality control in manufacturing, and robotic vision. It indicates the practical application of color-based object detection for improvement in the efficiency and accuracy of industrial processes. The yellow cubes identified by this project show how computer vision can be used to automate activities that have been time-consuming and error-prone when done manually.
</p>

---

## Abstract
<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The project aims to isolate and display objects based on their color by applying HSV thresholding, with a specific focus on detecting and isolating yellow-colored cubes on a conveyor belt. To achieve this, the memebers selects a dataset containing images with distinguishable yellow-colored objects and sets up the environment using Jupyter Notebook in Google Colab or a preferred IDE. Essential libraries such as OpenCV, NumPy, and Matplotlib are employed, and supporting files are sourced from a GitHub repository. Preprocessing steps, including resizing and Gaussian blurring, ensure consistency and noise reduction across images. Images are converted from RGB to HSV color space to facilitate precise color segmentation. Using a defined HSV range for yellow, a mask is created to isolate target regions, and morphological operations are applied to refine the results. Finally, the pipeline visualizes each step, from the original image to the final processed output, for transparency and analysis. The expected outcome is an accurate and robust detection system that isolates yellow-colored cubes, producing high-quality visual outputs even under variable lighting conditions. This approach demonstrates the effectiveness of HSV thresholding for color-based object detection, providing clear insights into its potential for industrial automation and computer vision applications.
</p>

---

## Project Methods
Follow the step-by-step procedure below to implement the project:

- **Choose a Dataset**:
   - Select a dataset suitable for the OpenCV task (e.g., images with distinguishable color objects).

- **Set Up the Environment**:
   - Open Google Colab or Jupyter Notebook.

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

## Additional Materials
- The code is provided in this repository with the file name OPenCV_Basics_MEXE4102_Cabarrubia_Cardenas - 8.ipynb
- The following images are the results of this project

![image](https://github.com/user-attachments/assets/86a120de-e5ac-49b2-b8fd-2ad82bfd1eaf)
![image](https://github.com/user-attachments/assets/e8647f46-22ba-484c-991f-0485e16a514a)
![image](https://github.com/user-attachments/assets/344c8af5-2082-439c-af43-293952c90a76)
![image](https://github.com/user-attachments/assets/ef15ca61-075e-4f43-b572-c2c34d4f9f40)
![image](https://github.com/user-attachments/assets/4edaa440-4105-42bd-aa2d-6608f6a35e4e)
![image](https://github.com/user-attachments/assets/558b8d1a-1060-4fb5-8062-43426a2521e3)
![image](https://github.com/user-attachments/assets/faee282c-4950-4fbb-b17a-ddb01633b37c)
![image](https://github.com/user-attachments/assets/902f8f10-da4f-47e6-ba9a-c20004662e4b)
![image](https://github.com/user-attachments/assets/e144e98e-2b4e-41c7-8bdc-b90b75b93244)
![image](https://github.com/user-attachments/assets/9ea1cdd7-d906-402e-b17e-4dc60b059fe0)
![image](https://github.com/user-attachments/assets/99025dff-8e21-44fc-aa28-c81acb29c442)
![image](https://github.com/user-attachments/assets/004f9284-b478-4407-8c99-dc3c83b9e65e)
![image](https://github.com/user-attachments/assets/3d27d88c-8bd5-4373-9bf8-75b5ebed349f)
![image](https://github.com/user-attachments/assets/e5b5f4cf-c56f-48d7-a699-0c606cce2aaf)
![image](https://github.com/user-attachments/assets/27c67f73-a9ab-4828-85a9-856a076eac71)

---

## Members
- Cabarrubia, Yuel Jeiro Daemian
- Cardenas, Sofia Bianca
---
