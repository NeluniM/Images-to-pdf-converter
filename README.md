 



# 🖼️📄 Image to PDF Converter  

This is a **Python-based GUI application** designed to convert multiple image files (e.g., PNG, JPG, JPEG) into a single PDF file. The application uses `Tkinter` for the GUI and leverages the `Pillow` and `ReportLab` libraries for image handling and PDF creation.  

---  

## 🌟 Features  

- 📂 **Batch Image Selection**: Easily select multiple images at once through a user-friendly file dialog.  
- 📝 **File Preview**: Displays the names of selected images in a list before conversion.  
- 🖋️ **Customizable Output File Name**: Specify a name for the generated PDF.  
- 📏 **Automatic Image Scaling**: Resizes images to fit A4 pages while maintaining aspect ratio.  
- 🎨 **Simple GUI**: Clean and intuitive interface for seamless operation.  
- 🚨 **Error Notifications**: Alerts users about invalid file formats or missing inputs.  

---  

## ⚙️ Requirements  

Make sure you have Python installed and the following libraries:  

- 🖌️ `Pillow` (for image processing)  
- 📄 `ReportLab` (for PDF creation)  
- 🖥️ `Tkinter` (usually bundled with Python)  

Install these libraries by running:  

```bash  
pip install pillow reportlab  
```  

---  

## 🚀 How to Use  

1. **Set Up**:  
   - Download or clone the repository.  
   - Open a terminal or IDE and run `main.py`.  

2. **Convert Images**:  
   - 🖼️ **Select Images**: Click **Select Images** to choose image files.  
   - 🖋️ **Enter PDF Name**: Type a name for your PDF (e.g., `MyPDF`).  
   - 📄 **Generate PDF**: Click **Convert to PDF** to create and save the PDF in the current directory.  

3. **Output**:  
   - The PDF will be saved with the specified name and include all selected images, resized to fit A4 pages.  

---  

## 🔍 Code Highlights  

### Key Features  

1. **User-Friendly Interface**:  
   - Built with `Tkinter` for labels, buttons, and file list preview.  

2. **Image Handling**:  
   - The `Pillow` library processes images efficiently and supports common formats.  

3. **PDF Generation**:  
   - `ReportLab` creates a PDF where each image fits an A4 page.  

4. **Error Handling**:  
   - Alerts users about unsupported file formats or other issues to ensure smooth operation.  

### File Structure  

```
ImageToPDFConverter/  
│  
├── main.py            # Main script to run the application  
├── README.md          # Documentation (this file)  
└── requirements.txt   # Dependencies list  
```  

---  

## 🔧 Customization Options  

### Change PDF Page Size  
To adjust the page size, modify the following in `convert_images_to_pdf`:  

```python  
pdf = canvas.Canvas(output_pdf_path, pagesize=(595.28, 841.89))  # A4 size (default)  
```  

Replace `(595.28, 841.89)` with:  
- Letter: `(612, 792)`  
- Custom dimensions: `(width, height)` in points.  

### Add More Features  
You can enhance the app by adding:  
- 📂 **Drag-and-drop** functionality for easier image selection.  
- 🖋️ **Advanced Editing**: Allow cropping, rotation, or filters before conversion.  
- 🌍 **Localization**: Add multilingual support for a global audience.  

---  

## 📅 Future Updates  

- ⏳ **Progress Indicators**: Show progress for large image batches.  
- ☁️ **Cloud Integration**: Save PDFs directly to platforms like Google Drive or Dropbox.  
- ✂️ **Advanced Editing Options**: Add tools for image rotation, cropping, or effects before conversion.  

---  

## 📜 License  

This project is licensed under the **MIT License**. Feel free to modify, use, and share the code as needed.  

---  

Enjoy converting your images to PDFs with ease! 🎉  

