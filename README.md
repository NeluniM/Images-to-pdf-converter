# 🖼️📄 **Image to PDF Converter**  

Transform your **images** (PNG, JPG, JPEG) into high-quality **PDFs** with ease! This Python-based tool combines the power of **Tkinter GUI**, `Pillow`, and `ReportLab` for a seamless experience.  

---

## **✨ Amazing Features**  

- **📸 Effortless Selection**: Choose multiple images in just a few clicks.  
- **🖼️ File Previews**: See selected images before converting them.  
- **✍️ Name Your PDF**: Create a custom file name with ease.  
- **📏 A4 Resizing**: Automatically fit images to A4 size without distortion.  
- **🎨 Intuitive Interface**: Enjoy a user-friendly GUI that’s simple to navigate.  
- **⚠️ Error Handling**: Receive clear notifications for unsupported formats or issues.  
- **🖨️ Professional Output**: Generate polished, high-quality PDF documents.  

---

## **🔧 What You Need**  

Ensure you have the following Python libraries installed:  
- **`Pillow`**: For image processing tasks.  
- **`ReportLab`**: To handle PDF creation.  
- **`Tkinter`**: For building the graphical interface.  

Install dependencies easily with:  
```bash  
pip install pillow reportlab  
```  

---

## **🚀 Steps to Use**  

1️⃣ **Get the Tool**: Clone or download the project files to your local machine.  

2️⃣ **Launch the App**: Open a terminal and run:  
```bash  
python main.py  
```  

3️⃣ **Convert Images to PDF**:  
- Click **Select Images** to add your files.  
- Enter your desired PDF name in the input box.  
- Hit **Convert to PDF** and save the file to your chosen location.  

---

## **🗂️ File Organization**  

```plaintext  
ImageToPDFConverter/  
├── main.py            # Main application code  
├── README.md          # Instructions and details  
└── requirements.txt   # List of dependencies  
```  

---

## **⚙️ Make It Your Own**  

- **Change Page Size**: Adjust dimensions in the `convert_images_to_pdf` function:  
  ```python  
  pdf = canvas.Canvas(output_pdf_path, pagesize=(595.28, 841.89))  # A4 size  
  ```  
  - **Switch to Letter**: Use `(612, 792)`.  
  - **Custom Sizes**: Provide `(width, height)` in points as needed.  

- **Upgrade the Interface**:  
  - Add stylish themes with libraries like `ttkbootstrap`.  
  - Enable drag-and-drop for easier file selection.  

---

## **🚧 Known Limitations**  

- Special characters in file names may cause errors.  
- Dependencies must be pre-installed for the tool to work.  

---

## **💡 Upcoming Features**  

- **⏳ Progress Indicator**: Show real-time progress for large file batches.  
- **🔒 PDF Security**: Add password protection for your PDFs.  
- **🎨 Editing Options**: Crop, rotate, or apply filters to images before conversion.  
- **🌍 Language Support**: Make the app usable in multiple languages.  
- **☁️ Cloud Saving**: Upload PDFs directly to services like Google Drive or Dropbox.  

---

## **📜 License Information**  

This tool is open-source under the **MIT License**—you’re free to use, modify, and share it! 🎉
