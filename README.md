# 🖼️✨ Image Caption Generator
<img width="976" height="372" alt="image" src="https://github.com/user-attachments/assets/807476ca-5519-48a3-be0b-6ef8af5c2c77" />


🚀 Overview

The Image Caption Generator is a Deep Learning project that combines Computer Vision and Natural Language Processing (NLP) to automatically generate meaningful captions for images.
It uses a CNN + LSTM architecture to understand image features and generate natural language sentences.


🔥 Features

✅ Generates human-like captions for images
✅ Uses Transfer Learning (InceptionV3 / ResNet50) for feature extraction
✅ Sequence modeling with LSTM / GRU
✅ Works on Flickr8k
✅ Extensible for custom datasets


📂 Project Structure
├── Image Caption Generator.ipynb   # Main Notebook
├── dataset/                        # Images + Captions dataset
├── models/                         # Trained model weights
├── assets/                         # Images for README
└── requirements.txt                # Dependencies


🛠️ Tech Stack

Python 3 🐍

TensorFlow / Keras 🤖

OpenCV 📷

NLTK / Text Processing 📝

Matplotlib / Seaborn 📊


📊 Dataset

We trained and tested the model on:

Flickr8k Dataset


📸 Example:
| Image                    | Caption                                    |
| ------------------------ | ------------------------------------------ |
| <img width="127" height="128" alt="image" src="https://github.com/user-attachments/assets/b1563242-7315-4761-859f-3ea4cbcc9f3f" />  | *"A hockey player in blue and red guarding the goal."*   |
   | *"A hockey player in blue and red guarding the goal."*   |
| <img width="125" height="124" alt="image" src="https://github.com/user-attachments/assets/757ae1ed-01bb-4155-884e-9d2552f64850" />
 | *"Two dogs play in the grass."* |


🤖 Model Architecture

<img width="909" height="482" alt="image" src="https://github.com/user-attachments/assets/5710a006-58c7-42f4-80f0-3fa85e7f6ec4" />


Feature Extraction → Pre-trained CNN (InceptionV3/ResNet50)

Caption Processing → Tokenization, Padding, Embedding

Sequence Generator → LSTM network for word generation

Beam Search / Greedy Search for final caption


⚡ Installation
# Clone this repository
git clone https://github.com/your-username/image-caption-generator.git
cd image-caption-generator

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook "Image Caption Generator.ipynb"


🚀 Future Improvements

Use Transformer-based models (ViT + GPT2/BLIP2)

Deploy as a Flask/Streamlit Web App

Optimize with Beam Search for better captions

🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss.

📜 License

This project is licensed under the MIT License.

✨ Developed with ❤️ by Gautam Giri
