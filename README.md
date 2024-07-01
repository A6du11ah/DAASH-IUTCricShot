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
  
![detection1](https://github.com/A6du11ah/DAASH-IUTCricShot/assets/107485472/2e51a43b-935b-42df-a78f-8c202cc377e2)
![detection2](https://github.com/A6du11ah/DAASH-IUTCricShot/assets/107485472/9fff42d6-d105-4468-8b76-153048fb28e8)

  
* **LRCN for Shot Type Classification:** Employs a Long-term Recurrent Convolutional Network (LRCN) to analyze the cropped video sequence and classify the shot type. Initially, we are detecting 4 types of shots.
    * **PULL**
      
      ![pull](https://github.com/A6du11ah/DAASH-IUTCricShot/assets/107485472/a9494ebb-57a5-4b8e-be7c-22c3fc2e515c)

    * **DEFENSE**
      
      ![defense](https://github.com/A6du11ah/DAASH-IUTCricShot/assets/107485472/df82d055-3599-4bdf-a8f2-b71bc448f80d)

    * **DRIVE**
      
      ![drive](https://github.com/A6du11ah/DAASH-IUTCricShot/assets/107485472/812605e3-07bd-49f0-bd2d-aa98b6289400)

    * **FLICK**
      
      ![flick](https://github.com/A6du11ah/DAASH-IUTCricShot/assets/107485472/b27c0f0c-5b3a-4b15-96f4-a97ac2f86861)



### Methodology

* **Object Detection:**
    * YOLO v9 is used to detect the batsman in each frame.
    * The detected region around the batsman is cropped for further analysis.
* **Shot Classification:**
    * The cropped video sequence is processed by an LRCN model.
    * The LRCN model classifies the type of cricket shot based on the batsman’s movements.
      
<!-- GETTING STARTED -->
## Getting Started

Here are the instructions on how to run this project on Google Collab.

### Prerequisites

* Google Collab Account
* Basic understanding of Python and machine learning
* Video footage of cricket matches for testing

### Accessing the Project

For the dataset used in this project, please email us at 
* abdullah20@iut-dhaka.edu

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.







