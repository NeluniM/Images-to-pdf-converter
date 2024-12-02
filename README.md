

---

# Image to PDF Converter

This is a Python-based graphical user interface (GUI) application that allows users to convert multiple image files (e.g., PNG, JPG, JPEG) into a single PDF file. The application is built using `Tkinter` for the GUI and `Pillow` and `ReportLab` libraries for image processing and PDF generation.

---

## Features

- **Select Multiple Images**: Users can select multiple image files at once using a file dialog.
- **Preview Selected Images**: Displays the names of the selected image files in a list.
- **Custom PDF Name**: Allows users to specify the name of the output PDF file.
- **Image Scaling**: Automatically scales images to fit within the dimensions of an A4 page.
- **User-Friendly Interface**: Simple and intuitive GUI for ease of use.

---

## Requirements

To run this project, you'll need Python installed along with the following libraries:

- `Tkinter` (usually included with Python installations)
- `Pillow` (Python Imaging Library)
- `ReportLab`

You can install the required libraries using pip:

```bash
pip install pillow reportlab
```

---

## How to Use

1. Clone or download this repository to your local machine.
2. Run the `main.py` file in your terminal or an IDE.
3. Follow these steps in the GUI:
   - **Select Images**: Click on the **Select Images** button to choose image files.
   - **Enter PDF Name**: Type the desired name for the output PDF (e.g., `output`).
   - **Convert to PDF**: Click the **Convert to PDF** button to generate the PDF.
4. The application will save the generated PDF in the current working directory.

---

## Code Overview

### Key Components

1. **GUI**:
   - Built with `Tkinter` for window management, buttons, labels, and listboxes.
2. **Image Selection**:
   - Uses `filedialog` to select images from the local file system.
3. **PDF Generation**:
   - Utilizes `ReportLab` to create a PDF with the selected images.
   - Resizes images to fit within A4 page dimensions while maintaining their aspect ratio.
4. **Error Handling**:
   - Includes basic error handling to manage issues with unsupported image formats or missing selections.

### File Structure

```
ImageToPDF/
│
├── main.py            # Main script for the application
├── README.md          # Documentation (this file)
└── requirements.txt   # List of dependencies (optional)
```

---

## Customization

### Modify Output Size
To change the PDF page size, edit the following line in the `convert_images_to_pdf` method:

```python
pdf = canvas.Canvas(output_pdf_path, pagesize=(612, 792))  # A4 size
```

You can replace `(612, 792)` with other dimensions, such as `letter` size `(612, 792)` or a custom size.

### Add More Features
You can extend this application to:
- Allow drag-and-drop image selection.
- Add watermarking or page numbering.
- Support other file formats.

---

## License

This project is licensed under the MIT License. Feel free to modify and distribute it as needed.

---

