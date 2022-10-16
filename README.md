# Training-on-Identify-Clothes

Developed a program that classifies different images into predicted categories with high accuracy through training. Established on
MiniPlaces Dataset and utilized CNN. Testing prediction correctness is above 90%.

## Dataset
MiniPlaces is a scene recognition dataset developed by MIT. This dataset has 120K images from 100 scene cate- gories. The categories are mutually exclusive. The dataset is split into 100K images for training, 10K images for validation, and 10K for testing.

## Resolution
The original image resolution for images in MiniPlaces is 128x128. To make the training feasible, our data loader reduces the image resolution to 32x32. You can always assume this input resolution.

<img width="937" alt="Screen Shot 2022-10-15 at 22 10 30" src="https://user-images.githubusercontent.com/112918739/196016129-f3ea3022-29a1-46a4-81e6-71ef98900360.png">
