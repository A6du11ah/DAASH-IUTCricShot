# DAASH-IUTCricShot
This repository contains the code and resources for a Machine Learning model designed to automatically detect cricket shot types from video footage.


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#key-features">Key Features</a></li>
      </ul>
      <ul>
        <li><a href="#methodology">Methodology</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#accessing-the-project">Accessing The Project</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project



Welcome to our project for detecting cricket shot types from video footage using machine learning! This project aims to classify cricket shots in real-time, leveraging advanced computer vision and deep learning techniques.



### Key Features

* **Advanced Object Detection with YOLO v9:** Utilizes a custom-trained YOLO v9 model to locate and crop the batsman from the video frames.
* **LRCN for Shot Type Classification:** Employs a Long-term Recurrent Convolutional Network (LRCN) to analyze the cropped video sequence and classify the shot type.
![main](https://github.com/A6du11ah/DAASH-IUTCricShot/assets/107485472/2a4d8bd1-9eb6-43ba-a3af-912b3a4e54e5)


### Methodology

* **Object Detection:**
    * YOLO v9 is used to detect the batsman in each frame.
    * The detected region around the batsman is cropped for further analysis.
* **Shot Classification:**
    * The cropped video sequence is processed by an LRCN model.
    * The LRCN model classifies the type of cricket shot based on the batsman’s movements.

![main](https://github.com/A6du11ah/DAASH-IUTCricShot/assets/107485472/dca1cf04-7be0-42de-b9c0-709f64d2cbf2)


<!-- GETTING STARTED -->
## Getting Started

Here are the instructions on how to run this project on Google Collab.

### Prerequisites

* Google Collab Account
* Basic understanding of Python and machine learning
* Video footage of cricket matches for testing

### Accessing the Project



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.







