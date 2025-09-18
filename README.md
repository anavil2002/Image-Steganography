# 📸 Image Steganography

Hide secret text messages inside images and extract them back without noticeable changes. This project demonstrates the fundamentals of **steganography** using Python.

---

## 🚀 Features

* 🔐 Hide text messages inside PNG/JPG images while keeping quality intact
* 🖼️ Retrieve hidden messages from stego-images
* 🐍 Simple Python implementation – easy to understand & extend
* 🌐 (Optional) Web/HTML demo for visualization

---

## 📂 Project Structure

```
Image-Steganography/
│
├── embed.py              # Script to hide messages
├── extract.py            # Script to retrieve messages
├── requirements.txt      # Dependencies
├── demo/                 # Example images
└── README.md             # Documentation
```

---

## 🛠️ Installation & Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/anavil2002/Image-Steganography.git
   cd Image-Steganography
   ```

2. **Create Virtual Environment (optional but recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate     # On Linux/Mac
   venv\Scripts\activate        # On Windows
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

> If you don’t have `requirements.txt`, install manually:

```bash
pip install pillow
```

---

## ▶️ Usage

### 🔹 Hide a Message (Embedding)

```bash
python embed.py --input demo/input.png --message "This is a secret!" --output demo/stego.png
```

* `--input` : Original image file
* `--message` : The text you want to hide
* `--output` : New image with hidden text

---

### 🔹 Extract a Message

```bash
python extract.py --input demo/stego.png
```

* `--input` : Stego-image containing hidden message

---


## 🔮 Future Improvements

* Add **encryption layer** before hiding messages
* Support for more formats (BMP, TIFF, etc.)
* Create a **GUI/Web app** for easy use
* Batch processing multiple images

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to improve.

---

## 📜 License

This project is licensed under the **MIT License**.

---
