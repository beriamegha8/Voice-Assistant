# Voice Assistant - M&M
M&M is a simple voice-controlled assistant implemented in Python. It utilizes various libraries to perform voice recognition, web browsing, Wikipedia searches, and more.

# Features-
Voice Recognition: M&M can understand and process voice commands using the SpeechRecognition library.
Wikipedia Search: The assistant can search Wikipedia for information based on user queries.
Web Browsing: M&M can open YouTube, Google, Stack Overflow, Spotify, and WhatsApp Web using the webbrowser module.
Time Reporting: The assistant can provide the current time.
Code and Application Launch: M&M can open Microsoft VS Code and Spotify applications.
Send WhatsApp Message: The assistant can send instant WhatsApp messages using the pywhatkit library.
Email Sending: M&M can send emails (currently configured for Gmail) using the smtplib library.

# Usage-
Install required dependencies using pip install pyttsx3 speech_recognition wikipedia pywhatkit.
Run the script and initiate a conversation with M&M.
Speak commands such as "Open YouTube," "Search Wikipedia," "What's the time," etc.
You can enjoy the voice-controlled functionalities provided by M&M.

# Configuration-
Configure the email credentials in the sendEmail function to enable email-sending functionality.
Adjust the paths for specific applications (e.g., VS Code, Spotify) based on your system.

# Dependencies-
pyttsx3
speech_recognition
Wikipedia
pywhatkit

# Notes-
The script uses Google's speech recognition API for voice recognition.
Make sure to configure the email credentials and paths based on your requirements.
Feel free to customize and enhance the functionality as needed!
