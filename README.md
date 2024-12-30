# 🖼️📄 **Image to PDF Converter**  

A lightweight and efficient **Python-based tool** designed to merge multiple images (PNG, JPG, JPEG) into a high-quality PDF. Featuring an intuitive **Tkinter GUI**, the app uses `Pillow` and `ReportLab` libraries to ensure excellent output quality and smooth performance.  

---

## **✨ Features**  

### 📂 **Select Multiple Images**  
- Easily pick multiple images at once using a file dialog.  

### 🔍 **Preview Before Conversion**  
- Display a list of selected images for confirmation.  

### ✍️ **Custom PDF Name**  
- Enter a custom name for the generated PDF.  

### 🖼️ **Smart Image Resizing**  
- Automatically adjusts images to fit A4 page dimensions while maintaining aspect ratio.  

### 🪄 **User-Friendly Interface**  
- Simple and clean layout with clear buttons and input fields.  

### ⚠️ **Error Notifications**  
- Alerts users about invalid inputs, unsupported formats, or other issues.  

### 📃 **High-Quality Output**  
- Generates professional-grade PDFs with sharp image quality.  

---

## **🛠️ Requirements**  

Make sure you have the following installed:  

- `Pillow` 📦: For handling image processing.  
- `ReportLab` 🖋️: For PDF creation.  
- `Tkinter` 🖼️: Comes pre-installed with Python.  

Install missing dependencies with:  
```bash  
pip install pillow reportlab  
```  

---

## **🚀 Getting Started**  

### Step 1️⃣: **Download the App**  
- Clone the repository or download the project files.  

### Step 2️⃣: **Run the App**  
- Open the terminal or IDE and run the script:  
   ```bash  
   python main.py  
   ```  

### Step 3️⃣: **Create Your PDF**  
- **Select Images**: Click the **Select Images** button to pick files.  
- **Name Your PDF**: Enter the desired PDF name in the input field.  
- **Generate PDF**: Click **Convert to PDF**, and save your file.  

---

## **🔍 Core Highlights**  

### 🪄 **Streamlined Workflow**  
- Easily navigate through image selection, naming, and conversion steps.  

### 🖼️ **Supports Popular Formats**  
- Works seamlessly with PNG, JPG, and JPEG files.  

### 📃 **Professional Output**  
- Generates PDFs optimized for A4 dimensions while maintaining image quality.  

### ⚠️ **Robust Error Handling**  
- Ensures smooth user experience with clear pop-ups for any issues.  

---

## **📂 File Structure**  

```plaintext  
ImageToPDFConverter/  
├── main.py            # Core logic for the app  
├── README.md          # Documentation and instructions  
└── requirements.txt   # List of required Python libraries  
```  

---

## **🔧 Customization Options**  

### ✏️ **Change PDF Page Size**  
To modify the page dimensions, adjust the following code in the `convert_images_to_pdf` function:  
```python  
pdf = canvas.Canvas(output_pdf_path, pagesize=(595.28, 841.89))  # A4 size  
```  

- For **Letter** size: Use `(612, 792)`  
- For **Custom Dimensions**: Replace with `(width, height)` in points.  

### 🎨 **Enhance GUI Design**  
- Add themes or modernize with libraries like `ttkbootstrap`.  
- Implement drag-and-drop support for easier file selection.  

---

## **✨ Future Enhancements**  

- ⏳ **Progress Bar**: Visualize the conversion process for large batches.  
- 🔒 **Secure PDFs**: Add options to password-protect your files.  
- 🎨 **Image Editing Features**: Rotate, crop, or add filters to images before conversion.  
- 🌍 **Localization**: Provide multi-language support for global users.  
- ☁️ **Cloud Integration**: Upload finished PDFs directly to services like Dropbox or Google Drive.  

---

## **🐞 Known Issues**  

1. **Special Characters in Names**: Some filenames with special characters may not work correctly.  
2. **Library Dependency**: Ensure `Pillow` and `ReportLab` are installed beforehand.  

---

## **📜 License**  

This project is distributed under the **MIT License**, allowing free use, modification, and distribution for personal and educational purposes.  

---  
