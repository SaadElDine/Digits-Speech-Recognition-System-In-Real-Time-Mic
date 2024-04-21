# Digits-Speech-Recongnition-System-In-Real-Time-Mic
This project aims to recognize spoken digits (0-9) from audio recordings using deep learning techniques. The model is trained on a dataset containing audio samples of spoken digits and is then used to predict the digit spoken in a given audio clip. Real-time testing allows the model to predict digits from live microphone input.

## Overview
This project aims to recognize spoken digits (0-9) from audio recordings using deep learning techniques. The model is trained on a dataset containing audio samples of spoken digits and is then used to predict the digit spoken in a given audio clip. Real-time testing allows the model to predict digits from live microphone input.

![sr](https://github.com/SaadElDine/Digits-Speech-Recongnition-System-In-Real-Time-Mic/assets/113860522/be24ae16-c909-48bc-af6c-499fcb81675d)


## Project Components
1. **Data Collection:** Audio samples of spoken digits (0-9) are collected and labeled.
2. **Data Preprocessing:** The audio samples are preprocessed to extract relevant features, such as Mel-frequency cepstral coefficients (MFCCs).
3. **Feature Extraction (MFCCs):** MFCCs are a representation of the short-term power spectrum of a sound, which mimic the human ear's response to sound. They are extracted by dividing the audio signal into short frames, applying the Fourier transform to each frame, and then taking the logarithm of the power spectrum.
4. **Model Training:** A deep learning model, such as a convolutional neural network (CNN) or recurrent neural network (RNN), is trained on the preprocessed audio data to learn to recognize the spoken digits.
5. **Model Evaluation:** The trained model is evaluated on a separate test set to assess its performance.
6. **Real-time Prediction:** The trained model is used to predict digits from real-time audio input, such as microphone recordings. The audio input is preprocessed in real-time to extract MFCCs, which are then fed into the model for prediction.

## Tools and Technologies Used
- Python
- TensorFlow/Keras
- Librosa (for audio processing)
- Google Colab (for training models)
- PyAudio (for real-time audio input)

## Results
The model achieved an accuracy of 90% on the test set, demonstrating its ability to recognize spoken digits from audio recordings. Real-time testing showed that the model can accurately predict digits from live microphone input.

## Future Improvements
- Improve model accuracy by collecting more diverse training data.
- Experiment with different model architectures and hyperparameters to further improve performance.
- Deploy the model as a real-time digit recognition application on a mobile device or web application.

## Conclusion
This project demonstrates the use of deep learning techniques for audio digit recognition, with the potential for further improvement and application in real-world scenarios.
