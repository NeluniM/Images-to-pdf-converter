# 🖼️📄 **Image to PDF Converter**  

Convert your **images** (PNG, JPG, JPEG) into **professional-quality PDFs** effortlessly! This Python-powered tool features a modern **Tkinter GUI** and utilizes `Pillow` and `ReportLab` for exceptional results.  

---

## **✨ Features You'll Love**  

- **📸 Easy Image Selection**: Pick multiple images in a snap.  
- **🖼️ Preview Files**: Quickly view selected images before converting.  
- **✍️ Custom Naming**: Define your preferred PDF file name.  
- **📏 Automatic Resizing**: Fit images to A4 size seamlessly, with no distortion.  
- **🎨 User-Friendly GUI**: Navigate through a clean and simple interface.  
- **⚠️ Error Notifications**: Get clear alerts for unsupported files or inputs.  
- **🖨️ Polished Output**: Produce PDFs with top-notch quality.  

---

## **🔧 Prerequisites**  

Ensure the following Python libraries are installed:  
- **`Pillow`**: For image processing.  
- **`ReportLab`**: To create PDF files.  
- **`Tkinter`**: For the graphical interface.  

Install dependencies with a single command:  
```bash  
pip install pillow reportlab  
```  

---

## **🚀 How to Get Started**  

1️⃣ **Download the Tool**: Clone or download the project files.  

2️⃣ **Run the App**: Open a terminal and execute:  
```bash  
python main.py  
```  

3️⃣ **Create Your PDF**:  
- Use **Select Images** to choose the files.  
- Enter a name for your PDF in the input field.  
- Click **Convert to PDF** and save your file in the desired location.  

---

## **🗂️ Project Structure**  

```plaintext  
ImageToPDFConverter/  
├── main.py            # Main application script  
├── README.md          # Documentation  
└── requirements.txt   # Dependency list  
```  

---

## **⚙️ Customization Tips**  

- **Adjust PDF Size**: Change page dimensions in the `convert_images_to_pdf` function:  
  ```python  
  pdf = canvas.Canvas(output_pdf_path, pagesize=(595.28, 841.89))  # A4 size  
  ```  
  - **For Letter size**: Use `(612, 792)`.  
  - **Other sizes**: Replace with `(width, height)` in points.  

- **Improve the GUI**:  
  - Add modern themes using libraries like `ttkbootstrap`.  
  - Enable drag-and-drop functionality for selecting files.  

---

## **🚧 Limitations**  

- Filenames containing special characters may lead to errors.  
- Requires Python dependencies to be installed beforehand.  

---

## **💡 Future Enhancements**  

- **⏳ Progress Bar**: Visualize the conversion process for large batches.  
- **🔒 Secure PDFs**: Add password protection features.  
- **🎨 Editing Tools**: Include options for cropping, rotating, and applying filters.  
- **🌍 Multi-Language Support**: Make the tool accessible globally.  
- **☁️ Cloud Integration**: Save PDFs directly to platforms like Google Drive or Dropbox.  

---

## **📜 License**  

This project is open-source and available under the **MIT License**—use, modify, and share freely! 🎉  
