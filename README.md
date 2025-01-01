# 🖼️📄 **Image to PDF Converter**

A lightweight and efficient **Python-based tool** to merge multiple images (PNG, JPG, JPEG) into a high-quality PDF. Featuring an intuitive **Tkinter GUI**, the app leverages the `Pillow` and `ReportLab` libraries for excellent output quality and smooth performance.

---

## **✨ Features**

### 📂 **Select Multiple Images**
- Pick multiple images simultaneously using a file dialog.

### 🔍 **Preview Before Conversion**
- View a list of selected images for confirmation.

### ✍️ **Custom PDF Name**
- Input a custom name for the generated PDF.

### 🖼️ **Smart Image Resizing**
- Automatically resizes images to fit A4 page dimensions while maintaining the aspect ratio.

### 🪄 **User-Friendly Interface**
- Clean, simple layout with clear buttons and input fields.

### ⚠️ **Error Notifications**
- Alerts for invalid inputs, unsupported formats, or other issues.

### 📃 **High-Quality Output**
- Produces professional-grade PDFs with sharp image quality.

---

## **🛠️ Requirements**

Ensure you have the following installed:

- **`Pillow`** 📦: For image processing.
- **`ReportLab`** 🖋️: For PDF creation.
- **`Tkinter`** 🖼️: Comes pre-installed with Python.

Install missing dependencies with:
```bash
pip install pillow reportlab
```

---

## **🚀 Getting Started**

### Step 1️⃣: **Download the App**
- Clone the repository or download the project files.

### Step 2️⃣: **Run the App**
- Open the terminal or IDE and execute:
   ```bash
   python main.py
   ```

### Step 3️⃣: **Create Your PDF**
- **Select Images**: Click the **Select Images** button to choose files.
- **Name Your PDF**: Enter a desired name for the PDF.
- **Generate PDF**: Click **Convert to PDF** and save your file.

---

## **🔍 Core Highlights**

### 🪄 **Streamlined Workflow**
- Smoothly navigate through image selection, naming, and conversion steps.

### 🖼️ **Popular Format Support**
- Compatible with PNG, JPG, and JPEG files.

### 📃 **Professional Output**
- Produces PDFs optimized for A4 dimensions without compromising quality.

### ⚠️ **Robust Error Handling**
- Clear pop-ups notify users of any issues.

---

## **📂 File Structure**

```plaintext
ImageToPDFConverter/
├── main.py            # Core application logic
├── README.md          # Documentation and instructions
└── requirements.txt   # List of required Python libraries
```

---

## **🔧 Customization Options**

### ✏️ **Change PDF Page Size**
Modify the page dimensions in the `convert_images_to_pdf` function:
```python
pdf = canvas.Canvas(output_pdf_path, pagesize=(595.28, 841.89))  # A4 size
```

- **Letter size**: Use `(612, 792)`.
- **Custom dimensions**: Replace with `(width, height)` in points.

### 🎨 **Enhance GUI Design**
- Add themes or modernize the interface with libraries like `ttkbootstrap`.
- Implement drag-and-drop functionality for file selection.

---

## **✨ Future Enhancements**

- ⏳ **Progress Bar**: Visualize the conversion process for large batches.
- 🔒 **Secure PDFs**: Add password protection options.
- 🎨 **Image Editing Features**: Rotate, crop, or apply filters before conversion.
- 🌍 **Localization**: Provide multi-language support.
- ☁️ **Cloud Integration**: Upload PDFs directly to services like Dropbox or Google Drive.

---

## **🐞 Known Issues**

1. **Special Characters in Names**: Filenames with special characters may cause issues.
2. **Library Dependency**: Ensure `Pillow` and `ReportLab` are installed beforehand.

---

## **📜 License**

This project is licensed under the **MIT License**, allowing free use, modification, and distribution for personal and educational purposes.

