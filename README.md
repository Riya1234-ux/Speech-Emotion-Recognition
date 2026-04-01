🎙️ Speech Emotion Recognition using LSTM

📌 Overview

This project focuses on detecting human emotions from speech signals using Machine Learning and Deep Learning techniques.
We extract audio features (MFCCs) and train an LSTM-based neural network to classify emotions.

---

📊 Dataset

- Dataset used: Toronto Emotional Speech Set (TESS)
- Contains audio recordings of different emotions like:
  - Happy 
  - Sad 
  - Angry 
  - Fear 
  - Disgust 
  - Surprise 
  - Neutral 

---

⚙️ Tech Stack

- Python 🐍
- NumPy & Pandas
- Librosa (for audio feature extraction)
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

---

🔍 Feature Extraction

- Extracted MFCC (Mel Frequency Cepstral Coefficients) from audio signals
- Each sample converted into a fixed-length feature vector

---

🧠 Model Architecture

- LSTM Layer (113 units)
- Dense Layers (64 → 32)
- Dropout (0.2)
- Output Layer (Softmax - 7 classes)

---

📈 Training Details

- Loss Function: Categorical Crossentropy
- Optimizer: Adam
- Epochs: 100
- Batch Size: 32
- Validation Split: 20%

---

📊 Results

- Achieved decent classification accuracy on validation data
- Model successfully distinguishes between multiple emotions

(You can add your exact accuracy here after checking results)

---

📉 Visualization

- Training vs Validation Accuracy plotted using Matplotlib
- Helps in analyzing overfitting and model performance

---

🚀 How to Run

1. Clone the repository:

git clone https://github.com/your-username/your-repo.git
cd your-repo

2. Install dependencies:

pip install -r requirements.txt

3. Run the notebook:

jupyter notebook

---

📁 Project Structure

├── notebook.ipynb
├── README.md
├── requirements.txt
└── dataset/

---

💡 Future Improvements

- Use CNN + LSTM hybrid model 🔥
- Data augmentation (noise, pitch shift)
- Hyperparameter tuning
- Real-time emotion detection

---

🤝 Acknowledgements

- Dataset providers
- Open-source libraries

---

⭐ If you like this project

Give it a star ⭐ on GitHub!
