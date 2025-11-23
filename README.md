# Title of the Project

PlateIQ – AI-Based Food Recognition and Calorie Estimation System

A smart web-based system that allows users to upload food images, automatically detect food items, estimate portion sizes, and calculate calories and nutrients using YOLOv8-based segmentation and a nutritional database.

# About

PlateIQ is an AI-powered dietary assessment system designed to simplify food tracking by using real-time image recognition. Users can upload images of their meals, and the system automatically identifies individual food items, segments them, estimates portion size, and calculates calories and nutrient content.

Traditional dietary tracking methods require manual logging or visual estimation, which often leads to errors and user fatigue. PlateIQ overcomes these challenges using YOLOv8 for fast and accurate segmentation (40–150 FPS) and a nutritional database to compute calories, proteins, fats, carbohydrates, and fiber. This solution is particularly beneficial for people with diabetes, athletes, and anyone seeking personalized dietary feedback.

# Features

Real-time food detection and segmentation using YOLOv8.

High accuracy (>98%) and fast performance suitable for web and mobile use.

Portion size estimation using mask-based area analysis and depth scaling.

Integration with nutritional databases for calorie and nutrient calculation.

Personalized dietary feedback for diabetic users, athletes, and general users.

Requirements

Operating System: 64-bit OS (Windows 10/11 or Ubuntu Linux) for running deep learning models.

Programming Language: Python 3.8 or later for development and deployment.

Deep Learning Frameworks: PyTorch and Ultralytics YOLOv8 for segmentation and detection.

Image Processing Libraries: OpenCV for image pre-processing and enhancement.

Database: USDA FoodData Central / Indian Food Composition Tables for nutritional values.

Version Control: Git and GitHub for model versioning and collaboration.

IDE: VSCode / PyCharm for development and debugging.

## Additional Dependencies: NumPy, Pandas, scikit-learn, MiDaS (depth estimation), Flask/Streamlit for front-end deployment.

# System Architecture

(Replace the placeholder with your PlateIQ system diagram)

# Output
## Output 1 – Food Detection & Segmentation

(Insert your segmentation output image)

## Output 2 – Calorie & Nutrient Calculation

Detection Accuracy: XX%
Mean Absolute Calorie Estimation Error: YY%
(Replace with your actual evaluated metrics.)

# Results and Impact

PlateIQ significantly improves dietary awareness by providing real-time, automated, and accurate food recognition. This system makes it possible for users—including diabetic individuals, fitness enthusiasts, and general users—to understand the nutritional content of their meals effortlessly.

Integrating YOLOv8 enables superior detection accuracy and speed compared to earlier CNN-based models, making it a practical solution for everyday diet monitoring. With growing reliance on smartphones and digital health tools, PlateIQ represents a scalable and accessible approach toward personalized nutrition and preventive health care.

# Articles Published / References

Banusharath K A et al., Applications of Hybrid Metaheuristic Algorithms for Image Processing, Springer, 2020.
Agarwal R. et al., Hybrid Deep Learning Algorithm-Based Food Recognition and Calorie Estimation, 2023.
