## Parking Spot Monitoring and Detection

### Overview
This project aims to develop a computer vision system for monitoring and detecting parking spots in a given area. It leverages the power of deep learning to accurately identify occupied and empty parking spaces, count the number of cars, and segment individual vehicles within the frame. The system utilizes the YOLOv8 model from the Ultralytics library for object detection and a pre-trained UNet model for image segmentation.

### Why Parking Management with AI?
Efficient parking management is crucial for urban areas to reduce traffic congestion, improve air quality, and enhance overall city planning. Traditional methods often rely on manual monitoring, which is time-consuming, prone to errors, and lacks real-time information. By employing AI-powered parking management systems, we can achieve:

* **Real-time monitoring:** Instantaneous updates on parking availability.
* **Improved traffic flow:** Reduced congestion caused by drivers searching for parking.
* **Increased revenue:** Optimized parking pricing and utilization.
* **Data-driven insights:** Valuable information for urban planning and traffic management.

### Dataset
The project utilizes a custom parking spot dataset sourced from Roboflow. The dataset comprises images of parking lots with annotated parking spaces, vehicle locations, and segmentation masks.

### Model Architecture
* **Object Detection:** YOLOv8 model from Ultralytics for detecting parking spaces and classifying them as occupied or empty.
* **Image Segmentation:** Pre-trained UNet model for segmenting individual vehicles within the detected parking spaces.

### Project Structure
```
parking_spot_monitoring/
├── models/
│   ├── yolov8.pt
│   ├── unet.pt
├── data/
│   ├── train/
│   ├── val/
│   ├── test/
├── requirements.txt
├── README.md
├── demo_output
```
### Installation
To install the project dependencies, run the following command:
```bash
git clone https://github.com/Milad0310/parking-spot-monitoring.git
```

```bash
pip install -r requirements.txt
```
### Contributions
Contributions to this project are welcome. Please open an issue or submit a pull request.
