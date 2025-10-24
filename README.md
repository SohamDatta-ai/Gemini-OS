# Gemini 95

## Description

Gemini 95 is a web-based simulator that recreates the nostalgic experience of the Windows 95 operating system, with a modern twist. Several classic applications are enhanced with the power of the Google Gemini API, offering unique AI-driven features. This project is a demonstration of integrating a powerful language model into a retro user interface.

## Features

The Gemini 95 desktop includes the following applications:

*   **My Gemtop**: A simple file explorer simulation.
*   **Chrome**: A simulated web browser that uses Gemini to generate entire 90s-style websites on the fly based on the domain you enter.
*   **GemNotes**: A text editor that can write creative stories for you with the click of a button.
*   **GemPaint**: A simple drawing program featuring an AI art critic that provides witty feedback on your creations.
*   **Doom II**: An embedded version of the classic game for a truly retro experience.
*   **Gemini App**: A dedicated chat client to interact directly with the Gemini model.
*   **GemSweeper**: The classic Minesweeper game, equipped with an AI-powered hint system to suggest your next move.
*   **GemPlayer**: A media player capable of streaming videos from YouTube.

## How to Run

To run this project locally, follow these steps:

1.  **API Key**: This project requires a Google Gemini API key. You need to set it as an environment variable named `GEMINI_API_KEY`.

2.  **Serve Locally**: Since the project uses ES modules, you need to serve the files from a local web server. You can use a simple server like Python's `http.server` or Node's `http-server`.
    ```bash
    # If you have Python 3
    python -m http.server
    ```

3.  **Open in Browser**: Open your web browser and navigate to the local server's address (e.g., `http://localhost:8000`).

## Technologies Used

*   HTML5
*   CSS3
*   TypeScript
*   Google Gemini API (`@google/genai`)
*   Tailwind CSS (via CDN)

## Credits

This project was originally created by @ammaar and @olacombe.
