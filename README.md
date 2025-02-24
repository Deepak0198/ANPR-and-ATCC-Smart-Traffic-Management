Intelligent Traffic Management System

An AI-powered traffic management system designed to efficiently handle real-time traffic at junctions using Automatic Traffic Counting and Classification (ATCC) and Automatic Number Plate Recognition (ANPR). The system dynamically manages traffic signals based on real-time data, reducing congestion and improving traffic flow.

Features

1. Helmet Detection

   - Identifies riders not wearing helmets to ensure traffic safety compliance.

2. Triple Riding Detection

   - Detects instances of more than two riders on a two-wheeler.

3. Accident Detection

   - Recognizes accidents in real-time to trigger alerts for quicker response.

4. Heatmap Visualization

   - Displays traffic density and congestion hotspots in a visual format.

5. Automatic Number Plate Recognition (ANPR)

   - Detects and recognizes vehicle license plates for tracking and monitoring purposes.

6. Automatic Traffic Counting and Classification (ATCC)

   - Counts and classifies vehicles in real-time for better traffic management.

7. Dynamic Signal Controlling

   - Adjusts traffic signals dynamically based on real-time vehicle counts on each road.

8. Flask Integration

   - Provides backend support for managing and processing traffic data.

 Technologies Used

 Programming Language

- Python

 Libraries and Tools

- OpenCV
- YOLO (You Only Look Once) for object detection
- PyTesseract for Optical Character Recognition (OCR)
- MySQL for database management
- Flask for backend web services

Hardware Requirements

- Optional integration with cameras for real-time feed

Install the Required Dependencies

```bash
pip install -r requirements_1.txt
```

 Run the Flask App

```bash
python app.py
```

How It Works

1. The system captures real-time traffic data using cameras.
2. ATCC processes the video feed to count and classify vehicles.
3. ANPR detects vehicle license plates for tracking or violation monitoring using PyTesseract.
4. YOLO is used for object detection in the video feed.
5. The signal logic determines which road gets the green light based on traffic density.
6. Additional functionalities, such as helmet detection, triple riding detection, accident detection, and heatmap visualization.
7. Dynamic signal controlling ensures smoother traffic flow by prioritizing roads with higher vehicle density.

Future Enhancements

- Add predictive traffic flow using machine learning models.
- Integration with IoT devices for real-time sensor data.
- Expand functionality for additional violations like overspeeding.
- Improve UI/UX for better interaction.

License

This project is licensed under the MIT License. See the LICENSE file for details.

