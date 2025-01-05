

# 🖼️📄 **Image to PDF Converter**

A **Python-based tool** to merge multiple images (PNG, JPG, JPEG) into a **high-quality PDF**. With an intuitive **Tkinter GUI**, it uses `Pillow` and `ReportLab` libraries to ensure sharp output and smooth performance. 

---

## **✨ Features**

### 📂 **Select Images Easily**
- Pick multiple images simultaneously with a simple file dialog.

### 🔍 **Preview Before Conversion**
- See a list of selected images before creating the PDF.

### ✍️ **Custom PDF Name**
- Name your PDF file to suit your preferences.

### 🖼️ **Smart Resizing**
- Automatically adjusts images to fit A4 dimensions while preserving the aspect ratio.

### 🪄 **Clean & User-Friendly**
- Simple layout with intuitive buttons and fields.

### ⚠️ **Error Notifications**
- Alerts for unsupported formats, invalid inputs, and other issues.

### 📃 **High-Quality PDFs**
- Generates professional-grade PDFs that retain image sharpness.

---

## **🛠️ Requirements**

Make sure you have the following installed:

- **`Pillow`** 🖼️: For image processing.
- **`ReportLab`** 📄: For PDF generation.
- **`Tkinter`** 🎨: Pre-installed with Python.

Install missing libraries with:
```bash
pip install pillow reportlab
```

---

## **🚀 How to Get Started**

### 1️⃣ **Download the Tool**
- Clone the repository or download the project files.

### 2️⃣ **Run the App**
- Open your terminal or IDE and execute:
   ```bash
   python main.py
   ```

### 3️⃣ **Convert Images to PDF**
- **Select Images**: Click **Select Images** to choose files.  
- **Name Your PDF**: Enter a custom name.  
- **Generate PDF**: Hit **Convert to PDF** to save the final file.

---

## **🔍 Core Features**

### 🪄 **Streamlined Process**
- Navigate seamlessly through selection, naming, and conversion.

### 🖼️ **Supports Common Formats**
- Works with PNG, JPG, and JPEG files.

### 📃 **Optimized for A4**
- Produces PDFs tailored for A4 pages without sacrificing quality.

### ⚠️ **Robust Error Handling**
- User-friendly pop-ups notify you of any issues.

---

## **📂 Project Structure**

```plaintext
ImageToPDFConverter/
├── main.py            # Main application script
├── README.md          # Documentation
└── requirements.txt   # Dependency list
```

---

## **🔧 Customization Options**

### ✏️ **Change PDF Dimensions**
Edit the page size in the `convert_images_to_pdf` function:  
```python
pdf = canvas.Canvas(output_pdf_path, pagesize=(595.28, 841.89))  # A4 size
```

- **Letter size**: Use `(612, 792)`.  
- **Custom size**: Replace with `(width, height)` in points.

### 🎨 **Improve the GUI**
- Add themes with `ttkbootstrap`.  
- Implement drag-and-drop for easier image selection.

---

## **✨ Future Features**

- ⏳ **Progress Bar**: Show progress for large image sets.  
- 🔒 **PDF Security**: Add password protection.  
- 🎨 **Image Editing**: Rotate, crop, or filter images before conversion.  
- 🌍 **Localization**: Multi-language support.  
- ☁️ **Cloud Features**: Upload PDFs to services like Google Drive or Dropbox.  

---

## **🐞 Known Issues**

1. **Special Characters**: Filenames with special characters may cause errors.  
2. **Dependencies**: Ensure `Pillow` and `ReportLab` are pre-installed.  

---

## **📜 License**

Licensed under the **MIT License**—free to use, modify, and distribute for personal or educational projects.
