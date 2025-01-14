# 🖼️📄 **Image to PDF Converter**  

Transform your **images** (PNG, JPG, JPEG) into **high-quality PDFs** with ease! This Python-powered tool boasts a sleek **Tkinter GUI** and leverages the power of `Pillow` and `ReportLab` for professional-grade results.  

---

## **✨ Key Features**  

- **📸 Image Selection Made Simple**: Choose multiple images in just a few clicks.  
- **🖼️ Preview Images**: See all your selected files at a glance.  
- **✍️ Custom File Names**: Set your preferred name for the PDF output.  
- **📏 Smart Resizing**: Images are auto-fitted to A4 size without distortion.  
- **🎨 Intuitive GUI**: Navigate effortlessly with a user-friendly design.  
- **⚠️ Reliable Error Handling**: Receive clear alerts for invalid inputs or unsupported formats.  
- **🖨️ Quality Output**: Your PDFs will look polished and professional.  

---

## **🔧 Requirements**  

Ensure these Python libraries are installed:  
- **`Pillow`**: Handles image processing.  
- **`ReportLab`**: Creates PDFs.  
- **`Tkinter`**: Provides the graphical interface.  

Install dependencies with:  
```bash  
pip install pillow reportlab  
```  

---

## **🚀 How to Use**  

1️⃣ **Download the Tool**: Clone or download the project.  

2️⃣ **Run the App**: Start the program with:  
```bash  
python main.py  
```  

3️⃣ **Convert Images to PDF**:  
- Click **Select Images** to choose files.  
- Enter a name for your PDF.  
- Click **Convert to PDF** and save the file.  

---

## **🗂️ Project Layout**  

```plaintext  
ImageToPDFConverter/  
├── main.py            # Main script  
├── README.md          # Documentation  
└── requirements.txt   # List of dependencies  
```  

---

## **⚙️ Customization Ideas**  

- **PDF Dimensions**: Change the page size in the `convert_images_to_pdf` function:  
  ```python  
  pdf = canvas.Canvas(output_pdf_path, pagesize=(595.28, 841.89))  # Default: A4 size  
  ```  
  - **For Letter size**: Use `(612, 792)`.  
  - **Other sizes**: Replace with `(width, height)` in points.  

- **Interface Enhancements**:  
  - Add themes with libraries like `ttkbootstrap`.  
  - Implement drag-and-drop for selecting files.  

---

## **🚧 Limitations**  

- Filenames with special characters may cause errors.  
- Dependency installation is required before use.  

---

## **💡 Future Upgrades**  

- **⏳ Progress Tracking**: Display progress for bulk conversions.  
- **🔒 PDF Security**: Add options for password protection.  
- **🎨 Image Editing**: Include cropping, rotation, and filters.  
- **🌍 Localization**: Support multiple languages.  
- **☁️ Cloud Storage**: Save PDFs directly to services like Google Drive or Dropbox.  

---

## **📜 License**  

This tool is released under the **MIT License**—free to use, modify, and share! 🎉  
