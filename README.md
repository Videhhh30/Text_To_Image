# Text_To_Image
Here's a concise **README description** tailored specifically to your code:

---

# 🎨 Diffusion Image Generator using Hugging Face `diffusers`

This project uses Hugging Face’s `diffusers` library to generate AI art using Stable Diffusion models. It loads pre-trained models like `dreamlike-art/dreamlike-diffusion-1.0` and `stabilityai/stable-diffusion-xl-base-1.0`, runs prompts through them, and visualizes the output using `matplotlib`.

## ✨ Features

* Load and run pre-trained diffusion models from Hugging Face Hub
* Generate stunning images from text prompts
* Visualize single or multiple generated images with `matplotlib`
* Optimized for CUDA (GPU) using `torch.float16`

## 🖼 Sample Prompt

```
dreamlikeart, a grungy woman with rainbow hair, travelling between dimensions, dynamic pose, happy, soft eyes and narrow chin, extreme bokeh, dainty figure, long hair straight down, torn kawaii shirt and baggy jeans
```

## ⚙️ Usage

* Install dependencies with:

  ```bash
  pip install diffusers transformers accelerate matplotlib
  ```
* Run the script to generate and visualize the image output from a prompt.

## 🧠 Fine-Tuning

To customize the diffusion model on your own dataset, you can fine-tune it using methods like DreamBooth or LoRA with Hugging Face tools.

---

