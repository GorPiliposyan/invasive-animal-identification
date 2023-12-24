# Invasive Terrapins Identification Project

![Project Banner](https://github.com/GorPiliposyan/invasive-animals/blob/main/banner_img.png)

This project aims to determine whether an animal captured in an image is classified as an invasive non-native (alien) species within specific regions of the United Kingdom. The full information from the UK government is provided [here](https://www.gov.uk/guidance/invasive-non-native-alien-animal-species-rules-in-england-and-wales). The current model specializes in distinguishing between invasive (non-native) terrapins and turtles compared to native species. Utilizing YOLOv5, our computer vision model accurately identifies 17 distinct species through object detection with bounding boxes.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Recognised species](#Recognised-species)
- [Usage](#usage)
- [License](#license)
<!-- - [Installation](#installation)-->
<!-- - [Contributing](#contributing)-->

## Introduction

The objective of this project is to create a computer vision solution for identifying invasive terrapin and turtle species. The YOLOv5-based model encompasses 17 species, leveraging object detection techniques with bounding boxes.

## Features

- **Species Identification**: Detects and identifies 17 invasive terrapin and turtle species.
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

The project offers a [web application](https://terrapin-species-classifier.streamlit.app/) that serves as a user-friendly interface for public use. Provide guidance here on how users can access and utilize the application for species identification.

## License

This model is available for educational purposes. Users are encouraged to cite this repository if the model is utilized elsewhere.

<!--
## Installation

Provide instructions here on how to install and set up the project for use.
-->

<!--
## Contributing

Welcome contributions! Guidelines for reporting bugs, suggesting enhancements, or submitting pull requests can be found [here](link_to_contributing_guidelines).
-->



