

---

# Gemini Pro Chatbot

This project is a conversational AI chatbot built using Gemini Pro and Streamlit. The chatbot leverages the capabilities of Gemini Pro for natural language understanding and processing, providing users with an interactive and responsive chat experience. Additionally, it uses a Google API key for accessing Google services.

## Features

- **Conversational AI**: Uses Gemini Pro to understand and respond to user inputs.
- **Interactive Interface**: Built with Streamlit to create a user-friendly web interface.
- **Google API Integration**: Utilizes Google API services for enhanced functionality.

## Prerequisites

Before running the application, ensure you have the following installed:

- Python 3.7 or higher
- Streamlit
- Gemini Pro SDK
- Google API Client Library for Python

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/dhar127/chatbot.git
   cd chatbot
   ```

2. **Create a virtual environment and activate it:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up your Google API key:**
   - Obtain your Google API key from the [Google Cloud Console](https://console.cloud.google.com/).
   - Create a `.env` file in the project directory and add your API key:
     ```
     GOOGLE_API_KEY=your_google_api_key_here
     ```

## Usage

To run the chatbot, execute the following command in your terminal:

```bash
streamlit run app.py
```

This will start the Streamlit server and open the chatbot interface in your web browser.

## Configuration

- **Streamlit Configuration**: Customize the Streamlit configuration as needed in the `app.py` file.
- **Gemini Pro Configuration**: Ensure your Gemini Pro SDK is properly configured and authenticated.
- **Google API Configuration**: Make sure your `.env` file is correctly set up with your Google API key.

## File Structure

- `app.py`: The main application file that sets up the Streamlit interface and handles user interactions.
- `requirements.txt`: Lists all the dependencies required for the project.
- `.env`: Contains the environment variables, including the Google API key.

## Contributing

If you wish to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements

- Special thanks to the developers of Gemini Pro and Streamlit for their amazing tools.
- Thanks to Google for providing the API services.

---


