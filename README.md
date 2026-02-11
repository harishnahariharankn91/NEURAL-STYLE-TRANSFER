# NEURAL-STYLE-TRANSFER

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: HARISHNA H

*INTERN ID*: CTIS5325

*DOMAIN*: ARTIFICIAL INTELLIGENCE

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

Task Description: NEURAL-STYLE-TRANSFER
The objective of this task is to design and implement a Neural Style Transfer (NST) system that applies artistic styles from one image onto another image using deep learning techniques. The system combines the content of a photograph with the artistic style of a painting to generate a new stylized image.

The project is developed using Python and implemented with PyTorch and Torchvision libraries. A pre-trained Convolutional Neural Network (VGG19 model) is used to extract high-level features from both the content image and the style image. The model analyzes:

Content features (structure and objects in the image)

Style features (textures, patterns, colors)

Neural Style Transfer works by optimizing a generated image so that it simultaneously:

Preserves the content of the original photograph.

Adopts the artistic style of the reference painting.

The system calculates:

Content Loss – Measures similarity between generated image and content image.

Style Loss – Uses Gram Matrix to measure texture similarity.

Total Loss – Combination of content and style loss.

During execution, the model iteratively updates the generated image using backpropagation and optimization techniques until the desired artistic transformation is achieved.

The final output is a stylized image that visually blends:

The structure of the content image

The artistic patterns of the style image
