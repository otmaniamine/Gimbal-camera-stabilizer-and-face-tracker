# Gimbal Camera Stabilizer and Face Tracker

Advanced camera stabilization system with real-time face tracking capabilities using computer vision.

## Description

A comprehensive gimbal control system combining hardware stabilization with intelligent face detection and tracking. The system automatically follows detected faces while maintaining smooth, stable video output.
![alt text](https://github.com/otmaniamine/Gimbal-camera-stabilizer-and-face-tracker/blob/main/figures/Stabilization%20test.jpeg)
## Features

- Real-time face detection and tracking
- 3-axis gimbal stabilization control
- Smooth motion following with predictive algorithms
- Multi-face tracking capability
- Calibration and tuning interface
- Low-latency video processing
- Hardware feedback integration

## Technology Stack

- Language: C/C++, Python
- Computer Vision: OpenCV
- Hardware Control: Arduino nano 
- Video Processing: FFmpeg
- Communication: Serial/USB protocols
![alt text](https://github.com/otmaniamine/Gimbal-camera-stabilizer-and-face-tracker/blob/main/figures/Face%20tracking%20test%20.jpeg )
## Requirements
- Camera module (USB/CSI)
- 3-axis gimbal mechanism
- Microcontroller (Arduino/STM32)
- Python 3.7+ / C++11 compiler
- OpenCV 4.0+



## Project Structure

```
Gimbal-camera-stabilizer-and-face-tracker/
├── src/
│   ├── main.py              # Main application entry
│   ├── face_tracker.py      # Face detection and tracking
│   ├── gimbal_controller.c  # Hardware control
│   ├── stabilizer.py        # Smoothing algorithms
│   └── utils.py
├── firmware/
│   ├── gimbal_firmware/
│   └── motor_control.ino
├── models/
│   └── cascade_classifier.xml
├── config.yaml
└── requirements.txt
```

## Performance

- Detection FPS: 30+ (1080p)
- Tracking latency: <50ms
- Gimbal response time: <20ms
- Power consumption: ~5W (5V, 1A)

## Future Improvements

- Multi-object tracking (not just faces)
- Gesture recognition control
- Cloud connectivity for remote operation
- Mobile app interface
- AI-powered predictive stabilization

 ![alt text](https://github.com/otmaniamine/Gimbal-camera-stabilizer-and-face-tracker/blob/main/figures/presentation%202.png)

## License

MIT License
