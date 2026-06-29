✍️ Handwritten Text Generation using Character-Level RNN
📌 Overview

This project implements a Character-Level Recurrent Neural Network (RNN) using TensorFlow/Keras to generate handwritten-style text. The model is trained on a collection of handwritten notes converted into plain text and learns character-by-character patterns to generate realistic-looking text.

This project demonstrates how deep learning can be used for sequence modeling and text generation.

🚀 Features
Character-Level Text Generation
GRU-based Recurrent Neural Network
Character Encoding & Decoding
Automatic Text Generation
Model Saving & Loading
Performance Visualization
Beginner-Friendly Implementation
🛠️ Technologies Used
Python
TensorFlow
Keras
NumPy
Matplotlib
📂 Dataset

The dataset consists of handwritten-style text converted into plain text format (handwritten_notes.txt).

The model learns:

Character sequences
Word patterns
Sentence structures
Writing style

⚙️ Model Architecture
Input Characters
        │
        ▼
Character Encoding
        │
        ▼
Embedding Layer
        │
        ▼
GRU Layer (128 Units)
        │
        ▼
Dense Output Layer
        │
        ▼
Generated Characters

📊 Visualizations

The project includes the following graphs:
Training Loss
Training Accuracy
Character Frequency Distribution
Sentence Length Distribution
Top 15 Most Frequent Characters

📈 Training Configuration
Parameter	Value
Model	GRU
Embedding Size	64
GRU Units	128
Sequence Length	40
Batch Size	32
Optimizer	Adam
Epochs	5

▶️ How to Run
Clone Repository
git clone https://github.com/yourusername/Handwritten-Text-Generation.git
Install Dependencies
pip install -r requirements.txt
Run
python handwritten_text_generation.py

or open

handwritten_text_generation.ipynb

and run all cells.

📝 Sample Generated Text
Dear Friend,

Believe in yourself and keep learning.
Practice every day to improve your skills.
Success comes from consistency and patience.
Thank you for your support.

📊 Results
Successfully learned character-level language patterns.
Generated coherent handwritten-style text.
Achieved stable training loss and accuracy.
Demonstrated sequence modeling using recurrent neural networks.

🎯 Learning Outcomes
Character-Level Language Modeling
Recurrent Neural Networks (RNN)
GRU Networks
Sequence Prediction
Text Generation
TensorFlow/Keras Implementation

📌 Future Improvements
Replace GRU with LSTM
Train on larger handwriting datasets
Add Attention Mechanism
Generate paragraph-length text
Develop a web application using Streamlit

👨‍💻 Author

Shreyas Biware
ML INTERN 
