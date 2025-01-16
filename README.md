### README.md

# Paper and Plastic Detection using YOLOv8

This repository contains a computer vision project to detect and classify paper and plastic objects using the YOLOv8 model. It leverages the Roboflow API for dataset management and Ultralytics for model training and evaluation.

## Features
- Efficient detection and classification of paper and plastic objects.
- Custom-trained YOLOv8 model.
- Interactive Gradio-based web interface for easy deployment.
- Performance metrics visualization.

## Installation

1. Clone the repository:
   ```bash
   git clone <your-repo-link>
   cd <your-repo-folder>
   ```
2. Install the required libraries:
   ```bash
   pip install ultralytics roboflow gradio matplotlib
   ```

## Training the Model
1. Authenticate with Roboflow and download the dataset.
2. Train the YOLOv8 model using the provided training scripts.

## Validation and Testing
- Run validation on the test dataset.
- Test the model to evaluate its performance on unseen data.

## Interactive Web Interface
Deploy a Gradio interface for predictions, allowing real-time detection of objects in uploaded images.

## Contributing
Feel free to submit issues or pull requests for improvements.

## License
This project is licensed under the MIT License.
