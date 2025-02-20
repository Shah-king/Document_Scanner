# Document Scanner

## 📌 Overview
This project is a **Document Scanner** built using Python, OpenCV, scikit-image, and imutils. It allows users to scan and extract documents from images by detecting edges, applying perspective transformations, and thresholding for better readability.

## 🚀 Features
- Automatic document detection and edge detection.
- Perspective transformation to correct document alignment.
- Image processing techniques to enhance scanned documents.
- Converts scanned documents to binary (black & white) format for better clarity.

## 🛠️ Technologies Used
- **Python** 🐍
- **OpenCV** (for image processing and transformations)
- **scikit-image** (for advanced image processing)
- **imutils** (for easier image manipulation)

## 📦 Installation
Ensure you have Python installed (>=3.7). Then, install the required dependencies:
```bash
pip install opencv-python numpy scikit-image imutils
```

## 📂 Usage
Run the script and provide an image of a document:
```bash
python document_scanner.py --image path/to/your/document.jpg
```

### Example
```bash
python document_scanner.py --image sample_doc.jpg
```

## 📝 How It Works
1. **Preprocessing** - Converts the image to grayscale and applies Gaussian Blur.
2. **Edge Detection** - Uses Canny edge detection to find document boundaries.
3. **Contour Detection** - Finds the largest contour that resembles a document.
4. **Perspective Transformation** - Warps the document to obtain a top-down view.
5. **Thresholding** - Converts the document into a high-contrast black & white image.

## 📷 Sample Output
- **Input:** Image of a document
- **Processed Output:** A scanned and optimized version of the document

## 🤖 Future Improvements
- Add support for real-time document scanning using a webcam.
- Implement OCR (Optical Character Recognition) using Tesseract.
- Deploy as a web or mobile application.

## 📜 License
This project is open-source and available under the **MIT License**.

---

🔥 **Contributions & Feedback**
Feel free to fork this repo, open issues, or contribute! If you have any suggestions, drop them in the issues section. 😊

