# Image_To_Text_Generator_Prj

-Image Captioning with Vision Transformer (ViT) and GPT-2:

This project uses a Vision Transformer (ViT) model paired with a GPT-2 decoder to generate captions for images. It’s designed to be run in Google Colab for easy access to GPU resources and streamlined execution.

-Colab Notebook:

You can run this project directly in Google Colab by clicking the badge below:

<a href="https://colab.research.google.com/github/kaashifatanveer/Image_To_Text_Generator_Prj/blob/main/Image_To_Text_Generator.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

-Features:

Image Preprocessing: Resizes images and converts them to RGB format to ensure compatibility with the model.
Enhanced Caption Generation: Adjustable parameters like max_length and num_beams for fine-tuning caption accuracy.
GPU Acceleration: Leverages Google Colab’s GPU for faster image processing and caption generation.
Setup

-Prerequisites:

A Google account to run the Colab notebook.
No local installations are required; all dependencies are handled within Colab.
Running the Notebook

Click on the "Open In Colab" badge above.
Once the notebook is open in Colab, follow the instructions to run each cell sequentially.
Upload your images to the Colab environment when prompted.
Run the prediction cells to generate captions for your images.
Example Outputs

Input Image: An image of an airplane in the sky.
Generated Caption: "A large jetliner flying through a blue sky"

Input Image: An image of a cat and dog sitting together.
Generated Caption: "A cat and a dog sitting on the floor"

-Customization:

max_length: Adjust the maximum length of the generated captions to get more descriptive outputs.
num_beams: Modify the number of beams used in the beam search to enhance the exploration of possible captions.
Contributing

Contributions are welcome! If you have ideas for improving the model or the notebook, please submit a pull request or open an issue.

-License:

This project is licensed under the MIT License - see the LICENSE file for details.

-Acknowledgments:

Hugging Face Transformers: https://huggingface.co/transformers/
ViT-GPT2 Image Captioning Model: https://huggingface.co/nlpconnect/vit-gpt2-image-captioning
