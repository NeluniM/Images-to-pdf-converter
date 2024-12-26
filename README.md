# 🖼️📄 **Image to PDF Converter**  

A powerful yet simple **Python-based application** designed to seamlessly convert multiple image files (PNG, JPG, JPEG) into a single PDF document. Featuring an easy-to-use GUI built with `Tkinter`, the app employs `Pillow` and `ReportLab` libraries for efficient image handling and high-quality PDF generation.

---

## ✨ **Features**  

- **Batch Image Selection** 📂: Choose multiple image files in one go using a user-friendly file dialog.  
- **Preview Selected Files** 🔍: Displays the names of all selected images before conversion.  
- **Custom Output Name** ✍️: Allows users to specify the name for the resulting PDF.  
- **Automatic Scaling** 🖼️: Adjusts images to fit A4 paper size while retaining aspect ratio.  
- **Simple GUI** 🪄: Intuitive interface for smooth navigation and quick operation.  
- **Error Notifications** ⚠️: Alerts for invalid file types or missing details, ensuring clarity.  
- **High-Quality Output** 📃: Converts images to PDF without compromising on quality.  

---

## 🛠️ **Requirements**  

Make sure you have Python installed along with the following libraries:  

- `Pillow` 📦 (for image processing)  
- `ReportLab` 🖋️ (for PDF creation)  
- `Tkinter` 🖼️ (pre-installed with Python by default)  

Install the required libraries with:  
```bash  
pip install pillow reportlab  
```  

---

## 🚀 **How to Use the Application**  

### 1. **Setup**  
   - Download or clone the project repository.  
   - Navigate to the project folder and run `main.py` using a terminal or IDE.  

### 2. **Convert Images to PDF**  
   - **Select Images**: Click **Select Images** and choose one or more image files.  
   - **Set PDF Name**: Type the desired name for your PDF (e.g., `Document1`).  
   - **Generate PDF**: Hit **Convert to PDF** to create and save the file.  

### 3. **Output**  
   - The PDF will be saved with your chosen name, including all the selected images formatted to fit A4 pages.  

---

## 🔍 **Core Highlights**  

### Simple and Intuitive Interface  
Built using `Tkinter`, the app provides buttons, input fields, and previews to ensure a smooth user experience.  

### Robust Image Processing  
With `Pillow`, the app supports popular image formats and ensures they are resized efficiently for PDF conversion.  

### High-Quality PDF Creation  
Using `ReportLab`, the generated PDFs maintain sharp image quality and are properly formatted.  

### Error Handling for Smooth Operation  
Alerts users about issues such as invalid image formats, missing inputs, or file selection errors.  

---

## 📂 **Project Structure**  

```
ImageToPDFConverter/  
│  
├── main.py            # Main script for running the application  
├── README.md          # Detailed documentation  
└── requirements.txt   # List of dependencies  
```  

---

## 🔧 **Customizations**  

### Adjust Page Size  
Modify the page size in the `convert_images_to_pdf` function:  
```python  
pdf = canvas.Canvas(output_pdf_path, pagesize=(595.28, 841.89))  # A4 by default  
```  

Options:  
- **Letter**: Replace with `(612, 792)`  
- **Custom Size**: Provide `(width, height)` in points.  

### Add New Features  
- **Drag-and-Drop** 🖱️: Simplify file selection by enabling drag-and-drop functionality.  
- **Image Editing** 🎨: Add tools for rotating, cropping, or applying filters to images before conversion.  
- **Multi-Language Support** 🌍: Provide language options for international users.  

---

## 🛠️ **Planned Features**  

- **Progress Indicators** ⏳: Show progress for converting large batches of images.  
- **Cloud Integration** ☁️: Add support to save PDFs directly to cloud storage like Google Drive or Dropbox.  
- **Advanced Editing Options** 🔄: Include tools for adjusting image brightness, contrast, or adding text overlays.  
- **PDF Security** 🔒: Allow users to set passwords for securing their PDFs.  
- **Cross-Platform Executables** 🖥️: Create standalone versions for Windows, macOS, and Linux.  

---

## 🐞 **Known Limitations**  

1. **Input Validation**: Special characters in filenames or empty fields might cause errors.  
2. **API Dependency**: The application requires `Pillow` and `ReportLab` to function properly.  

---

## 📜 **License**  

This project is distributed under the **MIT License**. You are free to modify, use, and distribute the code for personal or educational purposes.  

---  
