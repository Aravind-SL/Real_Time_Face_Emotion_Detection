# Real-Time Webcam Face Emotion Detection with Streamlit

## Overview

This project leverages Streamlit to create a user-friendly interface for real-time webcam-based face emotion detection. The application utilizes the Haar Cascade classifier for face detection and a transfer-learned ImageNet model trained on the FER 2013 dataset for facial emotion classification.

## Features

- **Streamlit Web Interface**: The application provides a seamless and interactive user experience through the Streamlit framework.

- **Face Detection**: Haar Cascade classifier is employed to detect faces in real-time from the webcam feed.

- **Emotion Classification**: A transfer-learned ImageNet model, trained on the FER 2013 dataset, is used for accurate emotion classification.

- **Real-Time Updates**: Emotion predictions are dynamically updated and displayed on the Streamlit app, providing instant feedback on detected facial expressions.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Aravind-SL/Real_Time_Face_Emotion_Detection.git
   cd Real_Time_Face_Emotion_Detection```

2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Streamlit app:**

    ```bash
    streamlit run app.py
    ```
## Usage

1. **Open the Streamlit app in your web browser:**
   Navigate to the provided URL after running the `streamlit run app.py` command.

2. **Webcam Feed:**
   The webcam feed will be displayed on the Streamlit app, with faces highlighted by the Haar Cascade classifier.

3. **Real-Time Emotion Predictions:**
   Emotion predictions will be overlaid on detected faces in real-time.

4. **Experiment:**
   Try different facial expressions to observe the real-time emotion classification.

## Contributing
  Contributions are encouraged! Feel free to open an issue or submit a pull request for any improvements or additional features.
### Drawbacks and Future Improvements

While the current model for real-time webcam face emotion detection has proven effective for Happy, Sad, Surprised, Angry and Neutral, it does have some limitations that should be acknowledged. Notably, the model struggles to accurately predict fear and disgust emotions.

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/license/mit/) file for details.

## Acknowledgments

The emotion detection model is based on a transfer-learned ImageNet architecture trained on the FER 2013 dataset.

