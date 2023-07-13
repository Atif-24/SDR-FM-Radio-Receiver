# FM Radio Receiver

This project serves as my first foray into the world of software-defined radio (SDR), specifically utilizing RTL-SDR and GNU Radio. Considered to be the "hello world" of SDR, it has provided me with an opportunity to learn the fundamentals of SDR and create a useful FM radio receiver. Throughout the development process, I enjoyed working with RTL-SDR and discovered that GNU Radio shares similarities with Simulink, making it an intuitive platform to work with.

## Overview

The FM Radio Receiver is designed to receive FM radio signals across a wide frequency range of 88 to 107 MHz. By leveraging RTL-SDR and GNU Radio, this project enables users to tune in to their favorite radio stations with ease. Additionally, it includes features such as user-friendly station switching and frequency monitoring with a visual waterfall spectrogram, all aimed at enhancing convenience, usability, and reception quality for listeners.

## Features

- Wide Frequency Range: Covering frequencies from 88 to 107 MHz, the FM Radio Receiver allows users to explore a diverse range of FM radio stations.

- User-Friendly Station Switching: Seamlessly switch between four local radio stations using an intuitive and user-friendly interface, improving convenience and usability.

- Frequency Monitoring and Visualization: The integration of a frequency monitoring capability provides users with real-time feedback on reception quality. The visual waterfall spectrogram offers a comprehensive and visual representation of the received frequencies, aiding in optimal reception and quality assessment.

## RTL-SDR Device and Antenna

For this project, I used the NooElec NESDR Mini 2+ as my RTL-SDR device along with the antenna that came with it. The NooElec NESDR Mini 2+ is a popular and reliable RTL-SDR device that offers excellent performance for a wide range of applications.

If you are interested in using the same RTL-SDR device, you can find it on Amazon: [NooElec NESDR Mini 2+](https://www.amazon.ca/NooElec-NESDR-Mini-Compatible-Packages/dp/B00VZ1AWQA/ref=sr_1_3?keywords=nooelec+mini+2%2B&s=electronics&sr=1-3). It comes bundled with the necessary accessories, including the antenna, making it a convenient choice for getting started with RTL-SDR.

## GNU Radio Flowchart

![GNU Radio Flowchart](https://github.com/Atif-24/SDR-FM-Radio-Receiver/blob/39935e1925c4b8bd6a7335f6cc482b3169c6f8f5/GNU%20FM%20Radio%20Receiver/Flowchart.png)

To create the flowchart for the FM Radio Receiver, I followed the instructions and guidance provided in the [RTL-SDR FM Radio Receiver with GNU Radio Companion](https://www.instructables.com/RTL-SDR-FM-radio-receiver-with-GNU-Radio-Companion/) instructable tutorial. This tutorial served as a valuable resource in understanding the required signal processing blocks and their connections to receive and demodulate FM radio signals.

## GUI (Graphical User Interface)

![FM Radio Receiver GUI](https://github.com/Atif-24/SDR-FM-Radio-Receiver/blob/39935e1925c4b8bd6a7335f6cc482b3169c6f8f5/GNU%20FM%20Radio%20Receiver/GUI.png)

The graphical user interface (GUI) for the FM Radio Receiver was developed through my own experimentation and exploration with the available GNU Radio blocks. By playing around with the blocks and their settings, I was able to create a GUI that provides an intuitive and user-friendly interface for controlling various functions of the receiver. This customization allowed me to tailor the GUI to suit the specific needs and preferences of the FM Radio Receiver project.

