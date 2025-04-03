# Installation
1. Clone the repository:
```
git clone https://github.com/kimh7537/streamlit.git
cd streamlit
```
2. Create and activate a virtual environment:
```
python3 -m venv venv
source venv/bin/activate
```
3. Install the required dependencies:
```
pip install -r requirements.txt
```

# Usage
1. Run the Streamlit application:
```
streamlit run chat.py
```
2. Open your web browser and navigate to the displayed local URL to interact with the application.

# Project Structure
`chat.py`: Main application script that runs the Streamlit interface.
`llm.py`: Contains utility functions for handling the knowledge base and model interactions.
`config.py`: File with few-shot learning templates used to generate answers.

# How It Works
- Data Retrieval: The application retrieves relevant sections of the South Korean Income Tax Law based on user queries.
- Contextual Processing: Utilizes chat history to maintain context across multiple interactions.
- Template-Based Generation: Applies few-shot learning templates to enhance the accuracy and relevance of the generated answers.
User Interface: Provides an intuitive web interface through Streamlit for users to interact with the application seamlessly.
