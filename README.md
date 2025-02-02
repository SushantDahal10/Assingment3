# Assingment3

This project evaluates pre-trained conversational models (DialoGPT, BlenderBot, ChatGPT) using the TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) method. The goal is to rank these models based on multiple performance metrics, including:

BLEU: Measures text generation quality.
Response Coherence: Assesses logical flow in responses.
Diversity: Evaluates the variety of generated responses.
Latency: Measures response time (lower is better).
The code normalizes the data, applies weights to criteria, and calculates TOPSIS scores to determine the best-performing model. Results are visualized using a bar chart and saved as a CSV file.

Key Features:
Multi-criteria decision-making for conversational AI models.
Visualization of performance through a bar chart.
Easily configurable metrics and weights for different evaluation needs.
This project helps identify the most optimal model for conversational tasks based on user-defined criteria.
