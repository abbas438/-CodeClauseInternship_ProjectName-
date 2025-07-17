# Facial Recognition using Python

This project is a basic facial recognition system developed as part of an internship under the Artificial Intelligence domain.

The system compares faces in a test image with known images and identifies whether the face is recognized. It uses the `face_recognition` library for facial encoding and OpenCV for displaying results.

---

## 🎯 Objective

- Detect faces in a test image
- Compare them with known faces
- Label them as recognized or unknown

---

## 🧰 Technologies Used

- Python
- OpenCV
- face_recognition
- NumPy

---

## 🗂️ Folder Structure

facial_recognition/
├── known_faces/
│ └── sample_face.jpg # Known face image
├── test.jpg # Image to test
├── main.py # Program file
└── README.md # Project documentation


---

## ⚙️ How to Run

1. Install the required libraries:

2. Add one or more face images to the `known_faces/` folder.

3. Add a `test.jpg` image with a face you want to check.

4. Run the program:

---

## ✅ Output

- Detects and marks all faces in the test image
- Labels recognized faces using filenames from `known_faces/`
- Labels unknown faces as "Unknown"

---

## 📌 Notes

- Use clear, front-facing images for best results
- Multiple faces in the test image can be detected
- Works offline without the need for a large dataset or training

---

## 📅 Project Status

Completed as part of an internship assignment in July 2025.
