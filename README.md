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

![GNU Radio Flowchart](gnu-radio-flowchart.jpg)

To create the flowchart for the FM Radio Receiver, I followed the instructions and guidance provided in the [RTL-SDR FM Radio Receiver with GNU Radio Companion](https://www.instructables.com/RTL-SDR-FM-radio-receiver-with-GNU-Radio-Companion/) instructable tutorial. This tutorial served as a valuable resource in understanding the required signal processing blocks and their connections to receive and demodulate FM radio signals.

## GUI (Graphical User Interface)

![FM Radio Receiver GUI](gui-screenshot.jpg)

The graphical user interface (GUI) for the FM Radio Receiver was developed through my own experimentation and exploration with the available GNU Radio blocks. By playing around with the blocks and their settings, I was able to create a GUI that provides an intuitive and user-friendly interface for controlling various functions of the receiver. This customization allowed me to tailor the GUI to suit the specific needs and preferences of the FM Radio Receiver project.

## Contributing

Contributions to the FM Radio Receiver project are welcome! If you would like to contribute, please follow these steps:

1. Fork the repository and create a new branch.
2. Make your changes and commit them.
3. Push your changes to your forked repository.
4. Submit a pull request describing your contributions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

For any questions or inquiries about the FM Radio Receiver project, please contact me at fmradio@project.com. I would be delighted to hear your feedback and suggestions.
