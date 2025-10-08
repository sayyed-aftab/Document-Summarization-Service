# Document-Summarizer
A document summarization tool using the OpenAI API to generate brief, detailed, or bullet-point summaries. It features a simple Gradio web interface and modular code for easy maintenance and readability.

## Features
- Accepts text input or file upload for summarization.
- Generates summaries in multiple styles: brief, detailed, or bullet points.
- Simple and interactive web interface built with Gradio.
- Modular and easy-to-maintain code structure.
- Handles different document sizes efficiently.
- Real-time summary generation using OpenAI API.

   ## Approach
The tool accepts input via a text area or file upload to provide flexibility for users.
OpenAI API is used for generating summaries in different styles (brief, detailed, bullet points) to offer versatile outputs.
The code is modular, with separate functions for input handling, API requests, and output display, ensuring readability and easier maintenance.
Gradio was chosen for the web interface because it allows a simple, interactive, and real-time user experience without complex web development.
Design decisions focused on simplicity, usability, and scalability, making it easy to extend the tool for additional features in the future.
