# CXR17_DenseParallel_ELM

### Built With

* [Tensorflow Lite](https://www.tensorflow.org/lite)
* [Picasso](https://square.github.io/picasso/)
* [Android Image Cropper](https://github.com/ArthurHub/Android-Image-Cropper/)


### Features
- [x] ML-based 17 types of Lung disease Detection



### Installation

1. Clone the repo using the following link in GitHub Desktop
   ```sh
   git clone https://github.com/khalid-syfullah/cxr17_denseparallel_elm.git
   ```
   Or, Download & Extract the .ZIP archive.

2. Download & Install Android Studio Bumblebee (May work with Dolphin also)
3. Download Android SDK 31
4. Open the project from Android Studio. It will download and install Gradle packages in a few minutes.
5. Wait till the Grade packages installation is finished.
6. Check for the following dependencies in app `build.gradle` file (it should be there already) 
   & add the following if not exists
   ```Java
   dependencies {
   
    implementation 'org.tensorflow:tensorflow-lite-support:0.3.0'
    implementation 'org.tensorflow:tensorflow-lite-metadata:0.3.0'
    implementation 'org.tensorflow:tensorflow-lite-gpu:2.3.0'
    implementation 'org.tensorflow:tensorflow-lite-gpu-delegate-plugin:0.3.0'
   
 }

7. Build the project.
8. To run the project on your phone, first turn on USB debugging in your phone from Developer Options (see tutorial)
   and connect the phone via USB. Then, run the project.
9. Alternatively, you can run the project on Emulator (best works with SDK version 31).
   ```



<!-- CONTACT -->
## Contact

Your Name - [@khalid_syfullah](https://twitter.com/khalid_syfullah) - khalidsyfullah@gmail.com

Project Link: [https://github.com/Khalid-Syfullah/CXR17_DenseParallel_ELM](https://github.com/Khalid-Syfullah/CXR17_DenseParallel_ELM)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)

[contributors-shield]: https://img.shields.io/static/v1?label=Contributors&message=2&color=red
[contributors-url]: https://github.com/khalid-syfullah/CXR17_DenseParallel_ELM/graphs/contributors
[forks-shield]: https://img.shields.io/static/v1?label=Forks&message=1&color=green
[forks-url]: https://github.com/khalid-syfullah/CXR17_DenseParallel_ELM/network/members
[stars-shield]: https://img.shields.io/static/v1?label=Stars&message=1&color=blue
[stars-url]: https://github.com/khalid-syfullah/CXR17_DenseParallel_ELM/stargazers
[issues-shield]: https://img.shields.io/static/v1?label=Issues&message=0&color=yellow
[issues-url]: https://github.com/khalid-syfullah/CXR17_DenseParallel_ELM/issues
[license-shield]: https://img.shields.io/static/v1?label=Licenses&message=0&color=purple
[license-url]: https://github.com/khalid-syfullah/CXR17_DenseParallel_ELM/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/static/v1?label=LinkedIn&message=Khalid-Syfullah&logo=linkedin
[linkedin-url]: https://bd.linkedin.com/in/khalid-syfullah
[product-screenshot]: https://github.com/Khalid-Syfullah/CXR17_DenseParallel_ELM/blob/master/app/src/main/res/drawable/splash.png
