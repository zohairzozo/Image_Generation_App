# AI Image Generation App
This is a simple web-based application that generates AI-based images from text prompts using Hugging Face's Diffusers library with the Stable Diffusion model. The app is built using Streamlit for the front-end interface and Hugging Face Diffusers for the image generation backend.

## Features
- Home Page: Provides an introduction to the app and its functionality.
- Image Generation: Enter a text prompt and generate an image using Hugging Face Diffusers with the Stable Diffusion model.

## Tech Stack
- Streamlit: A fast and simple framework for building web apps in Python.
- Hugging Face Diffusers: A library for running diffusion models like Stable Diffusion.
- PyTorch: A deep learning library for tensor computations and GPU acceleration.

## Setup Instructions

1. Clone the repository
2. Install the required libraries
3. Set up Environment Variables
4. Run the application: streamlit run app.py
5. Model Download: The code uses Stable Diffusion v1.5 model, which will be automatically downloaded from Hugging Face the first time you run the app. You will need access to a GPU to generate images efficiently.

## How it Works
***Input***: Enter a text prompt into the input box.
***Generate***: When you click the "Generate Image" button, the app sends the prompt to the Stable Diffusion model, which generates an image based on your text.
***Output***: The generated image is displayed on the screen along with a success message.
