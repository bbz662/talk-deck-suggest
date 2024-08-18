# Talk Deck Suggest

Talk Deck Suggest is a web application that uses voice recognition to transcribe speech and provides AI-powered topic suggestions to keep conversations flowing. It's designed to assist in various scenarios such as presentations, interviews, or casual conversations.

## Features

- Real-time speech recognition (currently set to Japanese)
- AI-powered topic suggestions based on conversation context and history
- Simple and intuitive user interface
- Conversation history tracking
- Responsive design for various screen sizes

## Getting Started

### Prerequisites

- A modern web browser that supports the Web Speech API (e.g., Chrome, Edge)
- An API key for the Gemini AI model from Google

### Usage

1. Enter your Gemini API key in the provided input field.
2. (Optional) Enter any specific context for your conversation in the "Conversation Context" textarea.
3. Click the "Start voice recognition" button to begin capturing speech.
4. Speak clearly, and your words will be transcribed in real-time.
5. The application will automatically generate topic suggestions based on your conversation.
6. Click the "Stop voice recognition" button when you're done.

## Technology Stack

- HTML5
- CSS3
- JavaScript (ES6+)
- Web Speech API
- Google Gemini AI API

## Configuration

You can modify the following settings in the `TalkDeckSuggest` class:

- `recognition.lang`: Change the language for speech recognition (default is 'ja-JP' for Japanese)
- `outputMaxTokens`: Adjust the maximum number of tokens for AI-generated suggestions

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
