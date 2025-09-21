# FluxStyle 🎨

FluxStyle is a simple project showcasing image generation using the **[FLUX.1-Kontext](https://huggingface.co/black-forest-labs/FLUX.1-Kontext-dev)** model from Hugging Face Diffusers.  
It allows generating images from text prompts either directly through Python or via a Gradio-powered interface.

---

## 🚀 Features
- Generate images from text prompts.
- Powered by Hugging Face `diffusers` and PyTorch.
- GPU-accelerated (CUDA support).
- Interactive demo with **Gradio**.

---

## 📦 Installation

```bash
git clone https://github.com/Viswajithm2001/FluxStyle.git
cd FluxStyle
```
# Create virtual environment (recommended)
```
python -m venv venv
source venv/bin/activate   # (Linux/Mac)
venv\Scripts\activate      # (Windows)
```
# Install dependencies
```
pip install torch diffusers transformers accelerate safetensors gradio
```
# Run with python
```
python fluxstyle.py
```

