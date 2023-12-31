<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![LinkedIn][linkedin-shield]][linkedin-url]
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/20945843.jpg" alt="Logo" width="400" height="300">
  </a>

  <h3 align="center">Facial Detection Camera</h3>
</div>





<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
This project was adapted from a class project. 
The project intends to be an exploration and deconstruction of how commercial "doorbell" cameras work.

The basic functionalities include being able to :
* Detect if a person enters the camera frame using facial detection
* Distinguish between static frames and dynamic motion
* Take a picture of the person/thing that enters the frame
* Sends the user a live email notification when motion is detected with the picture the camera takes

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* OpenCV
* numpy
* smtplib
* OpenCV Deep Learning Facial Detector
The OpenCV Facial Detector uses a deep neural network with caffe models provided in the dnn module of openCV written by https://github.com/arrybn


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites
As this project contains an IoT element, the project requires an active gmail address and an app password. Instructions on how to set up an app password can be found in the first few minutes of this 
<a href="https://www.linkedin.com/in/abramhuang" target="_blank">Video</a>
For facial detection, it is necessary to install the files "deploy.prototxt.txt" and "res10_300x300_ssd_iter_140000.caffemodel". They are provided in this repo.



### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Set up a new gmail account or use an account that you don't mind having potential spam sent to.
2. Clone the repo
   ```sh
   git clone https://github.com/ActuallyAbram/Facial_Detection_Cam.git
   ```
3. Install packages
   ```sh
   pip install opencv-python numpy 
   
   ```
4. Create a  `config.py` file and fill in the user key and pass key
   ```py
   smtpUserKey = "Email Here"
   smtpPassKey = "App Password Here"
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage


[![Img alt text](https://img.youtube.com/vi/3NMMvri0Eu0/0.jpg)](https://www.youtube.com/watch?v=3NMMvri0Eu0)
<p align="right">(<a href="#readme-top">back to top</a>)</p>
A video demo is provided above.





<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - Abram Huang


<a href="https://www.linkedin.com/in/abramhuang" target="_blank">LinkedIn</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
Image by vectorjuice on Freepik
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
