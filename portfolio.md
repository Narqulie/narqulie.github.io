---
layout: page
title: Portfolio
---

## Python Projects:

I have been learning Python for a while now, and I have been using it for various projects. My interests are in data analysis and management, web scraping and automation. I've used Python professionally for automation and REST API integrations.
I have an interest in making my code readable and clean. I also like logging and documenting my work to make it easier to understand and maintain.

### [Python_eye](https://github.com/Narqulie/Python_eye)
##### Computer vision exercises using OpenCV and Python

This is a test-case project for python and computer vision, using CV2. The program uses a simple Command Line Interface (CLI) for user interactions. It has multiple different functions:
* Training a face recognition model with reference pictures
* Analysing a live webcam feed and labelling recognized people
* Eye tracking
It's a living work in progress where I try out different computer vision related ideas and functionalities.

### [Tuner](https://github.com/Narqulie/Tuner)
##### Audio processing exercises using Python

Have YOU ever wanted a bad tuner for any instrument? 
This is a simple tuner program that uses the microphone to listen to the instrument and displays the frequency of the sound. It can be used for the tuning of any instrument, but it's not very good at it. It's a fun little project that I made to learn about audio processing and FFT.
* Using FFT (Fast Fourier Transform) to detect the peak frequency of an audio signal in real-time.
* Displaying a tuning bar, with red indicating lower frequencies and green for higher frequencies.
* Continuously averaging detected frequencies for smoother and more stable readings.
* Matching the detected frequency with the nearest musical note based on Western traditional tuning.

### [Microphone_sensor_HA](https://github.com/Narqulie/Microphone_sensor_HA)
##### Audio processing and MQTT integration using Python

This Python script uses a microphone to detect noise levels and sends the status to an MQTT broker. The noise level status can then be used by Home Assistant or any other platform that can subscribe to the MQTT topic.
* Real-time Noise Monitoring: The script harnesses the power of a microphone to continuously monitor and evaluate ambient noise levels.
* Integration with MQTT: Once the noise status is determined, it is promptly relayed to an MQTT broker. This seamless integration ensures the script's compatibility with platforms like Home Assistant, allowing users to tap into the noise data conveniently.
* Adaptive Noise Detection: Instead of relying on a static threshold, the script uses a dynamic thresholding mechanism. It recalculates the noise threshold every 5 seconds. This ensures the system remains responsive to sudden changes in noise levels.
* User-friendly Configuration and Logging: To enhance user experience, the script offers an easily editable configuration file for MQTT details. Additionally, all pivotal actions are meticulously logged in "mic_sensor.log", ensuring users have a transparent view of the script's operations.

