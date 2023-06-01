# Drowsiness Detection using YOLOv5 Model

The Drowsiness Detection project utilizes the YOLOv5 model for classifying whether a person is drowsy or awake. It leverages deep learning techniques and a custom dataset to train the model. The project uses PyTorch to load the YOLOv5s model and has been trained for 500 epochs. The `last.pt` weights in the directory `runs/exp5` are utilized for real-time drowsiness detection.

## Features

- **Drowsiness Classification**: The system classifies whether a person is drowsy or awake based on real-time video or image input.

- **YOLOv5 Model**: The project employs the YOLOv5s model, a state-of-the-art object detection algorithm, for accurate detection and classification.

- **Custom Dataset**: The model has been trained on a custom dataset, consisting of labeled images specifically collected for drowsiness detection.

- **PyTorch Integration**: The project uses PyTorch to load the YOLOv5s model, enabling seamless integration and efficient training.

## Installation

To set up the Drowsiness Detection project locally, follow these steps:

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/drowsiness-detection-yolov5.git
2. To see the images navigate into `images` directory
3. TO see the lables navigate into `labels` directory
4. Install the required dependencies:
   ```shell
   pip install -r requirements.txt
5. For remaining details go through the notebook `yolo5_object_detection.ipynb`
## Usage
1. Launch the project and ensure that your camera is connected or provide an image for drowsiness detection.

2. The system will detect faces in the video or image and classify each face as drowsy or awake.

3. The detected faces will be annotated with labels indicating their drowsiness status.

4. Observe the real-time drowsiness classification or analyze the results from the provided image.

5. Experiment with different scenarios, such as varying lighting conditions or different individuals, to evaluate the model's performance.
## Dataset
The drowsiness detection model has been trained on a custom dataset. Unfortunately, the dataset used for training is publicly available.

