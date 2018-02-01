# Color Your Thoughts
Color Your Thoughts is an interactive Javascript browser-based experiment that paints your screen in color palettes based on your spoken words.

## Setup
1. Download: ```git clone https://github.com/JeffJassky/Color-Your-Thoughts.git```
2. Install: ```npm install```
3. Launch: ```node server.js```
4. View: ```http://localhost:3000```

## Usage
1. Find a quiet space
2. Enable your microphone
3. Speak a colorful word or phrase.

## How does it work?
Color Your thoughts uses your microphone to capture words and phrases.
Speech Recognition is used to translate your audible speech to text.
A Google Images search is performed on your text.
Colors from the resulting images are represented as a vibrant palette on the screen.

## What's next?
### Polishing what's here
Adding loading indicators between search terms, circumventing daily limitations on Google Images API, fixing edge cases like sitting idle for long periods of time, limit search to photographs only (the API documentation for this doesn't seem to be working)
### Feature ideas
Saving individual color palettes & color palette history, adding audio for ambient sounds and user cursor and voice interactions.
