# product-description-generator
AI Product Description Generator is a Flask-based web application that uses Generative AI to automatically create product descriptions based on user input like product name and category.

Overview
AI Product Description Generator is a web-based application that uses Generative AI to automatically create high-quality product descriptions. Users simply enter a product name and category, and the system generates a professional and engaging description instantly.

Features

AI-based product description generation
Fast and real-time output
Simple and user-friendly interface
Dynamic prompt generation
Flask backend with API integration

Tech Stack
Frontend: HTML, CSS
Backend: Python (Flask)
AI Integration: Groq API
Model: LLaMA

Installation

Clone the repository
git clone https://github.com/shouryan7876-afk/ai-product-description-generator.git
Go to project folder
cd ai-product-description-generator/project
Install dependencies
pip install -r requirements.txt

API Key Setup

PowerShell
$env:GROQ_API_KEY="your_api_key_here"

CMD
set GROQ_API_KEY=your_api_key_here

Run Project
python app.py

Open in Browser
http://127.0.0.1:5000

How It Works
User enters product name and category → Backend creates prompt → API call to Groq → AI generates description → Output shown on screen

Example
Input: Running Shoes (Sports)
Output: A stylish and comfortable pair of running shoes designed for performance and durability.

Future Scope

Multi-language support
SEO optimized descriptions
Image-based input
Mobile app

References
Flask Documentation
Groq API Documentation
Python Documentation

Author
Shouryan
