# Object Removal using Image Inpainting

## 📌 Project Overview

This project implements an **object removal system** that removes unwanted objects from images and reconstructs the background using **image inpainting techniques**. The goal is to generate visually natural and seamless images after object removal.

The project can be used for photo cleanup, image enhancement, and as a learning reference for computer vision–based image restoration.

---

## ✨ Features

* Remove unwanted objects from images
* Seamless background reconstruction using inpainting
* Supports multiple images (dataset-based processing)
* Simple and easy-to-understand implementation
* Suitable for academic and GitHub projects

---

## 🛠️ Technologies Used

* Python
* OpenCV
* NumPy
* Matplotlib (for visualization)

---

## 📂 Project Structure

```
object-removal/
│── images/              # Input images
│── masks/               # Object masks
│── output/              # Processed images
│── main.py              # Main execution file
│── requirements.txt     # Required dependencies
│── README.md            # Project documentation
```

---

## 🚀 How It Works

1. The user provides an input image.
2. A mask is created for the object to be removed.
3. The masked region is removed from the image.
4. Inpainting is applied to fill the removed region using surrounding pixel information.
5. The final image is saved with a clean background.

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone <repository-url>
cd object-removal
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the project:

```bash
python main.py
```

---

## 📊 Sample Results

| Original Image | Mask | Output Image |
| -------------- | ---- | ------------ |
| Input Image    | Mask | Clean Image  |

---

## 🎯 Applications

* Photo cleanup
* Image restoration
* Removing unwanted objects from scenes
* Computer vision learning projects

---

## 📌 Future Enhancements

* Automatic object detection
* Deep learning–based inpainting
* GUI-based user interface
* Video object removal

---

## 👩‍💻 Author

Developed by **Thumati Sai Manichadana Devi**


