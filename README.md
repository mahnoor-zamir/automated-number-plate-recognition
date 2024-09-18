# Automated Number Plate Recognition

**Automated Number Plate Recognition** is a sophisticated system designed to detect and recognize number plates from a custom dataset that includes non-standard plates. The project encompasses the entire pipeline, from data preprocessing to model training and deployment, utilizing YOLO for detection and EasyOCR for recognition.

## Features

- **Custom Dataset**: Works with a locally collected dataset featuring non-standard number plates, which poses unique challenges for detection and recognition.
- **YOLO-Based Detection**: Implements various YOLO (You Only Look Once) models to accurately detect number plates in images.
- **EasyOCR Recognition**: Utilizes EasyOCR for extracting and recognizing text from detected number plates.
- **End-to-End Pipeline**: Covers the full pipeline including data handling, model training, detection, and recognition.

## Installation

### Prerequisites

- Python 3.x
- PyTorch
- YOLOv5 (or other YOLO versions)
- EasyOCR
- OpenCV
- NumPy
- Pandas

### Setup

1. **Clone the repository:**

   git clone https://github.com/yourusername/automated-number-plate-recognition.git
   
2. **Navigate to the project directory:**

  cd automated-number-plate-recognition

3. **Create a virtual environment (optional but recommended)**:
  python -m venv venv

4. **Activate the virtual environment**

5. **Install required Python packages:**
  Create a requirements.txt file with the following content:
    torch
    torchvision
    opencv-python
    numpy
    pandas
    easyocr
  Then install them using:
    pip install -r requirements.txt

6. **Download YOLO weights and EasyOCR models:**
   YOLO Weights: Follow the instructions in the YOLO documentation to download pre-trained YOLO models and place them in the models/ directory.
   EasyOCR Model: Download the model as per the EasyOCR documentation and place it in the models/ directory.

7. **Prepare the dataset:**
   Ensure your dataset is properly formatted and place it in the data/ directory. The data/dataset.yaml file should define the dataset structure.

### Contributing
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes and commit them (git commit -am 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Open a Pull Request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Contact
For questions or feedback, please contact m.zamirrsh@gmail.com.







9. 



