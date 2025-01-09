# AI Chat App

A simple Android chat application that uses Google's Gemini API for AI-powered conversations.

## Setup

1. Clone the repository
```bash
git clone https://github.com/yourusername/aichat.git
```

2. Set up your Gemini API key:
   - Get an API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Add it to your environment variables:
     ```bash
     export GEMINI_API_KEY=your_api_key_here
     ```
   - For GitHub Actions, add the API key as a repository secret named `GEMINI_API_KEY`

3. Build the project:
```bash
./gradlew build
```

## Features

- Real-time chat interface with AI
- Message history persistence
- Clean and modern Material Design UI
- Dark mode support

## Requirements

- Android Studio Hedgehog (2023.1.1) or newer
- JDK 17
- Android SDK 34
- Minimum Android version: 6.0 (API 24)

## Architecture

- MVVM architecture pattern
- Kotlin Coroutines for asynchronous operations
- Hilt for dependency injection
- Room for local data persistence
- Retrofit for network calls

## License

This project is licensed under the MIT License - see the LICENSE file for details. 