# Age & Gender Detection

This project is a Python-based age and gender detection system using OpenCV and Deep Learning models.

---

## 🚀 Features
- Detect faces in an image.
- Predict age and gender using a pre-trained model.
- Display results with bounding boxes.

---

## 📂 Project Structure
```
/age-prediction
|-- gad.py  # Main script for age & gender detection
|-- models  # Contains the pre-trained models
|   |-- age_net.caffemodel
|   |-- age_deploy.prototxt
|   |-- gender_net.caffemodel
|   |-- gender_deploy.prototxt
|-- README.md  # Documentation
```

---

## 🛠️ Installation & Setup

### Prerequisites:
- Install [Python 3](https://www.python.org/downloads/)
- Install required dependencies:

```sh
pip install opencv-python numpy dlib
```

---

## 🔥 Usage
1. Place an image in the project directory.
2. Run the script:
```sh
python gad.py --image path_to_image.jpg
```
3. The script will display the detected age and gender.

---

## 💡 Future Improvements
- Optimize model inference time.
- Support for video input.

---

## 📝 License
This project is open-source and available under the MIT License.

---

### 👨‍💻 Developed By
Mo Kaif Siddiqui

