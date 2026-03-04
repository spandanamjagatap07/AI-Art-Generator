# AI-Art-Generator

This project generates images from **text prompts** using the **Stable Diffusion model** through the Diffusers library.

### Project Overview

* The program installs and loads the **Stable Diffusion v1.5 pretrained model**.
* It detects whether the system has a **GPU (CUDA) or CPU** and runs the model accordingly.
* A **text prompt** is provided to the model to generate an AI-created image.
* The generated image is displayed and saved as an **image file**.

### Technologies Used

* **Python**
* **PyTorch (torch)** – for deep learning computations
* **Diffusers** – for running the Stable Diffusion model
* **Transformers** – for model components
* **Pillow (PIL)** – for image handling
* **Accelerate** – for efficient model execution

### Working Flow

1. Install required libraries such as **diffusers, transformers, accelerate, and torch**.
2. Check whether **CUDA (GPU)** or **CPU** is available.
3. Load the **Stable Diffusion v1.5 pretrained model**.
4. Provide a **text prompt** to the model.
5. Generate an image based on the prompt.
6. Display the generated image and save it as **ai_art.jpg**.

### Output

* AI-generated image is displayed on the screen.
* The image is saved as **ai_art.jpg**.
