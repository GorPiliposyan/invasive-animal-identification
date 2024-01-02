# Invasive Terrapin Identification project

![Project Banner](https://github.com/GorPiliposyan/invasive-animals/blob/main/banner_img.png)

This project aims to determine whether an animal captured in an image is classified as an invasive non-native (alien) species within specific regions of the United Kingdom. The full information from the UK government is provided [here](https://www.gov.uk/guidance/invasive-non-native-alien-animal-species-rules-in-england-and-wales). The current model specializes in distinguishing between invasive (non-native) terrapins and turtles compared to native species. Utilizing YOLOv5, our computer vision model accurately identifies 17 distinct species through object detection with bounding boxes.

## Table of Contents

- [Introduction](#introduction)
- [Tech Stack](#Tech-Stack)
- [Features](#features)
- [Recognised species](#Recognised-species)
- [Usage](#usage)
- [License](#license)
<!-- - [Installation](#installation)-->
<!-- - [Contributing](#contributing)-->

## Introduction

The objective of the Invasive Animal Identification Project is to create a computer vision solution that identifies terrapin and turtle species, thus differentiating invasive ones from native ones. Utilizing a YOLOv5-based model capable of detecting 17 distinct species through object detection and recognition techniques with bounding boxes, the project aids individuals in determining whether their pet or wild-caught turtle is native before releasing it into the wild. This proactive approach safeguards native wildlife and the broader ecosystem. The project invites contributions and aims to raise awareness about invasive species management, specifically focusing on England and Wales.

---

## Tech Stack

<img align="left" alt="Java" width="30px" style="padding-right:20px;" src="https://github.com/GorPiliposyan/invasive-animal-identification/blob/main/Images/Python-logo-notext.svg"/>
<img align="left" alt="Java" width="30px" style="padding-right:20px;" src="https://github.com/GorPiliposyan/invasive-animal-identification/blob/main/Images/PyTorch_logo_icon.svg"/>
<img align="left" alt="Java" width="100px" style="padding-right:20px;" src="https://github.com/GorPiliposyan/invasive-animal-identification/blob/main/Images/UltralyticsYOLO_full_blue.svg"/>
<img align="left" alt="Java" width="30px" style="padding-right:20px;" src="https://github.com/GorPiliposyan/invasive-animal-identification/blob/main/Images/OpenCV_Logo.svg"/>
<br />

#

- **Python**
- **PyTorch**
- **Ultralytics YOLOv5**
- **OpenCV**

#

## Features

- **Species Identification**: Detects and identifies 17 terrapin and turtle species.
- **Object Detection**: Utilizes bounding boxes for accurate identification within images.

## Recognised species

The model is currently trained to identify ***17 species of terrapins and turtles***, some of which are considered native and others invasive. The full list of invasive species in Engand and Wales can be found [here](https://www.gov.uk/guidance/invasive-non-native-alien-animal-species-rules-in-england-and-wales). The full list of the 17 species addressed in this project is available in the drop-down menu below.

<details>
  <summary>List of Turtle and Terrapin Species</summary>
  
  - Alligator snapping turtle
  - Common musk turtle
  - Cumberland slider terrapin
  - European pond turtle
  - False map turtle
  - Florida red-bellied cooter
  - Map turtle
  - Mississippi map turtle
  - Mud turtle
  - Peninsula cooter
  - Razorback musk turtle
  - Red-eared slider terrapin
  - River cooter
  - Snake necked turtle
  - Softshell turtle
  - Spotted turtle
  - Yellow-bellied slider terrapin
  
</details>



## Usage

The project utilizes Streamlit to create a [web application](https://terrapin-species-classifier.streamlit.app/) that serves as a user-friendly interface accessible to the public. To utilize the website, users simply upload an image and activate the 'Make Prediction' button. The model undertakes the detection process and subsequently presents a comprehensive list of identified animals within the image. Additionally, users have the option to export the results in a CSV file format for further analysis or record-keeping purposes.

## License

This model is made available solely for educational purposes and is not intended for commercial use. Users are kindly requested to acknowledge and cite this repository if the model is employed in external projects. Additionally, your support by starring this repository is greatly appreciated.

<!--
## Installation

Provide instructions here on how to install and set up the project for use.
-->

<!--
## Contributing

Welcome contributions! Guidelines for reporting bugs, suggesting enhancements, or submitting pull requests can be found [here](link_to_contributing_guidelines).
-->



