# Hand Sign Digit Recognizer

## Overview

The Hand Sign Digit Recognizer is a project that uses deep learning techniques to recognize hand gestures and predict the corresponding digit. This repository contains code that employs transfer learning with a pre-trained ResNet-50 model. The model's output layer was fine-tuned using a hand sign digit images dataset. The project aims to provide an accurate and efficient solution for recognizing hand-drawn digits using computer vision.

## Features

- Utilizes transfer learning with ResNet-50 for digit recognition.
- Trained on a hand sign digit images dataset.
- Implemented using Python and deep learning libraries.
- Provides a user-friendly interface to upload and predict digit gestures.

## Contributors

- Username: [@karansoni07](https://github.com/karansoni07)
- Contact: [karansoni988711@gmail.com](mailto:karansoni988711@gmail.com)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/karansoni07/sign-detector.git
   cd sign-detector
   ```

2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Run the main application:
   ```sh
   python app.py
   ```

2. Access the application in your web browser at `http://localhost:5000`.

3. Upload a hand gesture image to the application and receive the predicted digit.

## Model Training and Visualization

1. The model uses transfer learning with a pre-trained ResNet-50 architecture.

2. The output layer was fine-tuned using the hand sign digit images dataset.

3. The training script can be found in the `train.py` file.

4. To generate the Epochs vs Accuracy graph, run:
   ```sh
   python visualize.py
   ```

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to contribute, open issues, or provide suggestions to improve this project. Your feedback is valuable!
```