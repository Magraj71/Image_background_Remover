# 🖼️ Image Background Remover (Frontend Only)

A simple and responsive web application that allows users to remove image backgrounds using the [remove.bg](https://www.remove.bg/api) API. Built using HTML, CSS, and JavaScript — no backend required.

## 🎯 Features

- Upload an image and instantly remove its background
- Clean and minimal user interface
- Download the processed image with a transparent background
- Works on modern browsers

## 🌐 Live Demo

👉 [Try It Online](https://image-background-remover-red.vercel.app/)

## 🛠️ Tech Stack

- **HTML5** – for structure  
- **CSS3 / Tailwind CSS** – for styling  
- **JavaScript (Vanilla)** – for interactivity and API calls  
- **remove.bg API** – for AI-powered background removal

## 📸 How It Works

1. User uploads an image (PNG or JPG).
2. JavaScript sends the image to `remove.bg` API via a `fetch()` request.
3. The API responds with a new image (background removed).
4. The app displays the result and provides a download option.

> ⚠️ **Note:** This app requires a valid `remove.bg` API key and internet access to work.

## 🧪 Setup Instructions

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/image-background-remover-frontend.git
cd image-background-remover-frontend
