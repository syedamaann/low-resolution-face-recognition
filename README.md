# Single Image Low Resolution Face Recognition

## Overview

This project focuses on enhancing the resolution of low-quality face images and performing face recognition using deep learning and image processing techniques. The primary workflow involves using Super-Resolution Generative Adversarial Networks (SRGANs) for image enhancement, followed by face detection using Multi-task Cascaded Convolutional Networks (MTCNN). Additionally, a Siamese Model is employed for face detection, demonstrating its effectiveness over traditional methods.

## Features

- **Super-Resolution with SRGANs:** The project utilizes SRGANs to enhance the resolution of low-quality face images. This deep learning approach helps in producing high-resolution images from their low-resolution counterparts.

- **Face Detection with MTCNN:** Multi-task Cascaded Convolutional Networks (MTCNN) are employed for accurate and efficient face detection in the enhanced images. MTCNN is known for its ability to detect faces at different scales, making it suitable for diverse image resolutions.

- **Siamese Model for Face Detection:** In addition to MTCNN, the project explores the use of a Siamese Model for face detection. This model proves to be more useful in certain scenarios, offering an alternative approach to traditional face detection methods.

## How to Use

1. **Install Dependencies:**
   - Ensure that the required dependencies, including deep learning libraries such as TensorFlow or PyTorch, are installed. Refer to the `requirements.txt` file for a detailed list.

2. **Model Training (Optional):**
   - If needed, the SRGAN and Siamese Model can be retrained using the provided training scripts. Training data should include pairs of low-resolution and high-resolution face images.

3. **Image Enhancement:**
   - Apply the SRGAN model to enhance the resolution of low-quality face images. Use the provided script for easy integration into your workflow.

4. **Face Detection:**
   - Choose between MTCNN and the Siamese Model for face detection. The project provides separate scripts for each method, allowing users to compare and select the most suitable approach for their use case.

5. **Evaluate Results:**
   - Assess the performance of the face detection process by evaluating the accuracy, precision, and recall. The evaluation script is included in the project for this purpose.

## Contributing

Contributions to this project are welcome. If you have suggestions, bug reports, or would like to add new features, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for your purposes.

## Acknowledgments

- The project makes use of the SRGAN architecture, inspired by the work of Ledig et al. (2017).
- MTCNN is utilized for face detection, following the approach proposed by Zhang et al. (2016).
- The Siamese Model implementation is based on the work of Bromley et al. (1994).
