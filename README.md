# Text-To-Speech 
Text-to-Speech Converter

This project is a simple GUI-based Text-to-Speech (TTS) converter built using Python's tkinter and pyttsx3 libraries. The application allows users to enter text, select a voice, and convert the text into speech. The output is also saved as an audio file (output.mp3).


---

## Features

1. Voice Selection: Choose from available system voices.


2. Text Input: Enter the text you want to convert to speech in the provided text area.


3. Text-to-Speech Conversion: Listen to the text being read out loud.


4. Audio File Export: Automatically saves the converted speech as an output.mp3 file.




---

## Prerequisites

Required Libraries

Python 3.7 or higher

pyttsx3

tkinter (comes pre-installed with Python)



---

## Installation

1. Clone this repository or copy the code:

git clone https://github.com/yourusername/text-to-speech-converter.git
cd text-to-speech-converter


2. Install the required library:

pip install pyttsx3


3. Run the script:

python text_to_speech.py




---

## Usage

1. Launch the application:

python text_to_speech.py


2. Select a Voice:

Choose a voice from the dropdown menu in the "Select Voice" section.



3. Enter Text:

Type or paste the text you want to convert in the text input area.



4. Convert to Speech:

Click the "Convert to Speech" button to hear the text being read aloud.



5. Output File:

The speech is saved as output.mp3 in the same directory as the script.





---

## Troubleshooting

1. No Voices Available:

Ensure your system has text-to-speech voices installed.

Install additional voices based on your operating system.



2. Permission Errors:

Ensure you have write permissions for the directory where the script is run.



3. Error During Conversion:

Ensure the text entered is valid and not empty.





---

## Customization

1. Adjust Speech Rate: Modify the speech rate by changing this line:

engine.setProperty('rate', 150)  # Adjust the rate (default: 150)


2. Adjust Volume: Modify the volume by changing this line:

engine.setProperty('volume', 0.9)  # Set volume (range: 0.0 to 1.0)


3. Change Output Filename: Update the filename in the convert_text_to_speech function:

engine.save_to_file(text, "desired_filename.mp3")




---

## License

This project is open-source and available under the MIT License. Feel free to modify and enhance it as needed!


---

## Author
  DamarasinguGayathri

