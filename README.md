🎤 Speech-Based Gender Detection Using Pitch Analysis

This project is a simple MATLAB implementation of speech-based gender detection. It records audio input from a microphone, extracts the fundamental frequency (pitch), and classifies the speaker as male or female based on typical pitch ranges.

📌 Features
Real-time voice recording using MATLAB
Pitch extraction from speech signal
Gender classification based on frequency threshold
Simple and lightweight implementation
Beginner-friendly DSP project
⚙️ How It Works
The program records a short audio sample from the user.
The recorded signal is processed to estimate the fundamental frequency (pitch).
The pitch value is compared with a predefined threshold:
Lower pitch → Male
Higher pitch → Female
The result is displayed in the MATLAB command window.
📊 Methodology
Audio captured using MATLAB’s built-in recording functions
Pitch estimated using autocorrelation / built-in pitch detection functions (depending on implementation)
Decision boundary based on average human pitch range:
Male: ~85 Hz – 180 Hz
Female: ~165 Hz – 255 Hz
🧠 Technologies Used
MATLAB
Digital Signal Processing (DSP)
Audio Signal Analysis
▶️ How to Run
Open MATLAB

Run the script:

main.m
Speak into the microphone when prompted
View the predicted gender output
📁 Project Structure
Speech-Gender-Detection/
│
├── main.m
├── record_audio.m
├── pitch_extraction.m
├── classify_gender.m
└── README.md
📈 Future Improvements
Use machine learning (SVM / Neural Networks)
Train on larger datasets
Add noise filtering for real-world accuracy
Support multi-language speech inputs
GUI interface using MATLAB App Designer
⚠️ Limitations
Accuracy depends on microphone quality
Overlap in pitch ranges can cause misclassification
Works best in quiet environments
