  # Lane-and-Signal-Detection
An OpenCV major project to detect lanes and signals in order to aid the driver, helping create autonomous cars.
# Detection of Signal and Lane in Self-Driving Cars 🚗🛣️

This repository contains a comprehensive report and proof-of-concept implementation focused on detecting lane markings and traffic signals using computer vision techniques. The project demonstrates how traditional image processing methods and modern deep learning architectures can be combined to improve the safety and accuracy of autonomous driving systems.

## 📄 Project Overview

Autonomous vehicles rely on robust perception systems to navigate safely. Two critical components of this system are:

- **Lane Detection**: Ensures the vehicle stays centered and follows the correct path.
- **Traffic Signal Detection**: Allows the vehicle to recognize and respond appropriately to red, yellow, and green lights.

This project uses **OpenCV**, along with optional deep learning enhancements, to detect and classify both signals and lanes in real-time video streams.

## 🛠️ Technologies Used

- **Python 3.8+**
- **OpenCV 4.x**
- **NumPy**
- **Matplotlib** (for visualization)
- **(Optional) TensorFlow / PyTorch** for deep learning components

## 📁 Project Structure

├── Detection_of_Signal_and_Lane_in_Self_Driving_Cars.docx # Full project report
├── README.md # This file
├── signal_lane_detection.py # Sample implementation (optional)
├── sample_videos/ # Test videos (optional)
└── requirements.txt # Dependencies

🚀 Getting Started
1. Clone the Repository
```bash
git clone https://github.com/yourusername/self-driving-signal-lane-detection.git
cd self-driving-signal-lane-detection
```
2. Install Dependencies
```bash
pip install -r requirements.txt
```
3. Run the Application
You can run the basic signal and lane detection system on a test video:
```bash
python signal_lane_detection.py --video sample_videos/test_road.mp4
```

🧠 Key Features
Real-time lane boundary detection using edge detection and Hough Transform.

HSV-based traffic signal color recognition.

Contour detection and shape filtering for traffic light classification.

Gamma correction and adaptive brightness normalization.

Support for additional machine learning enhancements using CNNs.


📌 Future Improvements
Integrate deep learning models for robust classification (e.g., YOLOv8, SSD).

Use sensor fusion with LiDAR and radar data.

Expand training datasets with diverse traffic environments.

Improve real-time performance on edge devices.

🤝 Contributing
Contributions are welcome! Please fork the repository, make changes, and submit a pull request.


Maintainer : @divy02noob
```CSS

Let me know if you want me to generate a sample `requirements.txt`, add a sample Python implementation, or help create badges for GitHub display.
```




