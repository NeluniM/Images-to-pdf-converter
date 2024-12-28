# 🖼️📄 **Image to PDF Converter**  

A simple yet powerful **Python application** that converts multiple images (PNG, JPG, JPEG) into a single high-quality PDF file. Featuring an intuitive **GUI built with `Tkinter`**, it leverages the power of `Pillow` and `ReportLab` to deliver seamless performance and excellent output quality.  

---

## **✨ Features**  

### 📂 **Batch Image Selection**  
- Select multiple images at once via an easy-to-use file dialog.  

### 🔍 **Preview Files**  
- View the names of the selected images before converting them.  

### ✍️ **Custom Output Name**  
- Specify a custom name for the resulting PDF document.  

### 🖼️ **Automatic Image Scaling**  
- Adjust images to fit A4 page dimensions while maintaining aspect ratio.  

### 🪄 **User-Friendly GUI**  
- Navigate effortlessly using an intuitive interface with buttons and input fields.  

### ⚠️ **Error Handling**  
- Receive alerts for invalid file types, empty fields, or other input issues.  

### 📃 **High-Quality PDFs**  
- Ensure sharp, professional-grade output for every PDF created.  

---

## **🛠️ Requirements**  

Ensure Python is installed along with the following libraries:  

- `Pillow` 📦: For image processing.  
- `ReportLab` 🖋️: For PDF generation.  
- `Tkinter` 🖼️: Pre-installed with Python by default.  

Install dependencies via:  
```bash  
pip install pillow reportlab  
```  

---

## **🚀 How to Use the App**  

### 1️⃣ **Setup**  
- Clone or download the repository to your system.  
- Navigate to the folder containing the project files.  

### 2️⃣ **Run the Application**  
- Launch the app by running `main.py` in your terminal or IDE:  
   ```bash  
   python main.py  
   ```  

### 3️⃣ **Convert Images to PDF**  
- **Select Images**: Click the **Select Images** button to choose files.  
- **Name Your PDF**: Enter the desired name for your PDF file.  
- **Generate PDF**: Click **Convert to PDF** to create and save the document.  

---

## **🔍 Key Highlights**  

### 🪄 **Simple Interface**  
- Buttons for file selection, input fields for naming the output, and a clean layout make usage effortless.  

### 🖼️ **Robust Image Processing**  
- Supports multiple formats like PNG, JPG, and JPEG, ensuring smooth conversions.  

### 📃 **Professional PDF Output**  
- Preserves image quality and formats content to fit A4 dimensions perfectly.  

### ⚠️ **Error Notifications**  
- Guides users with pop-up alerts for invalid inputs, ensuring clarity.  

---

## **📂 Project Structure**  

```plaintext  
ImageToPDFConverter/  
├── main.py            # Main script for the application  
├── README.md          # Documentation for the project  
└── requirements.txt   # List of required libraries  
```  

---

## **🔧 Customizations**  

### ✏️ **Adjust Page Dimensions**  
Modify the page size in the script’s `convert_images_to_pdf` function:  
```python  
pdf = canvas.Canvas(output_pdf_path, pagesize=(595.28, 841.89))  # A4 size  
```  

- For **Letter** size: Replace with `(612, 792)`  
- For **Custom Dimensions**: Replace with `(width, height)` in points.  

### 🎨 **Enhance the GUI**  
- Add themes or animations for a more polished appearance.  
- Enable drag-and-drop functionality for quicker file selection.  

---

## **✨ Planned Features**  

- ⏳ **Progress Indicator**: Visual feedback for large file batches.  
- 🔒 **PDF Security**: Option to set passwords for securing files.  
- 🎨 **Image Editing Tools**: Add features like rotation, cropping, and filters.  
- 🌍 **Multi-Language Support**: Translate the interface for global users.  
- ☁️ **Cloud Integration**: Save PDFs directly to Google Drive or Dropbox.  

---

## **🐞 Known Limitations**  

1. **Filename Issues**: Special characters in file names may cause errors.  
2. **Dependency Requirements**: `Pillow` and `ReportLab` must be installed.  

---

## **📜 License**  

This project is licensed under the **MIT License**, allowing you to freely use, modify, and distribute the code for personal or educational purposes.  

