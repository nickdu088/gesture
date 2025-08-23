# Real-time Gesture Skeleton Tracking

A real-time gesture recognition web application based on MediaPipe Hands, TensorFlow.js, and Fingerpose, supporting both Chinese and English interfaces.

**Demo:** [https://nickdu088.github.io/gesture/](https://nickdu088.github.io/gesture/)

*中文说明看这里： [README-cn.md](https://github.com/nickdu088/gesture/blob/main/README-cn.md).*

## Features

- Real-time detection and tracking of hand skeleton keypoints.
- Recognition of common gestures (e.g., thumbs up, victory, fist, open palm).
- Supports bilingual interface (Chinese and English).
- Compatible with mainstream browsers without the need for additional software installation.
- Efficient inference using TensorFlow.js and MediaPipe Hands.

## Preview

![Screenshot Example](screenshot.png)

## How to Use

1. Clone or download the project code:

   ```bash
   git clone https://github.com/nickdu088/gesture.git
   cd gesture
2. Open the index.html file directly in your browser (no server setup required).

3. Grant the webpage access to your camera.

4. Click the language switch button in the top right corner to toggle between Chinese and English.

5. Perform gestures in front of the camera to see real-time recognition results.

## Tech Stack

*MediaPipe Hands — Hand keypoint detection.

* TensorFlow.js — Browser-based machine learning inference.

* Fingerpose — Gesture recognition library.

* Tailwind CSS — Page styling.

* Multi-language Support

* The page supports both Chinese and English. Click the button in the top right corner to switch languages.

* All interface text and status logs synchronize with the selected language.

## Contributing

Contributions are welcome! Please submit issues and pull requests to improve features or fix bugs.
Adhere to the project's coding standards and maintain clear commit messages.
