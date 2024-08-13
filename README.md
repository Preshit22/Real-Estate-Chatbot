# Real-Estate-Chatbot
Developed an AI-powered real estate chatbot using Streamlit, supporting text and audio inputs, Excel/CSV uploads, and OpenAI's GPT-4 and Whisper models. Includes session management for saving and reviewing chat histories, utilizing Streamlit, Pandas, and OpenAI API.

# Table of Contents
 1. Project Overview
 2. File Structure
 3. Setup and Installation
 4. Usage
 5. Data Description
 6. Scripts Description
 7. License

#Project Overview
The Real Estate Chatbot aims to provide insights into the housing market across different cities using various data analysis techniques. It includes a chatbot interface for real estate inquiries, implemented through a combination of Python scripts and multimedia components.

# File Structure

  ├── .env
  ├── audio_v2.py
  ├── Bangalore  house data.csv
  ├── changes.txt
  ├── Delhi house data.csv
  ├── Housing.csv
  ├── logo_img.jpeg
  ├── main.py
  ├── main_v1.py
  ├── Pune house data.csv
  ├── requirements.txt
  ├── temp_audio.mp3
  ├── utils.py
  ├── v1.py

# Setup and Installation
To set up the project, follow these steps:

1. Clone the repository:
  git clone <repository-url>
  cd realestate

3. Create a virtual environment and activate it:
  python3 -m venv venv
  source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

4. Install the required packages:
  pip install -r requirements.txt

5. Set up the environment variables:
  Create a .env file in the project root directory.
  Add the necessary environment variables as specified in the .env file.

# Usage
  ## Running the Main Script
  To run the main script for analyzing real estate data, use the following command:
  Streamlit run main.py

# Data Description
 1. Bangalore house data.csv: Contains housing data specific to Bangalore.
 2. Delhi house data.csv: Contains housing data specific to Delhi.
 3. Housing.csv: General housing data.
 4. Pune house data.csv: Contains housing data specific to Pune.

# Scripts Description
1. .env: Environment variables for the project.
2. audio_v2.py: Script for handling audio interactions with the chatbot.
3. main.py: Main script for data analysis.
4. main_v1.py: An older version of the main script.
5. utils.py: Utility functions used across the project.
6. v1.py: An alternative version of the main script.
7. changes.txt: Log of changes made to the project.
8. temp_audio.mp3: Temporary audio file used in the project.
9. logo_img.jpeg: Logo image for the project.

# License
This project is licensed under the MIT License.
