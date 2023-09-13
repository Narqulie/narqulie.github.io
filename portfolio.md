---
layout: page
title: Portfolio
---

## Python Projects:

I have been learning Python for a while now, and I have been using it for various projects. My interests are in data analysis and management, web scraping and automation. I've used Python professionally for automation and REST API integrations.
I have an interest in making my code readable and clean. I also like logging and documenting my work to make it easier to understand and maintain.

### [Python_eye](https://github.com/Narqulie/Python_eye)
##### Computer vision exercises using OpenCV and Python
![Python_eye](/images/python_eye_ss.png)

This is a test-case project for python and computer vision, using CV2. The program uses a simple Command Line Interface (CLI) for user interactions. It has multiple different functions:
* Training a face recognition model with reference pictures
* Analysing a live webcam feed and labelling recognized people
* Eye tracking
It's a living work in progress where I try out different computer vision related ideas and functionalities.

### [Tuner](https://github.com/Narqulie/Tuner)
##### Audio processing exercises using Python
![Tuner](/images/tuner_ss.png)

Have YOU ever wanted a bad tuner for any instrument? 
This is a simple tuner program that uses the microphone to listen to the instrument and displays the frequency of the sound. It can be used for the tuning of any instrument, but it's not very good at it. It's a fun little project that I made to learn about audio processing and FFT.
* Using FFT (Fast Fourier Transform) to detect the peak frequency of an audio signal in real-time.
* Displaying a tuning bar, with red indicating lower frequencies and green for higher frequencies.
* Continuously averaging detected frequencies for smoother and more stable readings.
* Matching the detected frequency with the nearest musical note based on Western traditional tuning.

### [Microphone_sensor_HA](https://github.com/Narqulie/Microphone_sensor_HA)
##### Audio processing and MQTT integration using Python
![Microphone_sensor_HA](/images/microphone_ss.png)

This Python script uses a microphone to detect noise levels and sends the status to an MQTT broker. The noise level status can then be used by Home Assistant or any other platform that can subscribe to the MQTT topic.
* Real-time Noise Monitoring: The script harnesses the power of a microphone to continuously monitor and evaluate ambient noise levels.
* Integration with MQTT: Once the noise status is determined, it is promptly relayed to an MQTT broker. This seamless integration ensures the script's compatibility with platforms like Home Assistant, allowing users to tap into the noise data conveniently.
* Adaptive Noise Detection: Instead of relying on a static threshold, the script uses a dynamic thresholding mechanism. It recalculates the noise threshold every 5 seconds. This ensures the system remains responsive to sudden changes in noise levels.
* User-friendly Configuration and Logging: To enhance user experience, the script offers an easily editable configuration file for MQTT details. Additionally, all pivotal actions are meticulously logged in "mic_sensor.log", ensuring users have a transparent view of the script's operations.

### [Python Log Crawler](https://github.com/Narqulie/log_crawler)
![Python_log_crawler](/images/log_crawler.png)

This tool simplifies the task of searching specific terms within files, making data retrieval a 
breeze. Useful for finding specific errors or events in log files, or for searching for specific
data in large files. The script is designed to be easy to use, and it's built to handle unexpected
file issues. It's a great tool for searching through log files, or any other files for that matter.

* Command-Line Interface: Input the term, file extension, and directory. Opt for case-sensitive or insensitive searches based on your need.
* Logging: Key actions and issues are logged for transparency and debugging.
* Deep Search: The script efficiently searches throughout the chosen directory.
* Case Sensitivity Choice: Allows for precise or general searches.
* Error Handling: Built to handle unexpected file issues.


## Electronics Projects:

### [ESP-Home presence detection](https://github.com/Narqulie/LD2410_ESP8266_radar)
##### Presence detection using ESP8266 and ESP-Home
![ESP-Home presence detection](/images/esp_home_ld2410.jpeg)

Venture into the realm of smart home integrations with this unique project that combines the precision of the LD2410 motion sensor with the versatility of the NodeMCU platform. The result is a powerful presence detection system that can be integrated into Home Assistant. This project is a great way to get started with ESPHome and ESP8266.

* Sophisticated Motion Detection: Unlike traditional motion sensors, the LD2410 can differentiate between moving and stationary targets, offering a detailed perspective on activities in any space, very suitable for say, the dunny.
* NodeMCU Integration: Using the open-source NodeMCU platform, this project streams real-time motion data, adaptable for alerts, device activations, or logging.
* Native Home Assistant Support: Elevate your home automation experience with seamless integration into Home Assistant. This enables automatic task scheduling, alerts, or space monitoring based on the refined motion data.
* Diverse Use-Cases: Envision enhanced security with motion-triggered alerts, energy conservation by regulating utilities based on room occupancy, or delve into data logging to discern activity patterns.
* 3D Printed Enclosure: Accommodate the ESP8266 and LD2410 in a tailor-made 3D printed enclosure. Designed for optimal mounting and adaptability, the enclosure has options for supplementary sensors.

---
