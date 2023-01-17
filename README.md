# Multi-Image-Input-CNN-Preprocessing 🖼️+🖼️ = 🖼️
<a href="https://colab.research.google.com/github/dilne/Multi-Image-Input-CNN-Preprocessing/blob/main/NotebookAndGuide.ipynb" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Summary
This notebook tutorial demonstrates how to preprocess image data for inputting multiple images into a CNN. It provides easy-to-use code for preparing your images for multi-image input in a CNN and includes a detailed walkthrough of the process.

## How It Works
The easiest way to input multiple images into a CNN is to merge their channels. In this example, we use two images of a cat and two images of a dog, taken from different angles (front and side). Each image has a width, height, and number of channels (e.g 512, 512, 3). We can use the images in greyscale or RGB format.

For merging two RGB images, we convert them into one six channel image. For greyscale images, we convert two one channel images into one two channel image. The resulting images are not easily viewable, so this notebook also includes instructions for viewing the images after preprocessing.

To use this notebook, simply open it, configure the "Variables for editing" section, and run the code. This will guide you through the process of preprocessing your images for multi-image input in a CNN.

![A Dog and Cat - Front and Side](https://user-images.githubusercontent.com/50206336/212647027-2dba4f5b-fae7-43f7-b8cc-f64b5bb79b97.png)
