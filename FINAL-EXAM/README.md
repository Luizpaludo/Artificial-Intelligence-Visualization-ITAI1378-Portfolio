# Final-Exam-ITAI1378
# License plate detector + gate opener.

## Project overview
The original goal of this project was to build a license plate detection system using the YOLO object detection model. During development, the project was expanded into a complete AI-powered gate access system.
The final system detects a vehicle's license plate using a custom-trained YOLO11 model, extracts the license plate text using EasyOCR, and compares the detected plate with a database of authorized vehicles. Based on the comparison, the system displays either **Access Granted** or **Access Denied**.

---

## Features
- Custom-trained YOLO11 license plate detector
- License plate text recognition using EasyOCR
- Authorized vehicle database
- Automatic access decision
- Detection results displayed with bounding boxes and recognized text

---

## Technologies Used
- Python
- Google Colab
- Ultralytics YOLO11
- EasyOCR
- OpenCV
- Pandas
- NumPy

---

## Repository Contents
```
notebooks/
    Final_Project_gate_opener.ipynb
    authorized_plates.csv

docs/
    AI_usage_log.md
    presentation.pdf

results/
    Sample predictions and model evaluation results

README.md
requirements.txt
```

---

## How to Run
1. Install the required libraries listed in `requirements.txt`.
2. Open `Final_Project_gate_opener.ipynb` in Google Colab or Jupyter Notebook.
3. Download the License_Plate_Dataset from the link and upload the authorized_plates.csv and the My_personal_dataset_2.zip.
4. Run the notebook cells in order.
5. Test the system using the provided sample images.

---

## Results
The completed project successfully detects license plates, recognizes the license plate characters, and determines whether a vehicle is authorized based on a predefined database.

---

## Demo Video
[(https://www.youtube.com/watch?v=uJrTQi0Emhg)]

---

## Author
Luiz Paludo
Houston City College
Associate of Applied Science in Artificial Intelligence
