# Image-Captioning

Please refer to Jason Brownlee's GITHUB link to Download Flickr_8k dataset

Flickr8k_Dataset.zip https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip

Flickr8k_text.zip https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip

Download both these zips, extract them and save them in the Flickr8k folder in our project folder.

## Using the Image Captioning AI

1. **Load Pre-trained Models and Tokenizer:** Start by loading pre-trained models and the tokenizer into your environment. The Convolutional Neural Network (CNN) is employed for feature extraction, capturing hierarchical and abstract features from the input image. These features are then fed into a Long Short-Term Memory (LSTM) network, a type of recurrent neural network (RNN), for generating sequential and contextually rich captions.

2. **Preprocess the Input Image:** Ensure your input image is properly formatted for the AI model. This involves resizing, normalizing, and preparing the image for feature extraction.

3. **Generate Caption for an Image:** Utilize the loaded models to generate a descriptive caption for the input image. The CNN extracts meaningful features from the image, preserving spatial hierarchy and important details. These features are then passed to the LSTM, which, through sequential processing, generates coherent and contextually relevant captions. The LSTM excels at handling variable-length sequences, allowing it to adapt to diverse lengths of generated captions for different images.

Adjust the provided code snippets according to your specific environment and use case. This process highlights the collaborative role of CNN and LSTM in understanding visual content and generating human-like captions.

The code snippets are in ```Image_Captioning.ipynb```.

The final model has been saved in ```final_model.h5```.

And some of the impressive results can be seen in ```results.png```.
