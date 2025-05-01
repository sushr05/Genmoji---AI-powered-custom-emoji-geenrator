# 🌟 Genmoji – AI-Powered Custom Emoji Generator

Genmoji is a generative AI project that creates custom emoji-style images from natural language prompts. It combines the power of Large Language Models (LLMs) and Stable Diffusion XL, fine-tuned on emoji datasets, to enable expressive and personalized emoji creation.

# 🧠 Key Features

Prompt Enrichment with DeepSeek LLM: Refines short or vague user input into detailed, expressive prompts suitable for visual generation.

Emoji Image Generation using Stable Diffusion XL (SDXL) fine-tuned with LoRA (Low-Rank Adaptation) on the Emojigraph dataset.

High-Quality Visual Output: Generates 512×512 emoji-style images, suitable for resizing and background removal (e.g., for sticker packs or messaging).

Transparent Workflow: Incorporates data preprocessing, LoRA tuning, and image post-processing with tools like rembg.

# 📦 Tech Stack

Python, PyTorch, Transformers, Diffusers

Stable Diffusion v2.1, LoRA Fine-Tuning

DeepSeek LLM for natural language understanding

Hugging Face for model hosting and inference

# 🧪 What’s Implemented
✅ LoRA fine-tuning pipeline on emoji dataset

✅ Prompt refinement using a hosted LLM

✅ Sample image generation from text prompts

✅ Model hosted on Hugging Face: sdxl-noto-emoji-lora-2

✅ Cost analysis and training optimization strategies

✅ Detailed testing strategy (unit, integration, UI)

# ⚙️ How It Works
Genmoji transforms a natural language prompt into a custom emoji-style image using a two-stage AI pipeline:

# 🧾 1. Prompt Enhancement (Text Preprocessing)
The user provides a short or vague prompt (e.g., "sad toast").

The prompt is processed using the DeepSeek LLM, which adds semantic richness and context.

Example transformation:

Input: "sad toast"

Output: "a slice of toast with teary eyes and a sad expression sitting on a breakfast plate"

# 🖼️ 2. Image Generation (Diffusion Model)
The enhanced prompt is passed to a Stable Diffusion XL (SDXL) model.

The model is fine-tuned using LoRA (Low-Rank Adaptation) on an emoji dataset (Emojigraph).

The system generates a 512×512 emoji-style image that matches the prompt's emotion and theme.

Final output is post-processed using Rembg to remove background and resize if needed.

# 🧪 Training Details
Model: Stable Diffusion XL v2.1

Fine-Tuning: LoRA (parameter-efficient training)

Dataset: Emojigraph (image-text emoji pairs)

Tools: PyTorch, Hugging Face Transformers & Diffusers

# 🚧 Future Work (Planned)
🌐 Real-time web UI for live emoji generation

📱 Integration with messaging platforms

🌍 Multilingual input support

📦 Batch generation & sticker pack export
