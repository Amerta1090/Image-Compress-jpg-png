# Compress Image Script

## 📌 Introduction
Welcome to the most dramatic and exhilarating journey of image compression! This script takes your massive, bulky images and shreds them down to a lean, optimized form—all while keeping them visually stunning (most of the time). If you’re tired of your bloated images hogging storage space, this script is your digital diet plan.

## 🎯 Features
✅ Compress JPEG and PNG images with surgical precision.
✅ Automatic quality adjustment using binary search for JPEGs.
✅ Smart optimization to maintain visual fidelity (because we care!).
✅ Supports a target size with a flexible tolerance range.
✅ Handles images like a seasoned digital magician.

## 🛠️ Installation
To get started, ensure you have the following dependencies installed:

```bash
pip install pillow
```

## 🚀 Usage
Run the script with the following command:

```python
python compress_image.py
```

Or use it in your own Python code like this:

```python
from compress_image import compress_image

compress_image(
    input_path="your_image.jpg",
    output_path="your_compressed_image.jpg",
    target_size=5000000,  # Target size in bytes (5MB in this case)
    tolerance=0.1  # 10% tolerance
)
```

## 📏 How It Works
1. **Reads your image** – Opens the image file like an art critic analyzing a masterpiece.
2. **Checks the size** – If it's already smaller than the target, we leave it alone (because we respect efficiency).
3. **JPEG Compression** – Uses binary search to find the best quality setting that meets your size constraints.
4. **PNG Compression** – Pushes the limits of lossless compression (because PNGs refuse to lose quality).
5. **Saves the final masterpiece** – Exports your compressed image with the optimal settings.

## ⚠️ Limitations
- Doesn't support WebP, GIF, or exotic image formats from deep space.
- If your PNG is stubbornly large, this script can only do so much.
- Not responsible for any artistic trauma caused by over-compression.

## 🤝 Contributing
Feel free to modify, improve, or hack it to suit your dark, mysterious needs. Just don't forget to share your improvements with the world.

## 🎉 Conclusion
This script is your best bet for keeping images under control without compromising their beauty. Use it wisely, and may your storage woes be forever banished!

