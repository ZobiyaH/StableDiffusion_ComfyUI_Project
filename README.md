# StableDiffusion_ComfyUI_Project
A project on Image Generation using Stable Diffusion and ComfyUI.
# StableDiffusion_ComfyUI_Project

## Project Overview
This project demonstrates the use of **Stable Diffusion** with **ComfyUI** for AI-powered image generation. It provides a user-friendly interface to generate high-quality images from textual prompts using diffusion models.

## Features
- **Text-to-Image Generation**: Convert text descriptions into stunning AI-generated images.
- **ComfyUI Interface**: A modular and easy-to-use UI for experimentation.
- **Customizable Parameters**: Adjust diffusion settings for optimal results.
- **High-Resolution Output**: Generate images with fine details and clarity.

## Installation
### Prerequisites
- Python 3.8+
- Git
- NVIDIA GPU (Recommended for faster inference)

### Steps
```bash
# Clone the repository
git clone https://github.com/yourusername/StableDiffusion_ComfyUI_Project.git
cd StableDiffusion_ComfyUI_Project

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Usage
### Running the ComfyUI Interface
```bash
python launch_comfyui.py
```
Access the interface via `http://localhost:5000` in your web browser.

### Generating an Image
1. Open the ComfyUI interface.
2. Enter your text prompt.
3. Adjust diffusion settings if needed.
4. Click on **Generate** to create an image.
5. Save your output from the results panel.

## Directory Structure
```
StableDiffusion_ComfyUI_Project/
│-- models/            # Pre-trained models
│-- outputs/           # Generated images
│-- scripts/           # Helper scripts
│-- launch_comfyui.py  # UI launcher
│-- requirements.txt   # Dependencies
│-- README.md          # Project documentation
```

## Results
![Sample Image]("C:\Users\sarfa\Downloads\internship comfyui\ComfyUI_00001_.png")

## Future Work
- Enhancing UI features for better user control.
- Implementing real-time image generation.
- Optimizing diffusion steps for faster results.



## Contact
For queries, reach out to **Zobiya Hussain** at [hussainzobiya27@gmail.com](mailto:hussainzobiya27@gmail.com).
