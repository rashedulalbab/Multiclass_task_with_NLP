# Multiclass_task_with_NLP

Multi-Task Learning for NLP:Emotion, Violence, and Hate Speech Classification

This project showcases a sophisticated multi-task learning (MTL) model for natural language processing (NLP), designed to classify text into three distinct categories: Emotion, Violence, and Hate Speech, each with specific sub-labels. Leveraging a shared neural architecture, the model efficiently processes text to predict nuanced classifications, demonstrating advanced NLP techniques.

Project Highlights:





Objective: Develop a robust MTL model to simultaneously detect emotions (Sadness, Joy, Love, Anger, Fear, Surprise), types of violence (Harmful Traditional Practice, Physical, Economic, Emotional, Sexual), and hate speech (Hate Speech, Offensive Speech, Neither).



Datasets:





Emotion.csv: Text labeled with six emotion categories.https://www.kaggle.com/datasets/nelgiriyewithana/emotions



Violence.csv: Text labeled with five violence types.https://www.kaggle.com/datasets/gauravduttakiit/gender-based-violence-tweet-classification

Hate.csv    :  Text labled with three hates types.https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset



Methodology: Utilizes TensorFlow/Keras for a multi-output neural network, with text preprocessing via NLTK and Keras Tokenizer for vectorization.



Interactive Testing: Features an intuitive ipywidgets interface for real-time text classification, enhancing user interaction and model evaluation.

Requirements:





Python 3.8+



Libraries: pandas, numpy, nltk, tensorflow, sklearn, ipywidgets, seaborn, matplotlib



Optional: GPU support (e.g., Google Colab with T4) for faster training and inference.

Key Features:





Multi-Task Efficiency: Shared text embeddings optimize computational resources across three classification tasks.



Robust Preprocessing: Employs stopword removal and sequence padding for consistent input representation.



User-Friendly Interface: Interactive widget for seamless text input and classification output.



Scalable Design: Model architecture supports extension to additional NLP tasks or datasets.

Example:

Input: "you are a boring person"
Output: Major Label: Violence, Sub Label: emotional_violence

