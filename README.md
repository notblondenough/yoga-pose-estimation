# AI-Powered Yoga Pose Estimation System

## Project Overview

This project develops an AI-powered system to assist yoga practitioners in achieving accurate poses using advanced computer vision and machine learning techniques.

### Problem Statement

Traditional yoga learning methods often lack real-time, personalized feedback. This system addresses these challenges by:
- Providing immediate pose accuracy assessment
- Offering targeted feedback on body alignment
- Helping prevent potential injuries
- Enhancing overall yoga practice effectiveness

## Features

- **Real-Time Pose Estimation**: Uses MediaPipe for accurate human pose detection
- **Confidence-Based Pose Classification**: Machine learning model classifies detected poses
- **Dynamic Feedback**: Provides specific, actionable guidance on pose corrections
- **Multiple Approach Support**: Includes both Machine Learning and Deep Learning models

## Supported Yoga Poses
1. ArdhaChandrasana
2. BaddhaKonasana
3. Downward Dog Pose
4. Natarajasana
5. Triangle Pose
6. UtkataKonasana
7. Veerabhadrasana
8. Vrukshasana

## Tech Stack

- **Programming Language**: Python
- **Libraries & Frameworks**:
  - MediaPipe
  - OpenCV
  - scikit-learn
  - TensorFlow
  - NumPy
  - Pandas

## Installation

1. Clone the repository
```bash
git clone https://github.com/notblondenough/yoga-pose-estimation.git
cd yoga-pose-estimation
```

2. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install required dependencies
```bash
pip install -r requirements.txt
```

## Usage

Run the main script:
```bash
python detection2.py
```

### Key Controls
- Press 'q' to quit the application

## Model Performance
- 97.44% Accuracy
- Minimum Classification Confidence: 65%

## Future Roadmap

1. Add voice-based feedback
2. Expand pose support
3. Enhance detection accuracy with advanced deep learning models
4. Develop mobile and web-based versions

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements

- Dr. Sandeep Saini (Faculty Mentor)
- Research inspiration: Debabrata Swain et al.

## Project Team

- Alok Ranjan Shukla (22UCS014)
- Suyash Mittal (22UCS215)
