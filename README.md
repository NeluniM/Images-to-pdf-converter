# 🖼️📄 **Image to PDF Converter**  

Effortlessly convert your **images** (PNG, JPG, JPEG) into **high-quality PDFs**! This powerful **Python tool** features a sleek **Tkinter GUI**, combining the capabilities of `Pillow` and `ReportLab` for outstanding results.  

---

## **✨ Highlights**  

### 📸 **Easy Image Selection**  
- Pick multiple images with a simple file dialog.  

### 🖼️ **Preview Your Choices**  
- View the selected images in a clear list.  

### ✍️ **Customizable PDF Names**  
- Set your preferred PDF filename with ease.  

### 📏 **Smart Resizing**  
- Automatically fits images to A4 size while maintaining aspect ratio.  

### 🎨 **User-Friendly Interface**  
- Clean, intuitive design for smooth navigation.  

### ⚠️ **Error Handling**  
- Alerts for unsupported formats, invalid inputs, and other issues.  

### 🖨️ **High-Quality Output**  
- Produces professional-grade PDFs every time.  

---

## **🛠️ What You’ll Need**  

Make sure the following libraries are installed:  

- **`Pillow`** 🖼️: For image processing.  
- **`ReportLab`** 📄: For creating PDFs.  
- **`Tkinter`** 🎨: Built into Python for GUI development.  

Install missing dependencies with:  
```bash  
pip install pillow reportlab  
```  

---

## **🚀 Getting Started**  

### 1️⃣ **Get the Tool**  
Download or clone the repository.  

### 2️⃣ **Launch the App**  
Run the script from your terminal or IDE:  
```bash  
python main.py  
```  

### 3️⃣ **Create Your PDF**  
- **Select Images**: Click **Select Images** and choose files.  
- **Name Your PDF**: Enter a custom filename.  
- **Generate PDF**: Click **Convert to PDF** to save the file.  

---

## **📦 Project Structure**  

```plaintext  
ImageToPDFConverter/  
├── main.py            # Main script  
├── README.md          # Documentation  
└── requirements.txt   # Dependencies list  
```  

---

## **⚙️ Customization Options**  

### ✏️ **Modify PDF Dimensions**  
Adjust the page size in the `convert_images_to_pdf` function:  
```python  
pdf = canvas.Canvas(output_pdf_path, pagesize=(595.28, 841.89))  # A4 dimensions  
```  
- **For Letter size**: Use `(612, 792)`.  
- **Custom size**: Replace with `(width, height)` in points.  

### 🎨 **Upgrade the Interface**  
- Add themes with `ttkbootstrap`.  
- Enable drag-and-drop functionality for selecting images.  

---

## **🚧 Current Limitations**  

1. **Special Characters**: Filenames with unusual symbols might cause errors.  
2. **Dependencies**: Ensure required libraries are properly installed.  

---

## **💡 What’s Coming Next?**  

- ⏳ **Progress Indicators**: Show conversion progress for larger batches.  
- 🔒 **PDF Security**: Include password-protection features.  
- 🎨 **Image Editing Tools**: Enable rotation, cropping, or filters before conversion.  
- 🌍 **Multi-Language Support**: Offer localized interfaces.  
- ☁️ **Cloud Integration**: Save PDFs directly to Google Drive or Dropbox.  

---

## **📜 License**  

Released under the **MIT License**—use, modify, and share freely! 🎉  
