# DefenceX

## Description
DefenceX is a web application designed to analyze phone calls for potential scams. It utilizes audio transcription and advanced analysis techniques to provide users with insights into the nature of their calls.

## Features
- Upload audio files for analysis.
- Convert audio to WAV format.
- Transcribe audio using Google Cloud's Speech-to-Text API.
- Analyze transcripts for suspicious content using the Gemini API.
- Render results on a user-friendly web interface.

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Bb-03/DefenceX.git
   cd DefenceX
   ```
2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up Google Cloud credentials and environment variables as needed.

## Usage Instructions
1. Run the application:
   ```bash
   python server.py
   ```
2. Open your web browser and navigate to `http://localhost:5000`.
3. Upload audio files and select the language for transcription.
4. Review the analysis results displayed on the web interface.

## API Keys
Make sure to set up your Google Cloud and Gemini API keys. Update the relevant environment variables in your application.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
