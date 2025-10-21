# NusaMaps: AI-Powered Stop Recommendations for Long-Distance Trip Planning
## 📖 Overview
Nusa Maps is an Android application designed to enhance the travel experience by providing automatic recommendations for rest stops along a user’s route.
The app focuses on suggesting:<br>
⛽ Refueling stations (SPBU)<br>
💤 Rest areas<br>
🏨 Accommodations when necessary<br>
By integrating these essential services, Nusa Maps helps make long-distance travel more efficient, comfortable, and enjoyable.<br>

## 🤖 Machine Learning Model
This repository contains the TensorFlow Lite (TFLite) model used in the Nusa Maps Android application. The model was trained using a **Decision Tree** algorithm with **1000 data samples**, split into **70% training** and **30% testing**. The dataset can be viewed [here](./dataset/). The model has been trained using TensorFlow and later converted into **.tflite** format to enable on-device inference — allowing predictions to be made directly on the user’s smartphone.<br>
| File | Description |
|------|--------------|
| `combined_model.tflite` | The optimized TensorFlow Lite model used in the Android app |
| `combined_model_metadata.json` | Metadata describing input/output format and preprocessing details |

## ⚙️ Running the Model
Although the model runs automatically inside the Android app, you can also test it locally using Python before deployment.<br>
#### Requirements
##### Install the required library:
```bash
pip install tensorflow numpy
```
##### Clone the repository 
```bash
git clone https://github.com/NajmahFemalea/ML-Maps.git
```

> **Note:**  
> The trained `.tflite` model is integrated into the **Nusa Maps** Android application using the TensorFlow Lite Interpreter.  
> The Android team handles model integration within the app’s codebase.  
> This repository focuses on the **Machine Learning** side — model development, training, and conversion to TensorFlow Lite.
