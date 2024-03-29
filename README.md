# Face Recognition and Image Processing Toolbox
This project combines face recognition and basic image processing operations into a single Python application. It provides functionalities for face detection, face recognition, and morphological image processing.

## Description
The project includes the following features:

## Image Processing
Demonstrates basic morphological operations such as dilation, erosion, opening, and closing.
Provides thresholding techniques to create binary masks for image segmentation.

![image](https://github.com/Lkoushik29/FaceRecognition/assets/91585444/eb338349-7121-4380-bb77-627b86331d9e)

## Face Recognition
Utilizes pre-trained deep learning models for face detection and recognition.
Recognizes faces in images and videos, with options for labeling and bounding box visualization.

-> Haar Cascades

-> OpenCV Deep Learning-based Face Detection

-> ResNet SSD Face Detection

![image](https://github.com/Lkoushik29/FaceRecognition/assets/91585444/438809b5-f63a-4014-90ab-63f3d69c3cb6)

## Comparison between them
This project demonstrates a comparison of different face detection techniques using OpenCV in Python. The following techniques are implemented and compared:

![image](https://github.com/Lkoushik29/FaceRecogntion-and-ImageProcessing/assets/91585444/f4a5db43-d71a-4f5f-8a87-ace45091b0a1)

# Face Detection in Video
This is the same methods but for a video so the detection border change correspond to the face in the video

![image](https://github.com/Lkoushik29/FaceRecogntion-and-ImageProcessing/assets/91585444/45db2b9d-4a18-4ab5-94db-4563ef4385f0)



## Comparison of Face Detection Techniques

In summary, the "best" method depends on your specific requirements and constraints. If speed and resource usage are critical, Haar Cascades might be preferred. For higher accuracy and robustness, especially in challenging conditions, deep learning-based methods such as OpenCV DNN or ResNet SSD would be more suitable. It's recommended to evaluate these methods based on your specific use case and performance requirements.

If you want accurate and less errors it have to use Deeplearning-based method and resNet SSD and if you are working with small data and need the output quick it is Haar Cascades model

Requirements

-> Python (>= 3.6)

-> OpenCV (>= 4.0)

Usage
Clone the repository to your local machine:

bash

# git clone https://github.com/Lkoushik29/FaceRecognition.git

Navigate to the project directory:

cd facedetection-comparison

Run the Python script:

python face_detection_comparison.py
Press 'q' to exit the application.

## Usage

For usage instructions, please refer to the [Usage](#usage) section in the [README](README.md) file.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
