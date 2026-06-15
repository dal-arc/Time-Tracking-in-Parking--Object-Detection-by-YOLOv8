# Time-Tracking-in-Parking--Object-Detection-by-YOLOv8

## Project Overview

This project focuses on detecting and tracking vehicles in a parking lot using a deep learning-based object detection model. The system aims to automate vehicle monitoring by identifying different vehicle types, tracking their movement, measuring the time each vehicle spends parked, and analyzing vehicle color using image processing techniques.
The main goal of this project is to support smarter parking lot management by reducing manual monitoring, improving organization, and generating useful statistical insights about parking usage patterns.

## Project Objectives

* Detect vehicles in a parking lot environment.
* Track vehicles across video frames.
* Measure the parking duration for each detected vehicle.
* Analyze vehicle color using image processing.
* Generate statistical reports about vehicle activity and parking behavior.
* Improve parking lot monitoring through automation and data-driven insights.

## Model Training: YOLOv8 Nano

The object detection model used in this project is based on **YOLOv8 Nano (YOLOv8n)**. YOLOv8 provides multiple model versions with different trade-offs between speed, model size, and detection accuracy.

## Transfer Learning and Fine-Tuning
Instead of training the model from scratch, this project uses a pre-trained **YOLOv8 Nano model** and fine-tunes it on a custom dataset.

This approach applies **Transfer Learning**, where the model benefits from knowledge learned from large-scale datasets and adapts it to the target detection task. Fine-tuning helps reduce training time and improves detection performance compared to building a model from the beginning.


## Tools and Libraries Used

*
*
*
*

## Project Status

This project includes object detection, vehicle tracking, color analysis, parking duration calculation, and statistical reporting. Further improvements may include enhancing tracking accuracy, improving color classification, optimizing real-time performance, and expanding the reporting dashboard.

