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


# Install dependencies
pip install -r requirements.txt
```


## **1. Download and Set Up ComfyUI**

### **Step 1: Clone the ComfyUI Repository**
Open a terminal and run:
```sh
git clone https://github.com/comfyanonymous/ComfyUI.git
cd ComfyUI
```

### **Step 2: Install Dependencies**
Ensure you have **Python 3.8+** installed, then install the required packages:
```sh
pip install -r requirements.txt
```

---

## **2. Download Stable Diffusion Model Checkpoints**

### **Step 3: Get a Stable Diffusion Model**
Download a Stable Diffusion model from Hugging Face:
- **Comfy-Org/stable-diffusion-v1-5-archive**: [Download](https://huggingface.co/Comfy-Org/stable-diffusion-v1-5-archive/blob/main/v1-5-pruned-emaonly-fp16.safetensors)


### **Step 4: Move Model to the Correct Folder**
After downloading, move the model file to the `models/checkpoints/` directory:
```sh
mkdir -p models/checkpoints
mv path/to/downloaded/model.safetensors models/checkpoints/
```

---

## **3. Running ComfyUI with Stable Diffusion**

### **Step 5: Start the ComfyUI Interface**
Run the following command to start ComfyUI:
```shhttps
python main.py
```

### **Step 6: Access the Web Interface**
Once ComfyUI is running, open your browser and go to:
👉 **http://127.0.0.1:8188**

---

## **4. Generating an Image**

### **Step 7: Provide a Text Prompt**
- In the ComfyUI interface, enter a **text prompt** describing the image.
- Adjust **sampling steps, CFG scale, and resolution** if needed.

### **Step 8: Select the Checkpoint**
- Ensure your **Stable Diffusion model** is selected under "Checkpoint".

### **Step 9: Generate the Image**
- Click **"Generate"** to create the image!
- The generated images will be saved in the `output_images/` directory.

---

## **5. Saving and Accessing Generated Images**

- Images are saved in the **`output_images/`** folder inside the ComfyUI directory.
- You can edit or enhance these images using an image editor.

---

## **6. Stopping the Interface**

To stop ComfyUI, press:
```sh
CTRL + C
```
Or simply close the terminal window.

---

## **7. Conclusion**

You have successfully set up **ComfyUI with Stable Diffusion**! 🚀 Start experimenting with different prompts and models to create unique AI-generated images.


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
![ComfyUI_00001_ ](""C:\Users\sarfa\Downloads\ComfyUI_windows_portable_nvidia\ComfyUI_windows_portable\ComfyUI\output\ComfyUI_00001_.png"")

## Future Work
- Enhancing UI features for better user control.
- Implementing real-time image generation.
- Optimizing diffusion steps for faster results.



## Contact
For queries, reach out to **Zobiya Hussain** at [hussainzobiya27@gmail.com](mailto:hussainzobiya27@gmail.com).
