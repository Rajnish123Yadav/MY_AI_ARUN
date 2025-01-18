# MY_AI_ARUN
MY_FIRST_WEB-SITE-USING HTML, CSS AND JAVASCRIPT NAMED AS ARUN(AS AI_VOICE ASSISTENT)


Arun, My Virtual Assistant

Overview

Arun is a voice-activated virtual assistant implemented using HTML, CSS, and JavaScript. This project features speech recognition, speech synthesis, and dynamic interaction to perform tasks like greeting the user, playing songs on YouTube, and responding to basic queries. It uses web APIs for voice recognition and synthesis, providing a seamless and interactive user experience.

Features

1. Greeting Based on Time

The assistant greets the user with "Good Morning," "Good Afternoon," or "Good Evening" depending on the time of day.

This feature is triggered automatically when the webpage loads.

2. Speech Recognition

Users can interact with Arun by clicking the "Click here and talk to me..." button to start voice recognition.

The assistant listens to user commands and processes them accordingly.

3. Speech Synthesis

Arun can respond audibly to user inputs using speech synthesis.

It uses the SpeechSynthesis API to generate voice output.

4. Play Songs on YouTube

Users can enter a song name in the input box or use voice commands to specify the song.

Arun searches for the song on YouTube and opens the results in a new tab.

5. Dynamic User Interaction

Arun responds to various commands such as:

"What’s your name?"

"What are you doing?"

"What is the time/date?"

If Arun doesn’t recognize a command, it prompts the user to try again.

6. Error Handling

Handles common errors like lack of microphone permissions or speech input.

Provides user-friendly messages for troubleshooting.

Files

1. HTML File

Contains the structure of the virtual assistant, including:

A heading introducing Arun.

Buttons and input fields for user interaction.

Embedded JavaScript for dynamic functionality.

2. CSS (Embedded)

Styles the assistant interface with modern and responsive design:

Responsive layout for different screen sizes.

Hover effects and transitions for a polished user experience.

Custom fonts for aesthetic appeal.

3. JavaScript

Implements the core functionality:

Speech recognition and synthesis using web APIs.

Time-based greeting functionality.

Commands for playing YouTube songs.

Error handling and dynamic updates to the user interface.

Setup Instructions

Prerequisites

A modern web browser (e.g., Google Chrome, Mozilla Firefox) with support for Web Speech API.

An active internet connection to open YouTube links.

Steps

Clone or download the project files to your local machine.

Open the HTML file in a supported browser.

Ensure the browser has microphone permissions enabled.

Interact with Arun by clicking buttons or typing commands.

Usage Guide

1. Launch the Application

Open the HTML file in a browser.

2. Interact with Arun

Greet Arun: Speak or type "Hello" or "Hi."

Ask for the Time/Date: Say "What is the time/date?"

Play Songs: Enter a song name or say "Play [song name]."

Test Responses: Try commands like:

"What’s your name?"

"What are you doing?"

"Who is your mama?"

3. Error Handling

If the assistant doesn’t respond, ensure microphone permissions are granted.

Refresh the browser if speech recognition stops working.

Technical Details

APIs Used

SpeechSynthesis API: Converts text to speech.

SpeechRecognition API: Captures and processes user voice commands.

Browser Compatibility

Fully compatible with modern browsers that support the Web Speech API.

Enhancements

Add more commands for Arun to respond to.

Integrate additional APIs for tasks like weather updates or reminders.

License

This project is open-source and available for modification and redistribution. Contributions are welcome.

Acknowledgements

Web Speech API documentation

Open-source fonts from Google Fonts

Icon resources used in the project

