# Smart Surveillance System

## Overview

The Smart Surveillance System is a sophisticated multi-object (human) detection and tracking system designed for public environments. It leverages advanced computer vision techniques and machine learning models to provide real-time insights into human activities. Key features include object detection, object tracking, object counting, region waiting time calculation, walk flow detection and Re-Identification.

## **Here is a demo containing the project output:**
![Smart Surveillance System](https://github.com/supunlakshan100/Smart-Surveillance-System/blob/main/OutputVideos/sample_outputvideo.gif?raw=true)


## Features

- **Human Detection:** Utilizes a custom-trained YOLOv8 model for accurate human detection.
- **Object Tracking:** Employs advanced tracking algorithms such as Deep SORT, ByteTrack, and FairMOT to maintain continuous tracking of detected objects.
- **Re-Identification:** Enhances tracking by re-identifying individuals across different camera views and time intervals.
- **Region Object Counting:** Counts the number of objects in specified regions.
- **Region Waiting Time Calculation:** Computes the time objects spend in designated regions.
- **Walk Flow Detection:** Analyzes and visualizes the flow of movement within the surveillance area.

## Technologies Used

- **Computer Vision:** OpenCV
- **Detection Model:** YOLOv8 (custom-trained)
- **Programming Language:** Python
- **Tracking Algorithms:** Deep SORT, ByteTrack, FairMOT
- **Framework:** PyTorch

## Project Details

This project showcases the implementation of a high-level surveillance system designed to enhance security and monitoring in public areas. The system integrates multiple advanced technologies to deliver precise and actionable insights.

### Human Detection and Tracking

The system uses a custom-trained YOLOv8 model for human detection, ensuring high accuracy and efficiency. The detection is followed by tracking algorithms like Deep SORT, ByteTrack, and FairMOT, which provide robust and reliable tracking capabilities.

### Re-Identification

The Re-Identification feature allows the system to recognize and track individuals across different camera views and over time, enhancing the overall tracking performance and providing more comprehensive surveillance coverage.

### Region-Based Analysis

To offer more in-depth analysis, the system includes features like region object counting and waiting time calculation. These features help in understanding crowd density and movement patterns within specific areas, contributing to better management and planning.

### Walk Flow Detection

The walk flow detection feature visualizes the movement patterns of individuals, aiding in the analysis of crowd behavior and the identification of potential issues in public space management.

## Note

Due to the sensitive nature of the project, the source code is not publicly available. However, the results and methodologies used are described in this README to provide an overview of the capabilities and functionalities of the system.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [YOLOv8](https://github.com/ultralytics/yolov8)
- [OpenCV](https://opencv.org/)
- [Deep SORT](https://github.com/nwojke/deep_sort)
- [ByteTrack](https://github.com/ifzhang/ByteTrack)
- [FairMOT](https://github.com/ifzhang/FairMOT)
- [PyTorch](https://pytorch.org/)
