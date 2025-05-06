# 3D-Model-Generator-Project
A Python tool to convert images/text into 3D printable models

## 📝 Project Description
This project converts either:
- An **image input** (JPEG/PNG) of a single object (e.g., chair, car) 
- Or a **text prompt** (e.g., "a small toy car")

into a basic 3D model in OBJ or STL format using AI-powered 3D generation.

## 🛠️ Technologies Used
- Python 3.8+
- Shap-E (for 3D generation)
- OpenCV (for image processing)
- Trimesh (for 3D visualization)

## 📂 File Structure
project_folder/
├── main.py # Main Python script
├── requirements.txt # Dependency list
├── README.md # This file
├── input/ # Optional: Sample input images
│ └── sample.jpg
└── output/ # Optional: Generated 3D models
├── model.obj
└── model.stl
