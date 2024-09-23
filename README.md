# README

## Introduction
This README provides instructions on how to run the `track_func.py` script with specific parameters.

## Prerequisites
Before running the script, make sure you have the following:
- Python installed on your system
- The necessary dependencies installed (e.g., OpenCV, ByteTrack)

## Usage
To run the script with the desired parameters, follow these steps:

1. Open a terminal or command prompt.
2. Navigate to the directory where the `track_func.py` script is located.
3. Execute the following command:

```bash
python track_func.py --yolo-weights yolov8m.engine --tracking-method bytetrack --device 0 --show-vid --classes 0
```

## Parameters
- `--yolo-weights`: Specify the path to the YOLO weights file (`yolov8m.engine` in this case).
- `--tracking-method`: Choose the tracking method (`bytetrack` in this case).
- `--device`: Specify the device to be used (e.g., GPU index 0).
- `--show-vid`: Enable video display during tracking.
- `--classes`: Specify the classes to be tracked (0 in this case).

## Conclusion
By following the steps outlined in this README, you should be able to run the `track_func.py` script with the provided parameters successfully.
