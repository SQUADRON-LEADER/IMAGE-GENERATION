# Stable Diffusion Image Generation

Welcome to the **Stable Diffusion Image Generation** repository! This project leverages the powerful [Stable Diffusion](https://github.com/CompVis/stable-diffusion) model by Stability AI to create high-quality images from textual prompts.

## ✨ Features

* Generate stunning visuals from descriptive text inputs.
* Built on top of Stable Diffusion v2.1.
* GPU-accelerated inference for faster processing.
* Easily customizable and modular codebase.

## 🛠️ Prerequisites

* Python 3.10 or higher
* Hugging Face account ([Sign up here](https://huggingface.co/join))
* GPU (recommended for best performance)

## 📦 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/stable-diffusion-image-generation.git
   cd stable-diffusion-image-generation
   ```

2. **Install required dependencies:**

   ```bash
   pip install diffusers transformers torch torchvision huggingface_hub
   ```

3. **Authenticate with Hugging Face:**

   ```python
   from huggingface_hub import login
   login(token="your_huggingface_token")
   ```

## 📄 Usage

1. **Edit the prompt:**
   Open `stable_diffusion_pipeline.py` and modify the `prompt` variable:

   ```python
   prompt = "A futuristic cityscape at sunset, vibrant colors, high detail"
   ```

2. **Run the script:**

   ```bash
   python stable_diffusion_pipeline.py
   ```

3. **View your creation:**
   The output image will be saved as `generated_image.png` in the project directory.

## 🎨 Example Output

### Input Prompt:

> "A futuristic cityscape at sunset, vibrant colors, high detail"

### Generated Image:

*Output will be displayed/saved after execution.*

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.


## 🙌 Acknowledgements

* [Stability AI](https://stability.ai/) for developing Stable Diffusion.
* [Hugging Face](https://huggingface.co/) for hosting models and APIs.

---

**Happy Generating!** 🎉
