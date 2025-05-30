# 🖼️ BLIP Image Captioning

This project uses the **BLIP** (Bootstrapped Language Image Pretraining) model for image captioning in two modes:

1. **Gradio Web App** – Upload an image, get a caption instantly.
2. **Web Scraper + Bulk Captioning** – Scrape images from a webpage, generate captions, and save them in `captions.txt`.

---

## 🚀 Features

- 📷 Image captioning with BLIP
- 🧠 Powered by HuggingFace Transformers
- 🖼️ GUI with Gradio
- 🌐 Bulk captioning from scraped webpage images
- 📄 Outputs captions with image URLs to `captions.txt`

---

## 📦 Installation

```bash
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
pip install gradio requests beautifulsoup4 transformers
