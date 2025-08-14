# Next Word Predictor

A simple **LSTM-based** next word prediction project built with Python and TensorFlow/Keras.  
The model predicts the next word in a sequence based on the training text (*Hamlet* by William Shakespeare).

---

## 📂 Project Structure

next-word-predictor/
├── app.py # Script to run predictions using the trained model
├── experiemnts.ipynb # Jupyter Notebook for training and experimenting
├── hamlet.txt # Training dataset
├── next_word_lstm.h5 # Saved LSTM model
├── tokenizer.pickle # Saved tokenizer for text preprocessing
├── requirements.txt # Python dependencies
└── .gitignore


---

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Palak2811/next-word-predictor.git
   cd next-word-predictor


Create and activate a virtual environment

python3 -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate


Install dependencies

pip install -r requirements.txt

🛠 Usage
1. Run the prediction script
python app.py


The script will prompt you to enter a sequence of words.

The model will predict and display the next word.

Example:

Enter your text: To be or not to
Predicted next word: be

📓 Training the Model

Open the Jupyter Notebook:

jupyter notebook experiemnts.ipynb


The notebook contains:

Data loading (hamlet.txt)

Tokenization and preprocessing

LSTM model creation

Training and saving the model + tokenizer

📦 Requirements

Main libraries:

tensorflow

numpy

pickle

jupyter

Install everything from:

pip install -r requirements.txt

📊 Dataset

Source: Hamlet by William Shakespeare (public domain)

The dataset is small and mainly for demonstration purposes.
For better results, train on a larger text corpus.

