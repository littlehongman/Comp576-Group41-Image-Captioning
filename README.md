# Project Files Overview

### cleaning.ipynb
- **Description**: A Jupyter notebook containing scripts and methodologies for cleaning and preprocessing text data for model training.

### Amazon_cleaned.csv
- **Description**: This CSV file contains text data preprocessed and cleaned. Since the image data is too large to store in Github, we stored the image data in an Amazon S3 bucket.

### ConvNext_GPT2.ipynb
- **Description**: A Jupyter notebook featuring an encoder-decoder model setup that integrates ConvNext as the encoder and GPT-2 as the decoder for generating image captions.

### ConvNext_OPT.ipynb
- **Description**: A Jupyter notebook featuring an encoder-decoder model setup that integrates ConvNext as the encoder and OPT as the decoder for generating image captions.

### ViT_GPT2.ipynb
- **Description**: A Jupyter notebook featuring an encoder-decoder model setup that integrates Vision Transformer (ViT) as the encoder and GPT-2 as the decoder for generating image captions.

### selected_images.zip
- **Description**: A compressed zip file containing a collection of images from Amazon.com. These images are selected to evaluate the model's proficiency in generating captions for data not seen during the training and validation phases. It is also used to compare the abilities of different encoder-decoder models.
