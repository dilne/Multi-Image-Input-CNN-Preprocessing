# Multi-Image-Input-CNN-Preprocessing 🖼️🖼️ = 🖼️
<a href="https://colab.research.google.com/github/dilne/Multi-Image-Input-CNN-Preprocessing/blob/main/NotebookAndGuide.ipynb" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Summary
Notebook tutorial demonstrating how to preprocess image data for multiple image input into a CNN

Sometimes, you want multiple images as input to a CNN. This notebook contains easy to use code for preprocessing your images for multi-image input for a CNN. Just configure the "Variables for editing" section and run. This notebook will also provide a detailed walkthrough of what you need to know when using multiple images as input to a CNN.

## How It Works
The simplest way to use multiple images as input to a CNN is to merge their channels. In this example, we have two images of a cat and two images of a dog. The two cat images are of the same cat taken from the front and side and the dog images are of the same dog taken from the front and side. Each image has a width, height, and channels (e.g 512, 512, 3).

We can take the images as greyscale or RGB. For merging two RGB images, we convert two three channel images into one six channel image. Greyscale is simpler; we convert two one channel images into one two channel image. These images can't be viewed (not clearly at least) in their current state, so this notebook demonstrates how to view the images after preprocessing, as well as how the preprocessing is performed.
