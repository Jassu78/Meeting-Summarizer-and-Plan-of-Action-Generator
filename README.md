# Meeting Summarizer and Plan of Action Generator

## Overview

The Meeting Summarizer and Plan of Action Generator is a tool designed to automate the process of summarizing meetings and generating actionable plans from meeting transcriptions. The project integrates with Microsoft Teams to retrieve recordings, transcribe audio, and summarize content into actionable points. It utilizes OpenAI's Whisper for transcription and Streamlit for the user interface.

## Features

- **Automated Recording Retrieval**: Automatically retrieves meeting recordings from OneDrive.
- **Transcription**: Uses OpenAI's Whisper to convert audio recordings into text.
- **Summarization**: Generates concise summaries and action points from meeting transcriptions.
- **Email Notifications**: Sends meeting summaries and action points to participants.
- **User Interface**: Built with Streamlit for easy interaction.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/jassu78/Meeting-Summarizer-and-Plan-of-Action-Generator.git
    ```
2. **Navigate to the Project Directory**:
    ```bash
    cd repository
    ```
3. **Install Dependencies**:
    Ensure you have Python installed, then install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Configuration

1. **Set Up API Keys**:
    - Obtain an API key from OpenAI for Whisper and set it up in the configuration file or environment variables.
    - Set up credentials for accessing OneDrive.

2. **Configuration File**:
    - Create a configuration file `config.json` and add the necessary API keys and credentials.

## Usage

1. **Start the Streamlit App**:
    ```bash
    streamlit run app.py
    ```
2. **Interact with the Application**:
    - Follow the prompts in the Streamlit interface to start recording, retrieve, and process meeting recordings.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have suggestions or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, feel free to contact [jaswanthjogi7815@gmail.com].

## working Screenshots

![Screenshot 2024-07-16 002712](https://github.com/user-attachments/assets/77329fba-4bb1-4d59-ba7e-3c0191976501)

![Screenshot 2024-07-16 002729](https://github.com/user-attachments/assets/7c45c626-44ad-4f23-9dac-5754556f567a)

![Screenshot 2024-07-16 002817](https://github.com/user-attachments/assets/42acb2a0-4422-4698-b2a8-107b22346af6)

![Screenshot 2024-07-16 002924](https://github.com/user-attachments/assets/bcc33e90-c35a-470e-8ada-9e55c6cb361c)
