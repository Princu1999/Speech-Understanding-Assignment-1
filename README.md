# Speech Understanding Programming Assignment - 1

## Project Overview
This repository contains the code and analysis for the Speech Understanding Programming Assignment, focusing on spectrogram analysis and windowing techniques using the UrbanSound8k dataset. The project explores various aspects of speech processing, including:

- Implementation of windowing techniques (Hann, Hamming, and Rectangular)
- Generation of spectrograms using Short-Time Fourier Transform (STFT)
- Classification of urban sounds using features extracted from spectrograms
- Comparative analysis of spectrograms from different music genres

## Key Features
- **Windowing Techniques Implementation**: Hann, Hamming, and Rectangular window functions
- **Spectrogram Generation**: Short-Time Fourier Transform (STFT)-based spectrogram analysis
- **Urban Sound Classification**: Machine learning classifiers (Convolutional Neural Network) for urban sound classification
- **Spectrogram Analysis**: Comparative study of spectrograms across different music genres

## Dataset
The project utilizes the **UrbanSound8K** dataset, which consists of 8732 labeled sound excerpts categorized into 10 different urban sound classes. These classes include:
- Dog Bark
- Children Playing
- Car Horn
- Air Conditioner
- Street Music
- Engine Idling
- Drilling
- Jackhammer
- Siren
- Gun Shot

## Installation & Usage
### Prerequisites
- Python 3.x
- NumPy
- Librosa
- Matplotlib
- Scikit-learn
- TensorFlow/PyTorch (for Neural Network classifier)

### Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/yourusername/speech-understanding.git
cd speech-understanding
pip install -r requirements.txt
```

### Running the Project
To generate spectrograms and train classifiers, run:
```bash
python SA_ASSIGNMENT1_QUES2_TASKA.py
python Q2_TASK_B.py
```

## Results & Analysis
- Spectrograms generated using different windowing techniques
- Performance of Convolutional Neural Network classifier
- Insights into the impact of windowing on spectrogram quality and classification accuracy

## Contributing
Feel free to submit pull requests or raise issues for improvements.
