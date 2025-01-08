# 🖼️📄 **Image to PDF Converter**

Turn your **images** (PNG, JPG, JPEG) into **high-quality PDFs** effortlessly! This **Python-powered tool** features an intuitive **Tkinter GUI** and leverages `Pillow` & `ReportLab` for exceptional results.  

---

## **✨ Key Features**

### 📸 **Select Images with Ease**  
- Choose multiple images using a simple file dialog.  

### 🖼️ **Preview Your Selection**  
- See the selected images listed before conversion.  

### ✍️ **Custom PDF Names**  
- Personalize your PDF filename to your liking.  

### 📏 **Smart Image Resizing**  
- Adjusts images to A4 size while preserving aspect ratio.  

### 🎨 **Clean, User-Friendly GUI**  
- Intuitive buttons and fields for a seamless experience.  

### ⚠️ **Error Alerts**  
- Get notified about unsupported formats, invalid inputs, and more.  

### 🖨️ **Professional-Quality PDFs**  
- Outputs sharp, high-quality PDFs.  

---

## **🛠️ Prerequisites**

Ensure the following libraries are installed:

- **`Pillow`** 🖼️: For image handling.  
- **`ReportLab`** 📄: For PDF generation.  
- **`Tkinter`** 🎨: Pre-installed with Python.  

Install missing packages with:  
```bash
pip install pillow reportlab
```

---

## **🚀 Quick Start**

### 1️⃣ **Download the Tool**  
Clone the repository or download the files.  

### 2️⃣ **Run the App**  
Open a terminal or IDE and execute:  
```bash
python main.py
```  

### 3️⃣ **Convert Images to PDF**  
- **Select Images**: Click **Select Images** to choose files.  
- **Name Your PDF**: Enter a custom name.  
- **Generate PDF**: Click **Convert to PDF** to save your file.  

---

## **📦 Project Layout**  

```plaintext
ImageToPDFConverter/
├── main.py            # Core script
├── README.md          # Documentation
└── requirements.txt   # Dependencies
```

---

## **⚙️ Customization Options**

### ✏️ **Change PDF Dimensions**  
Adjust the page size in the `convert_images_to_pdf` function:  
```python
pdf = canvas.Canvas(output_pdf_path, pagesize=(595.28, 841.89))  # A4 size
```  
- **Letter size**: Replace with `(612, 792)`.  
- **Custom size**: Use `(width, height)` in points.  

### 🎨 **Enhance the GUI**  
- Add themes using `ttkbootstrap`.  
- Enable drag-and-drop for easier image selection.  

---

## **🚧 Known Issues**

1. **Special Characters**: Filenames with unusual characters may cause errors.  
2. **Dependencies**: Ensure required libraries are installed.  

---

## **💡 Future Upgrades**  

- ⏳ **Progress Bar**: Indicate conversion progress for large image batches.  
- 🔒 **PDF Security**: Add password protection.  
- 🎨 **Image Editing**: Rotate, crop, or filter images before saving.  
- 🌍 **Localization**: Add multi-language support.  
- ☁️ **Cloud Integration**: Save PDFs to Google Drive or Dropbox.  

---

## **📜 License**  

Released under the **MIT License**—feel free to use, modify, and distribute! 🎉  
