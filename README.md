🧱 LEGO Piece Detection using Computer Vision
📌 Overview

Developed a classical computer vision solution to detect and count LEGO pieces using image segmentation techniques such as thresholding, edge detection, and contour analysis; compared different approaches to evaluate their effectiveness in object detection tasks.

📊 Dataset

This project uses a publicly available LEGO dataset from Kaggle:
https://www.kaggle.com/datasets/dreamfactor/biggest-lego-dataset-600-parts

Note: The dataset is not included in this repository due to size limitations.

⚙️ Techniques Used
Image Processing
Image Segmentation
Edge Detection
Contour Detection
Object Counting
🛠️ Tools & Technologies
Python
OpenCV
NumPy
Matplotlib
📂 Project Structure
README.md  
requirements.txt  
notebooks/lego_piece_detection_cv.ipynb  
outputs/results/  
▶️ How to Run
Install dependencies using requirements.txt
Open and run the notebook located in the notebooks folder
⚠️ Limitations
Sensitive to lighting conditions
Difficulty handling overlapping objects
Less robust compared to deep learning-based methods
💡 Future Improvements
Apply deep learning–based object detection (e.g., YOLO)
Improve segmentation for complex backgrounds
Enhance counting accuracy for overlapping objects