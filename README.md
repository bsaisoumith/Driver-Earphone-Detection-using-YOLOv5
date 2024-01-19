Driver Earphone Detection using YOLOv5

This project utilizes YOLOv5 to detect the presence of earphones or headphones on drivers, promoting safe driving practices. 
The model is trained on a custom dataset to accurately identify earphone usage specifically in the context of drivers.

## Requirements

- Python 3.x
- PyTorch (refer to the [official PyTorch website](https://pytorch.org/) for installation instructions)
- OpenCV (`pip install opencv-python`)
- YOLOv5 (install using the instructions provided in the [YOLOv5 GitHub repository](https://github.com/ultralytics/yolov5))

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/bsaisoumith/Driver-Earphone-Detection-using-YOLOv5
   
2. Navigate to the project directory:
   cd Driver-Earphone-Detection-using-YOLOv5

3. Install the required dependencies:
   pip install -r requirements.txt
   
4. Download the YOLOv5 pre-trained weights:
   python download_weights.py

## Usage

- To detect earphones on drivers in an image, run the following command
  python detect.py --source path/to/your/image.jpg

- To detect in a video stream, run:
  python detect.py --source 0

## Customization

If you want to train the model on your custom dataset, refer to the YOLOv5 documentation for training instructions. 
You can use the provided data.yaml file for configuration.

## Results

Include sample images or video frames with the detections highlighted to showcase the performance of your model.
