# Assignment4


---

# Streamlit Image Processing Apps

This repository contains Streamlit applications for image processing, including Image Matching and Image Search by Text. These apps leverage machine learning models and various image processing techniques to provide useful functionalities.

## Table of Contents

- [Introduction](#introduction)
- [Applications](#applications)
- [Requirements](#requirements)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The purpose of this repository is to showcase two Streamlit applications:
- **Image Match**: Utilizes TensorFlow and computer vision techniques to match and compare images based on their visual similarity.
- **Image Search by Text**: Utilizes the CLIP model by OpenAI to perform image searches based on textual input.

These applications are built using Streamlit, a Python library for creating web applications for data science and machine learning projects. Each application has its functionalities and uses various machine learning models to perform image-related tasks.

## Applications

### Image Match

The Image Match app uses TensorFlow, VGG19, and cosine similarity to compare the visual features of images. It processes a directory of images, extracts their visual features, and matches them based on their similarity.

### Image Search by Text

The Image Search by Text app leverages the CLIP (Contrastive Language-Image Pre-training) model by OpenAI. Users can enter text queries, and the app finds the most relevant images based on the textual input.

## Requirements

The applications have dependencies listed in the `requirements.txt` file. Key dependencies include:
- TensorFlow
- OpenCV
- CLIP by OpenAI
- Streamlit

Make sure to install these dependencies before running the applications.

## Usage

To run these applications:
1. Install the required dependencies mentioned in the `requirements.txt` file.
2. Run the Streamlit app file `streamlit.py`.
3. Access the Streamlit app in your browser by following the provided link.

Feel free to explore the functionalities and test the apps with your images or text queries.

## Contributing

Contributions to enhance these applications or add new features are welcome! Feel free to fork this repository, make your changes, and submit a pull request.

If you encounter any issues or have suggestions for improvement, please open an issue in the repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

You can customize this README file further by adding more detailed instructions, examples, or any additional information specific to your project.