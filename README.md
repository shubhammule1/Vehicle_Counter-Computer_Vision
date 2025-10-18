# 🚗 Vehicle Detection and Counting using YOLOv8

This project is a real-time vehicle detection and counting system built using YOLOv8, OpenCV, and SORT tracking algorithm.
It detects vehicles (cars, trucks, buses, motorbikes) in a video stream, tracks them across frames, and counts how many cross a defined line.
This can be used for traffic analysis, intelligent transportation systems, or surveillance applications.

# ✨ Features

🚘 Real-time object detection using YOLOv8

🧭 Multi-object tracking with SORT algorithm

🧮 Vehicle counting when crossing a specific line

🖼️ Region masking for focused detection

📊 Real-time overlay with count display



# 🧰 Tech Stack

🐍 Python 3.x

💻 OpenCV (Computer Vision)

🤖 Ultralytics YOLOv8

📈 SORT Tracker

🪄 cvzone (UI Overlay & Graphics)

# ⚡ How It Works

Load a video and a mask image to focus on a specific region.

Detect vehicles in that region using YOLOv8.

Track objects frame by frame using SORT.

Draw a virtual line — whenever a vehicle crosses it, the counter increments.

Display the count in real-time on the video.
