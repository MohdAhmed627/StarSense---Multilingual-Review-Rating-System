# ⭐ StarSense - Multilingual Review Rating System

StarSense is an AI-powered web application that predicts 1–5 star ratings from textual reviews using Natural Language Processing (NLP). Built with Gradio and Hugging Face Transformers, the application provides an intuitive interface for analyzing reviews related to products, movies, restaurants, and services.

The application uses the nlptown/bert-base-multilingual-uncased-sentiment model, a multilingual BERT-based sentiment analysis model capable of predicting star ratings across multiple languages.

### 🚀 Features
 Predicts 1–5 star ratings from review text.
 Supports multiple languages (English, French, German, Dutch, Spanish, and Italian).
 Displays the confidence score for every prediction.
 Modern and responsive Gradio web interface.
 Built-in review examples for quick testing.
 One-click Clear button.
 Fast inference using the Hugging Face Transformers pipeline.
 Responsive design suitable for desktop and mobile devices.
### Tech Stack
Python
Gradio
Hugging Face Transformers
BERT (Multilingual)
PyTorch
HTML & CSS (Gradio Custom Styling)
🤖 AI Model

This project uses the Hugging Face model:

Model: nlptown/bert-base-multilingual-uncased-sentiment

The model predicts:

⭐ 1 Star
⭐⭐ 2 Stars
⭐⭐⭐ 3 Stars
⭐⭐⭐⭐ 4 Stars
⭐⭐⭐⭐⭐ 5 Stars

along with a confidence score for each prediction.

🌐 Supported Languages
🇬🇧 English
🇫🇷 French
🇩🇪 German
🇪🇸 Spanish
🇮🇹 Italian
🇳🇱 Dutch
📷 Application Preview

(Add screenshots or a GIF of the application here.)

📂 Project Structure
StarSense/
│
├── app.py                 # Main Gradio application
├── requirements.txt       # Project dependencies
├── README.md              # Project documentation
└── assets/
    └── screenshot.png

cd StarSense

pip install -r requirements.txt

python app.py
💬 Example Review

Input

"This phone is amazing. The battery lasts all day and the camera quality is outstanding."

Prediction

⭐⭐⭐⭐⭐
5 Stars

Confidence Score:
99.84%
🎯 Future Improvements
Support additional multilingual sentiment models.
Add sentiment labels (Positive, Neutral, Negative).
Display confidence charts and visual analytics.
Maintain prediction history.
Enable CSV/Excel batch review analysis.
Deploy on Hugging Face Spaces or Streamlit Cloud.
Add dark mode and customizable themes.
📜 License

This project is intended for educational and learning purposes.

👨‍💻 Author

Mohd Ahmed

Artificial Intelligence & Data Science Student
Passionate about Machine Learning, NLP, Generative AI, and Large Language Models (LLMs).
