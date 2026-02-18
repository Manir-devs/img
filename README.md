<p align="center">
  <img src="assets/logo.png" alt="Manir's Image Tool Logo" width="180"/>
</p>

<h1 align="center">🎨 MANIR'S IMAGE TOOL</h1>
<p align="center">
  <b>Powerful • Lightweight • CLI + GUI Hybrid Image Utility</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Python-3.8+-yellow?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20Mac-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/License-MIT-red?style=for-the-badge"/>
</p>

---

## 🚀 About The Project

**Manir's Image Tool** is a professional-grade image utility designed for developers, designers, and power users.

It combines:

- ⚡ Fast CLI-based processing  
- 🖼️ Interactive GUI image viewer  
- 📦 Exact file size generation  
- 🔄 Format conversion (GIF, PDF, SVG, JPG, PNG, etc.)  
- ✂️ Interactive cropping tool  
- 🎯 Animated GIF frame extraction & creation  

All in one lightweight Python-based toolkit.

---

# 📥 Download Latest Release

<p align="center">
  <a href="https://github.com/Manir-devs/img/releases/latest">
    <img src="https://img.shields.io/badge/⬇ Download Latest Release-black?style=for-the-badge"/>
  </a>
</p>

---

# ⚙️ Installation Guide

## 🔹 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
```

---

## 🔹 2️⃣ Install Dependencies

### Required Python Version:
```
Python 3.8 or higher
```

### Install Required Libraries:

```bash
pip install pillow colorama svglib reportlab
```

---

## 📦 Dependencies

| Package | Purpose |
|---------|----------|
| Pillow | Image processing engine |
| colorama | Colored terminal output |
| svglib | SVG parsing |
| reportlab | SVG rendering support |
| tkinter | GUI support (comes with Python) |

---

# 🛠 Features & Commands

---

## 🖼 Open Image (GUI Viewer)

```bash
python tool.py open image.jpg
```

Opens the image in a Tkinter-based window.

---

## 📏 Make Exact File Size

```bash
python tool.py make kb 500 photo.jpg
```

Supports:
- bit
- byte
- kb
- mb
- gb

✔ Automatically adjusts resolution  
✔ Smart quality compression  
✔ Padding or trimming to match exact byte size  

---

## 🔄 Convert Formats

### Extract GIF Frames:
```bash
python tool.py ext animation.gif output_folder png
```

### Convert Folder → GIF:
```bash
python tool.py ext frames_folder output.gif
```

### Convert PDF → GIF:
```bash
python tool.py ext file.pdf output.gif
```

### Convert SVG:
```bash
python tool.py ext image.svg output.png
```

---

## ✂️ Interactive Crop Tool

```bash
python tool.py crop image.jpg
```

- Drag to select
- Automatically saves cropped image
- Clean and minimal UI

---

# 🧠 How It Works

✔ Smart compression loop  
✔ Dynamic resolution scaling  
✔ Frame-by-frame animation handling  
✔ Transparent format handling  
✔ Automatic RGBA → RGB correction  

Built with performance and reliability in mind.

---

# 📌 Version

Current Version:
```
v1.0
```

Check version:

```bash
python tool.py --version
```

---

# 🔮 Future Roadmap

### 🚀 Upcoming Features

- 🔥 Drag & Drop GUI Mode
- 📊 Batch Image Optimization
- 🎞 Advanced GIF Controls (FPS, Quality)
- 🧩 Plugin System
- 🌐 Web-based Interface
- 📱 Android Compatible Version
- 🧠 AI Image Compression
- 🖌 Watermarking System
- 🗜 Lossless Compression Engine
- 🧵 Multithreading for Faster Processing

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Submit a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

You are free to:
- Use
- Modify
- Distribute
- Contribute

---

# 👑 Author

Developed with passion by **Manir**

---

# ⭐ Support

If you like this project:

- ⭐ Star the repository
- 🍴 Fork it
- 🐛 Report issues
- 💡 Suggest features

---

<p align="center">
  <b>Made with ❤️ in Python</b>
</p>
