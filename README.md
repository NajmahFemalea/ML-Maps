# NUSA MAPS
## Overview
Nusa Maps is an Android application designed to enhance the travel experience by providing automatic recommendations for rest stops along a user’s route.
The app focuses on suggesting:<br>
⛽ Refueling stations (SPBU)<br>
💤 Rest areas<br>
🏨 Accommodations when necessary<br>
By integrating these essential services, Nusa Maps helps make long-distance travel more efficient, comfortable, and enjoyable.<br>

## Machine Learning Model
This repository contains the TensorFlow Lite (TFLite) model used in the Nusa Maps Android application. The model has been trained using TensorFlow and later converted into .tflite format to enable on-device inference — allowing predictions to be made directly on the user’s smartphone.<br>
| File | Description |
|------|--------------|
| `combined_model.tflite` | The optimized TensorFlow Lite model used in the Android app |
| `combined_model_metadata.json` | Metadata describing input/output format and preprocessing details |
