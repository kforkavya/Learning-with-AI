# Learning-with-AI

# AI Projects Showcase

## 1. Tactical Brilliance: Tic-Tac-Toe AI with Minimax Algorithm

### Overview

Embark on a strategic journey with our Tic-Tac-Toe AI, a masterpiece driven by the Minimax algorithm. This sophisticated decision-making strategy optimizes each move, skillfully minimizing potential losses and maximizing victories. As the AI navigates through diverse game states, it strategically selects its next move, creating an immersive and challenging experience for players.

### Running the AI

The actual program is written in **JavaScript**. But it has been provided...

---

## 2. Visions Unleashed: Image Captioning with Deep Learning

### Overview

Dive into the captivating world of computer vision with our Image Captioning project. Harnessing the power of deep learning, this AI crafts vivid and descriptive captions for images, leveraging a fusion of Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks. Trained on the expansive Flickr8k dataset, the models showcase an intricate understanding of visual content.

### Using the Image Captioning AI

1. **Download the Dataset:** Secure the [Flickr8k dataset](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip) and [text annotations](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip). Extract and organize these files in the 'Flickr8k' folder within the project directory.

2. **Load Pre-trained Models and Tokenizer:** Initiate by loading pre-trained models and the tokenizer into your environment...

3. **Preprocess the Input Image:** Ensure your input image is properly formatted for the AI model. This involves resizing, normalizing, and preparing the image for feature extraction.

4. **Generate Caption for an Image:** Employ the loaded models to generate a descriptive caption for the input image. The CNN extracts meaningful features from the image, preserving spatial hierarchy and essential details...

Review the code snippets in `Image_Captioning.ipynb`. The final model is saved in `final_model.h5`, and compelling results are displayed in `results.png`.

---

## 3. Artistry in Pixels: MNIST GAN for Handwritten Digits

### Overview

Immerse yourself in the creation of lifelike handwritten digits with our MNIST GAN project. The GAN architecture, housing a generator and discriminator, collaborates to produce synthetic images mirroring real digits from the MNIST dataset.

### Dual-Framework Symphony

To showcase adaptability, we harness the capabilities of both PyTorch and TensorFlow...

### Workflow

1. **Dataset Loading:** Load and preprocess the MNIST dataset, comprised of 28x28 grayscale images representing digits 0 through 9.

2. **Model Definition:**
   - *Generator:* Crafts synthetic images.
   - *Discriminator:* Distinguishes between real and synthetic images.

3. **Training Loop:**
   - Iterative adversarial training for generator and discriminator enhancement...
   - Dynamically observe improvements in image generation quality.

4. **Visualization:**
   - Visualize generated images to assess GAN performance...
   - Compare PyTorch and TensorFlow outputs for insights into framework-specific nuances.

### Framework Forte

- **PyTorch:**
  - Dynamic computation graph...
  - Intuitive interface suitable for research applications.

- **TensorFlow:**
  - Static computation graph...
  - Widely adopted in production settings.

This dual-framework approach provides a comprehensive understanding of GAN implementation, catering to both research-oriented and production-focused deep learning environments.
