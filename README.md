# Yoga_detection
# Yoga Pose Detection

## Overview

This project aims to detect and classify yoga poses from images using Mediapipe and OpenCV. It involves pose detection, angle calculation between key body landmarks, and classification of the detected pose.

## Installation

1. Clone this repository: `git clone https://github.com/your-username/yoga-pose-detection.git`
2. Navigate to the project directory: `cd yoga-pose-detection`
3. Install the necessary dependencies: `pip install -r requirements.txt`

## Usage

1. Ensure Python is installed.
2. Install the required libraries mentioned above.
3. Prepare your dataset of images containing different yoga poses.
4. Update the Python script (`yoga_pose_detection.py`) with your data preprocessing, model training, and evaluation code.
5. Run the Python script to execute the pose detection and classification tasks.
6. Review the evaluation metrics and adjust the model as needed.

## Files

- `yoga_pose_detection.py`: Python script containing code for pose detection, angle calculation, and pose classification.
- `requirements.txt`: List of Python dependencies needed for this project.

## Approach

1. **Pose Detection**: Load your image and use Mediapipe to detect pose landmarks.
2. **Angle Calculation**: Calculate angles between key body landmarks to understand the pose geometry.
3. **Pose Classification**: Classify the detected pose based on the calculated angles and predefined criteria.
4. **Model Training (if applicable)**: Train a machine learning model using the detected landmarks and angles to improve classification accuracy.
5. **Model Evaluation**: Evaluate the model's performance using metrics such as accuracy, precision, and recall.
6. **Visualization**: Visualize the detected landmarks, angles, and classification results on the images.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-improvement`).
3. Implement your changes or enhancements.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-improvement`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
