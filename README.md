# AI Hand Detection


A real-time hand detection system using deep learning and computer vision techniques. This project detects and tracks hands in live video streams or static images, providing bounding box coordinates and confidence scores.

## Features

- Real-time hand detection using a pre-trained deep learning model
- Supports both image and video (including webcam) inputs
- Adjustable confidence threshold for detection sensitivity
- Lightweight and efficient implementation
- Easy-to-use Python API

## Requirements

- Python 3.6+
- OpenCV
- TensorFlow/Keras (or PyTorch, depending on your implementation)
- NumPy
- Matplotlib (for visualization)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/dhruvv1402/ai-hand-detection-master.git
   cd ai-hand-detection-master
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### For Image Detection
```python
python detect.py --image path/to/image.jpg
```

### For Webcam Detection
```python
python detect.py --webcam
```

### For Video File Detection
```python
python detect.py --video path/to/video.mp4
```

### Optional Arguments
- `--threshold`: Detection confidence threshold (default: 0.7)
- `--output`: Path to save output file
- `--display`: Show real-time detection (default: True)

## Project Structure
```
ai-hand-detection-master/
├── models/                # Pre-trained model weights
├── utils/                # Utility scripts
├── detect.py             # Main detection script
├── train.py              # Training script (if applicable)
├── requirements.txt      # Dependencies
└── README.md
```


## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
[MIT License](LICENSE)

## Contact
For questions or suggestions, please contact:
- Dhruv Gupta
- GitHub: [dhruvv1402](https://github.com/dhruvv1402)

---
