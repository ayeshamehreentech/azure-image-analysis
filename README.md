This folder contains Python code# Azure Image Analysis Project

This project uses **Azure AI Vision** to analyze images and extract insights such as captions, tags, objects, and people. It also generates annotated images with bounding boxes.

## 🚀 Features

* Image caption generation
* Dense captions
* Object detection
* People detection
* Image tagging
* Annotated output images

## 🛠️ Technologies Used

* Python
* Azure AI Vision SDK
* PIL (Pillow)
* Matplotlib
* dotenv

## 📦 Installation

```bash
pip install azure-ai-vision-imageanalysis python-dotenv pillow matplotlib
```

## 🔐 Setup

Create a `.env` file:

```
AI_SERVICE_ENDPOINT=your_endpoint_here
AI_SERVICE_KEY=your_key_here
```

## ▶️ Run the Project

```bash
python app.py
```

OR with custom image:

```bash
python app.py images/yourimage.jpg
```

## 📁 Output

* `objects.jpg` → Objects annotated
* `people.jpg` → People annotated

## ⚠️ Note

* `.env` is ignored for security
* Images are included in repo

## 👩‍💻 Author

Ayesha Mehreentech
