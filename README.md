# ChatMaven

ChatMaven is a web-based chatbot application built using Flask and integrated with Google's generative AI for conversational responses. It allows users to interact with a chatbot interface and receive formatted responses in real-time.

## Table of Contents

- [Features](#features)
- [Setup](#setup)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Interactive chat interface with a responsive design.
- Integration with Google's generative AI for natural language processing.
- Markdown support for formatting bot responses.
- Copy and audio playback options for messages.

## Setup

To run ChatMaven locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/shahram8708/ChatMaven.git
   cd ChatMaven
   ```

2. **Install dependencies:**

   Ensure you have Python installed. Then, install the required Python packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables:**

   Export your Google API key as an environment variable:

   ```bash
   export API_KEY='your_google_api_key'
   ```

   Replace `'your_google_api_key'` with your actual API key.

4. **Run the application:**

   Start the Flask development server:

   ```bash
   python app.py
   ```

   The application will be accessible at `http://localhost:5000`.

## Dependencies

The following Python packages are used in this project:

- Flask
- google
- markdown

These dependencies are listed in `requirements.txt`.

## Usage

1. Open your web browser and go to `http://localhost:5000`.
2. Type a message in the input field and press Enter or click the send button.
3. The chatbot will respond with a formatted message based on your input.
4. You can copy messages to the clipboard or listen to them using the audio button.

## Contributing

Contributions are welcome! Here are a few ways you can contribute:

- Report bugs and help triage issues.
- Suggest new features or improvements.
- Submit your own fixes or enhancements via pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
