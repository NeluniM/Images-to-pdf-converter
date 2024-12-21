 



# 🖼️📄 Image to PDF Converter  

This is a **Python-based GUI application** designed to convert multiple image files (e.g., PNG, JPG, JPEG) into a single PDF file. The application uses `Tkinter` for the GUI and leverages the `Pillow` and `ReportLab` libraries for image handling and PDF creation.  

---  

## 🌟 Features  

- 📁 **Batch Image Selection**: Quickly choose multiple images at once using an intuitive file dialog.  
- 🔍 **File Preview**: Displays a list of selected image filenames before converting.  
- ✍️ **Customizable Output File Name**: Specify your preferred name for the generated PDF.  
- 🖼️ **Automatic Image Scaling**: Adjusts images to fit A4 pages while maintaining their aspect ratio.  
- 🪄 **User-Friendly Interface**: Minimalistic and intuitive GUI for hassle-free operation.  
- ⚠️ **Error Alerts**: Notifies users of invalid formats or missing inputs for a smoother experience.  

---  

## ⚙️ Requirements  

Ensure you have Python installed and the following libraries:  

- 🖌️ `Pillow` (for image processing)  
- 📄 `ReportLab` (for PDF creation)  
- 🖥️ `Tkinter` (bundled with Python by default)  

Install these libraries using:  

```bash  
pip install pillow reportlab  
```  

---  

## 🚀 How to Use  

1. **Set Up**:  
   - Clone or download the repository.  
   - Run `main.py` via terminal or an IDE.  

2. **Convert Images**:  
   - 🖼️ **Select Images**: Click on **Select Images** to pick image files.  
   - ✏️ **Enter PDF Name**: Type a name for the output PDF (e.g., `MyPDF`).  
   - 📜 **Generate PDF**: Click **Convert to PDF** to create and save the PDF in your directory.  

3. **Output**:  
   - Your PDF will be saved with the specified name and include all chosen images, scaled to fit A4 pages.  

---  

## 🔍 Code Highlights  

### Key Features  

1. **Simple GUI**:  
   - Built with `Tkinter` for intuitive buttons, labels, and file preview.  

2. **Robust Image Handling**:  
   - Utilizes `Pillow` for efficient image processing across common formats.  

3. **Seamless PDF Creation**:  
   - Leverages `ReportLab` to generate PDFs with proper formatting and scaling.  

4. **Error Handling**:  
   - Built-in alerts for unsupported formats or missing inputs for a smoother experience.  

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
To modify the page size, update this part in `convert_images_to_pdf`:  

```python  
pdf = canvas.Canvas(output_pdf_path, pagesize=(595.28, 841.89))  # A4 size (default)  
```  

Replace `(595.28, 841.89)` with:  
- Letter: `(612, 792)`  
- Custom dimensions: `(width, height)` in points.  

### Add More Features  
Enhance the app with additional features like:  
- 📂 **Drag-and-drop**: Simplify image selection further.  
- 🛠️ **Image Editing**: Add cropping, rotation, or filters.  
- 🌐 **Language Support**: Enable multilingual options for a global user base.  

---  

## 📅 Future Updates  

- ⏳ **Progress Bars**: Show conversion progress for large batches.  
- ☁️ **Cloud Sync**: Save PDFs directly to cloud storage platforms.  
- 🎨 **Advanced Editing Options**: Add tools for image effects, rotation, or cropping.  

---  

## 📜 License  

This project is licensed under the **MIT License**. Feel free to modify, use, and distribute the code as you see fit.  

---  

