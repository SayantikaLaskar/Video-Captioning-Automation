# Video Captioning Automation with BLIP

This project uses a Vision-Language Model (BLIP) to automatically generate natural language descriptions for videos.

## 🔧 How It Works

- Extracts a frame from each video using OpenCV
- Uses the BLIP image captioning model to describe the content of that frame
- Saves all captions to a text file

## 🧪 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
