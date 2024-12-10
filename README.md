---

# Image to PDF Converter

This is a Python-based graphical user interface (GUI) application designed to convert multiple image files (e.g., PNG, JPG, JPEG) into a single PDF file. The application uses `Tkinter` for the GUI and leverages the `Pillow` and `ReportLab` libraries for image handling and PDF creation.

---

## Features

- **Batch Image Selection**: Select multiple images simultaneously through an easy-to-use file dialog.
- **File Preview**: View the names of selected image files in a list before conversion.
- **Customizable Output File Name**: Specify a desired name for the resulting PDF.
- **Automatic Image Scaling**: Resizes images to fit A4 page dimensions while preserving aspect ratio.
- **Simple GUI**: Clean and intuitive interface for effortless operation.
- **Error Notifications**: Alerts users about invalid file formats or missing inputs.

---

## Requirements

To run the application, ensure you have Python installed and the following libraries:

- `Tkinter` (bundled with most Python installations)
- `Pillow` (Python Imaging Library for image processing)
- `ReportLab` (for PDF generation)

Install the required libraries with:

```bash
pip install pillow reportlab
```

---

## How to Use

1. **Set Up**:
   - Download or clone this repository.
   - Open your terminal or IDE and run `main.py`.

2. **Convert Images**:
   - **Select Images**: Click on **Select Images** to choose multiple image files.
   - **Enter PDF Name**: Provide a name for the PDF (e.g., `MyPDF`).
   - **Generate PDF**: Click **Convert to PDF** to create and save the PDF in the current directory.

3. **Output**:
   - The PDF will be saved with the specified name and will include all selected images, resized to fit A4 pages.

---

## Code Highlights

### Core Features

1. **User-Friendly Interface**:
   - Built using `Tkinter` for labels, buttons, and a file list preview.
   
2. **Image Handling**:
   - The `Pillow` library ensures compatibility with common image formats and supports resizing.

3. **PDF Generation**:
   - `ReportLab` generates a PDF where each image fits an A4-sized page.
   
4. **Resilience**:
   - Includes basic error handling to address invalid file formats or other common issues.

### File Structure

```
ImageToPDFConverter/
│
├── main.py            # Main script to run the application
├── README.md          # Documentation (this file)
└── requirements.txt   # Dependencies list
```

---

## Customization Options

### Adjust PDF Page Size
Modify the page dimensions in the `convert_images_to_pdf` function:

```python
pdf = canvas.Canvas(output_pdf_path, pagesize=(595.28, 841.89))  # Default A4 size in points
```

For other sizes, such as Letter `(612, 792)` or custom dimensions, replace the `(595.28, 841.89)` tuple accordingly.

### Add Features
Enhance the app by adding:
- Drag-and-drop functionality for image selection.
- Advanced options like adding page numbers or watermarks.
- Support for additional file types (e.g., GIF, BMP).

---

## Future Updates

Planned updates for the application:
- **Progress Indicators**: Display conversion progress for large batches of images.
- **Cloud Integration**: Option to save PDFs directly to cloud storage like Google Drive.
- **Advanced Editing**: Add rotation, cropping, or filters to images before conversion.

---

## License

This project is licensed under the MIT License. You are free to modify, use, and distribute the code as needed.

---
