##🌟 Genmoji – AI-Powered Custom Emoji Generator
Genmoji is a generative AI project that creates custom emoji-style images from natural language prompts. It combines the power of Large Language Models (LLMs) and Stable Diffusion XL, fine-tuned on emoji datasets, to enable expressive and personalized emoji creation.

##🧠 Key Features
Prompt Enrichment with DeepSeek LLM: Refines short or vague user input into detailed, expressive prompts suitable for visual generation.

Emoji Image Generation using Stable Diffusion XL (SDXL) fine-tuned with LoRA (Low-Rank Adaptation) on the Emojigraph dataset.

High-Quality Visual Output: Generates 512×512 emoji-style images, suitable for resizing and background removal (e.g., for sticker packs or messaging).

Transparent Workflow: Incorporates data preprocessing, LoRA tuning, and image post-processing with tools like rembg.

##📦 Tech Stack
Python, PyTorch, Transformers, Diffusers

Stable Diffusion v2.1, LoRA Fine-Tuning

DeepSeek LLM for natural language understanding

Hugging Face for model hosting and inference

##🧪 What’s Implemented
✅ LoRA fine-tuning pipeline on emoji dataset

✅ Prompt refinement using a hosted LLM

✅ Sample image generation from text prompts

✅ Model hosted on Hugging Face: sdxl-noto-emoji-lora-2

✅ Cost analysis and training optimization strategies

✅ Detailed testing strategy (unit, integration, UI)

##🚧 Future Work (Planned)
🌐 Real-time web UI for live emoji generation

📱 Integration with messaging platforms

🌍 Multilingual input support

📦 Batch generation & sticker pack export
