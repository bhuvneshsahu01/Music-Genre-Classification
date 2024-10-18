# Music Genre Classification 🎵

This project explores the use of deep learning models to classify music genres from audio data. By leveraging **Convolutional Neural Networks (CNNs)** and **Recurrent Neural Networks (RNNs)**, the system analyzes the audio signals and identifies their corresponding genres. 

## Project Overview  
With the growing size of digital music libraries, automated genre classification improves music discovery and organization. This project aims to classify audio tracks into ten genres using visual and temporal features from audio signals.

### **Genres Covered**  
- Blues  
- Classical  
- Country  
- Disco  
- Hip-Hop  
- Jazz  
- Metal  
- Pop  
- Reggae  
- Rock  

---

## Dataset  
The **GTZAN dataset** (from Kaggle) is used, consisting of 1,000 audio clips (100 per genre), each 30 seconds long in WAV format. It offers a diverse set of tracks, providing a reliable foundation for training the models.

### Libraries Used  
- **Librosa**: For audio feature extraction  
- **Pydub**: Handles file format inconsistencies during loading  
- **TensorFlow/Keras**: Builds and trains the machine learning models  

---

## Model Architecture  

1. **Convolutional Neural Networks (CNNs):**  
   - Extract visual patterns from spectrograms and tempograms  
   - Components: Convolution, ReLU activation, Dropout, and Pooling layers  

2. **Recurrent Neural Networks (RNNs):**  
   - Capture temporal dependencies and musical dynamics over time  
   - Useful for analyzing rhythmic patterns and long-term dependencies  

---

## Performance  
- **Training Accuracy:** 77.80%  
- **Validation Accuracy:** 61.81%  
- **Testing Accuracy:** 79.60%  

---

## Usage  

### 1. Installation  
Clone the repository and install the necessary dependencies:
```bash
git clone https://github.com/hannahbenjamin/music-genre-classification.git
cd music-genre-classification
pip install -r requirements.txt
