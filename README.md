# 🔳 QR Code Generator (Python)

A simple Python script to generate a styled QR code from a URL using the `qrcode` library.

---

## 📌 Description

This project generates a QR code for any given URL. The QR code is customizable with colors, size, and error correction level. The generated QR code is saved as an image file.

---

## 🚀 Features

- Generate QR code from a URL  
- Custom QR code color (red on white)  
- Adjustable size and border  
- High-quality image output  
- Lightweight and easy to use  

---

## 🛠️ Technologies Used

- Python 3  
- qrcode library  

---

## 📂 Project Structure
.
├── generate_qrcode.py
├── README.md


---

## ⚙️ Installation

Install the required dependency:

```bash
pip install qrcode[pil]
```
---

## ▶️ Usage

1. Open generate_qrcode.py

2. Replace the URL in the script:
```bash
input_URL = "https://www.google.com/"
```

3. Run the script:
```bash
python3 generate_qrcode.py
```
---

## 📤 Output

A QR code image named url_qrcode.png will be generated in the project directory.

---

## ⚙️ Configuration Explained

version=1 → Controls size of QR code (1 = smallest)

error_correction → Handles data recovery if QR is damaged

box_size=15 → Size of each box in pixels

border=4 → Thickness of border

---

## ✏️ Customization

You can enhance the script by:

- Taking URL input from user
- Changing colors dynamically
- Saving with custom filenames
- Generating QR codes in bulk

---

## ⚠️ Requirements

Python 3.x

qrcode library

---

## 👤 Author

MD Minhaj Ali

📜 License

This project is open-source and free to use.
