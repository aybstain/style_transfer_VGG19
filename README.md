# Neural Style Transfer using TensorFlow

This Python script implements neural style transfer using TensorFlow and a pre-trained VGG19 model. Neural style transfer is a technique that combines the content of one image with the style of another image to create artistic and visually appealing results.

## Overview

Neural style transfer involves the following steps:

1. Load the content and style images.
2. Define the architecture of the VGG19-based style transfer model.
3. Extract features from both the content and style images.
4. Optimize the generated image to match the style and content of the input images.
5. Save the stylized image as the output.

## Dependencies

- TensorFlow (v2.x)
- PIL (Python Imaging Library)
- NumPy

You can install these dependencies using pip:

```
pip install tensorflow pillow numpy
```

## Usage
You can run the style transfer script by providing paths to the content and style images. Here's an example:
```
python style_transfer.py --content /path/to/content_image.jpg --style /path/to/style_image.jpg
```

## Results
The stylized image will be saved with a name specified in the script, along with an epoch number. You can customize the save location and file format as needed.
