# Speech Recognition and AI-powered Chatbot using GPT-3

This program uses Speech Recognition library to receive input from a user's microphone, then processes the input using OpenAI's GPT-3 to generate a response, which is then outputted using a Text-to-Speech engine.
## Installation
To run this program, you will need to have the following Python Libraries installed:

- speech_recognition
- pyttsx3
- openai
- dotenv

You will also need to signup for an OpenAI API key, which you can do so on this link: https://beta.openai.com/signup/
## Usage
In order to run this program, add your OpenAI API key to a .env file. The key should be saved as:

  OPENAI_API_KEY=YOUR-API-KEY-HERE

Then, run the code. The program will take input from the microphone, process it using GPT-3, and generate a response that is outputted using a text-to-speech engine. The user can then continue the conversation by giving another input using voice.

## Troubleshooting
If you receive "Unknown value error" message, that could be due to the Speech Recognition API not being able to recognize your voice, and you may need to speak clearer. Additionally, if you receive an error involving the OpenAI API, make sure that your API key has been properly added to your .env file and that your file is in the correct directory.


#This is bugged
Currently there is an issue that the bot is stuck in a loop
