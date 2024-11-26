# Images_Captioning

This project demonstrates image captioning using a combination of Vision Transformer (ViT) for image feature extraction and GPT-2 for text generation. The model leverages the pre-trained nlpconnect/vit-gpt2-image-captioning model, which is fine-tuned to generate descriptive captions for input images.

Features:
Image Processing: The project uses the ViT (Vision Transformer) model to extract visual features from input images.
Text Generation: The GPT-2 model generates captions from the visual features, transforming them into coherent, human-readable text.
Support for Multiple Images: The model can generate captions for multiple images in a single run.
Customizable Caption Length: The caption length can be adjusted via the max_length parameter.
Beam Search: Uses beam search decoding for more accurate and diverse caption generation.
Requirements:
Python 3.x
PyTorch
Hugging Face transformers library
Pillow (for image processing)
Matplotlib (for displaying images)
