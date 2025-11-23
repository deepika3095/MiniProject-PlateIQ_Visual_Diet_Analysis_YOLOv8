# Title of the Project

PlateIQ – AI-Based Food Recognition and Calorie Estimation System
A smart web-based system that allows users to upload food images, automatically detect food items, estimate portion sizes, and calculate calories and nutrients using YOLOv8-based segmentation and a nutritional database.

# About

PlateIQ is an AI-powered dietary assessment system designed to simplify food tracking by using real-time image recognition. Users can upload images of their meals, and the system automatically identifies individual food items, segments them, estimates portion size, and calculates calories and nutrient content.
Traditional dietary tracking methods require manual logging or visual estimation, which often leads to errors and user fatigue. PlateIQ overcomes these challenges using YOLOv8 for fast and accurate segmentation (40–150 FPS) and a nutritional database to compute calories, proteins, fats, carbohydrates, and fiber. This solution is particularly beneficial for people with diabetes, athletes, and anyone seeking personalized dietary feedback.

# Features

1. Real-time food detection and segmentation using YOLOv8.

2. High accuracy (>98%) and fast performance suitable for web and mobile use.

3. Portion size estimation using mask-based area analysis and depth scaling.

4. Integration with nutritional databases for calorie and nutrient calculation.

## Additional Dependencies:
NumPy, Pandas, scikit-learn, MiDaS (depth estimation), Flask/Streamlit for front-end deployment.
# Requirements

1. Operating System: 64-bit Windows 10 or Ubuntu

2. Python: Version 3.6 or later

3. Deep Learning Frameworks:

4. YOLOv8

5. TensorFlow

6. Image Processing Library: OpenCV

## Additional Dependencies:

1. scikit-learn

2. Version Control: Git

3. IDE: Visual Studio Code/Goosle Colab
# System Architecture

<img width="411" height="765" alt="image" src="https://github.com/user-attachments/assets/c5fde8fe-e220-45e3-8087-be554faecbdf" />

# Output
## Output 1 – Food Detection & Segmentation
<img width="342" height="342" alt="image" src="https://github.com/user-attachments/assets/bc9d7001-e76a-48bb-a2be-8a0a003edf5e" />


## Output 2 – Calorie & Nutrient Calculation
<img width="690" height="734" alt="image" src="https://github.com/user-attachments/assets/b21c94e3-65fd-4b5c-a0c6-51923025e90a" />
<img width="732" height="742" alt="image" src="https://github.com/user-attachments/assets/84e7af5d-71bc-433b-b281-4444596834ed" />
<img width="681" height="731" alt="image" src="https://github.com/user-attachments/assets/720d3b72-3956-42a6-95b1-93d4324f05c0" />
<img width="704" height="738" alt="image" src="https://github.com/user-attachments/assets/5ec42655-c101-41a5-9466-35165b7a2f91" />
<img width="720" height="760" alt="image" src="https://github.com/user-attachments/assets/9a2b6c28-7e09-4bd0-ba5d-5e14379a405c" />
<img width="688" height="733" alt="image" src="https://github.com/user-attachments/assets/0901eb81-c28c-4eee-9b47-f7765e0c3589" />
<img width="677" height="736" alt="image" src="https://github.com/user-attachments/assets/d680d824-d9be-47b2-a3fc-acebedd23d62" />

# Results and Impact

PlateIQ significantly improves dietary awareness by providing real-time, automated, and accurate food recognition. This system makes it possible for users—including diabetic individuals, fitness enthusiasts, and general users—to understand the nutritional content of their meals effortlessly.

Integrating YOLOv8 enables superior detection accuracy and speed compared to earlier CNN-based models, making it a practical solution for everyday diet monitoring. With growing reliance on smartphones and digital health tools, PlateIQ represents a scalable and accessible approach toward personalized nutrition and preventive health care.

# Articles Published / References
1. Banusharath K A et al., Applications of Hybrid Metaheuristic Algorithms for Image Processing, Springer, 2020.
2. Agarwal R. et al., Hybrid Deep Learning Algorithm-Based Food Recognition and Calorie Estimation, 2023.
