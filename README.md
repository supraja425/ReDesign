# 🖌️ AI-Powered Object Redesign with Stable Diffusion ControlNet

This project allows you to **redesign objects** in an uploaded image using the **Stable Diffusion ControlNet (Canny)** model. It preserves the original shape while adding intricate artistic details, based on your textual prompt. Built using 🧠 `diffusers`, 🎨 `Gradio`, and 🤖 `ControlNet`.

---

## 🚀 Features

- ✅ Edge detection via Canny to retain shape.
- ✅ Generate highly-detailed, colored redesigns.
- ✅ Gradio-powered web interface.
- ✅ Uses Stable Diffusion v1.5 with ControlNet for structured image generation.

---

## 🧰 Requirements

Install the required libraries with:

```bash
pip install gradio diffusers transformers accelerate opencv-python pillow
```
Also ensure you have:

A GPU-enabled system (with CUDA support)

A Hugging Face account and access token

🎯 How It Works
Upload an object image (e.g., a plain T-shirt or bottle).

Enter your redesign prompt (e.g., "floral design with golden accents").

The model applies Canny edge detection and generates a redesigned version based on your description.
