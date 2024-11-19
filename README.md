# Recognition-of-gestures-and-actions

This project leverages a pre-trained deep learning model to recognize gestures and movements in images and videos. By detecting and analyzing key points on the human body, the system can identify specific poses and actions, making it useful for applications like pose estimation, activity monitoring, and gesture-based controls. 

## Features

- **Pose Detection:** Identifies key points on the human body, such as joints and limbs.
- **Gesture Recognition:** Recognizes specific gestures like raised arms or specific poses.
- **Image and Video Support:** Works with both static images and video files.
- **Real-Time Processing:** Can be adapted for live video feeds (e.g., webcam input).

## Requirements

- Python 3.7+
- OpenCV
- Matplotlib
- Numpy 

## Implementation

- Download the pre-trained model: Place your pre-trained model file (e.g., model.onnx) in the project directory.
- Insert the images and videos and perform the required task
#### Adjustable Parameters
- `threshold`: Adjust confidence threshold for key point detection (default: 0.1).
- `output`: Specify output path for processed images or videos.
#### Example Output
- Images: Processed images with key points and gesture labels are saved as PNG files in the outputs/ directory.
- Videos: Processed video frames with key points and gesture labels are combined and saved as GIF files for easy viewing.

## Acknowledgments

This project utilizes deep learning techniques and pre-trained models for pose detection, enabling fast and accurate recognition of human gestures and movements.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
