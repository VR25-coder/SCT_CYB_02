# 🖼️ Image Encryption Task - SkillCraft Technology

## 🔐 Task Description

This task demonstrates a basic method of **image encryption** using Python. The script inverts the RGB values of every pixel in the image, creating a visually "encrypted" version. It’s a beginner-friendly approach to understanding how pixel manipulation works in image processing.

---

## 📁 File Included

- `image_encrypt.py` - Python script that performs image encryption by inverting RGB values.

---

## 🧠 Concepts Used

- Python Imaging Library (PIL / Pillow)
- Pixel-level image processing
- RGB color manipulation
- Basic file input/output in Python

---

## ⚙️ How It Works

The script opens an image, reads each pixel's RGB value, inverts it (using `255 - value`), and saves the result as a new image.

### 🔄 Example:

Original RGB: `(100, 150, 200)`  
Encrypted RGB: `(155, 105, 55)`

---

## 💻 How to Run on Kali Linux

### 🔸 Step 1: Install Pillow (if not installed)

```bash
pip3 install Pillow
