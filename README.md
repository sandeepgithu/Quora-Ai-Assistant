# Quora-Ai-Assistant
Quorra AI Assistant Description: Quorra is an intelligent voice-controlled AI assistant designed to help you with a wide range of tasks, making your daily routines more efficient and engaging. Inspired by the digital character "Quorra," this assistant seamlessly integrates voice recognition, natural language processing


import os
import openai

# Use environment variable to set the API key
openai.api_key = os.getenv('OPENAI_API_KEY')

elif "create file" in query:
    say("Please say the name for your file.")
    filename_query = takeCommand().lower()
    filename = filename_query.replace("name", "").strip()  # Remove unnecessary keyword
    if filename:
        create_file(filename, "# Enter your Python code here...")
    else:
        say("I couldn't understand the file name. Please try again.")

import pyttsx3

# Initialize text-to-speech engine
engine = pyttsx3.init()

def say(text):
    engine.say(text)
    engine.runAndWait()

pip install pyttsx3

elif "run fan" in query:
    try:
        # Replace 'SomeFanControlApp' with the actual app name
        call(["open", "-a", "SomeFanControlApp"])  
        say("Running fan control application.")
    except FileNotFoundError:
        say("Fan control application not found.")



import re

# Function to sanitize filenames
def sanitize_filename(filename):
    return re.sub(r'[\\/*?:"<>|]', "", filename)

# In the ai() function
filename = sanitize_filename(prompt.replace(' ', '_').lower()) + ".txt"
