# Face Detection System for Digital Camera

## Project Overview

This project is part of the Master ProfessionAI in Data Science and is aimed at developing a face detection system for a new compact digital camera designed by ProCam S.p.A. The camera is intended for young aspiring photographers, and the face detection feature will be used to optimize camera settings, particularly for selfies with one or more people.

### Problem Description

The task involves building a computer vision system, specifically a face detection model, using the `scikit-learn` library. The model should be capable of receiving an input image and returning a list of bounding box coordinates where faces are detected. If no faces are present in the image, the list should be empty.

### Constraints

1. **No Pre-trained Models:** Pre-trained models are not allowed. The model must be trained from scratch using `scikit-learn`.
2. **Computational Limitations:** The system has limited computational capacity, so the model must be lightweight and require minimal computational resources.
3. **Dataset:** No predefined dataset is provided. You must search for or construct a dataset independently, disregarding commercial licensing issues as this is an educational project.
4. **Documentation:** The notebook must be thoroughly documented, explaining the solutions adopted and the rationale behind them. All external resources used (research papers, blog posts, GitHub repositories) must be cited and documented.

### Model Development

The face detection model was developed based on extensive bibliographic research and analysis of existing face detection techniques. Given the need to build the model from scratch and keep it lightweight, specific decisions were made regarding feature selection, model architecture, and training strategies.

#### Research and Technical Choices

Several techniques and algorithms for face detection were explored in the development of the system, including:

- **Haar Cascades:** A traditional face detection technique that uses a cascade of Haar features to identify face regions in an image.
- **Support Vector Machines (SVM):** Used for classifying segmented image regions to distinguish between those containing faces and those without.
- **Pyramid Scaling and Sliding Windows:** Ensures the detection of faces of different sizes and positions within an image.

These choices were made with an emphasis on balancing accuracy with computational efficiency, given the limited resources available.


### Resources and References

Various resources were utilized during the development of this project to inform the technical and methodological choices. These include:

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [OpenCV Tutorials](https://docs.opencv.org/master/d6/d00/tutorial_py_root.html)

### Acknowledgments

I would like to thank the instructors and peers from the Master ProfessionAI in Data Science for their support and guidance throughout this project.

### License

This project is developed for educational purposes as part of the Master ProfessionAI and is not intended for commercial use.
