Travel Guide Chatbot
A simple, rule-based travel guide chatbot built with Python and JavaScript that provides facts about five countries (India, South Africa, Australia, USA, and Sri Lanka) and their famous things and places. The backend runs a Flask application served by Gunicorn.
✨ Features
Travel facts: Provides information on cities, countries, and their famous landmarks and attractions.
Rule-based responses: Delivers pre-defined facts based on user inputs.
Interactive interface: A user-friendly web interface for real-time interaction.
Production-ready server: Uses Gunicorn, a production-ready WSGI server, to handle requests efficiently and provide scalability.
🛠️ Technologies Used
Python: Backend logic using the Flask framework.
Gunicorn: A Python WSGI HTTP server used to run the Flask application in a production environment.
JavaScript: Frontend interactivity, managing user input, and displaying responses.
HTML/CSS: Structure and styling of the chatbot interface.
🚀 Installation
To run this project locally, follow these steps:
Clone the repository:
bash
git clone https://github.com
Use code with caution.

Navigate to the project directory:
bash
cd Chatbot
Use code with caution.

Install Python dependencies:
The project uses a requirements.txt file listing Flask and Gunicorn. It's recommended to use a virtual environment:
bash
# Optional: Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt
Use code with caution.

Run the application (for development):
You can run the Flask app locally for development:
bash
python app.py
Use code with caution.

For production, you would typically use gunicorn directly:
bash
gunicorn app:app
Use code with caution.

💡 Usage
Open your web browser and navigate to the local address provided in your terminal output (e.g., http://127.0.0.1 or http://127.0.0.1).
Type options to see the list of available countries.
Enter the corresponding number (1 to 5) for the country you want facts about.
🤝 Contributing
Contributions are welcome! If you'd like to improve the chatbot, please consider:
Adding more countries, cities, and famous places to the responses.js file.
Improving the frontend design or adding more advanced natural language processing features.
Please fork the repository and submit a pull request with your changes.
👤 Author
Nishank1403 (Project Creator and Maintainer)
'''
