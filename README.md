# Voice-to-Text Infosys

A project demonstrating speech-to-text conversion using Python and modern AI/ML techniques. This repository provides a simple pipeline to capture audio, process it, and convert spoken words into text with accuracy and efficiency.

## Features

- **Speech Recognition**: Converts audio input into text.
- **Python-based Implementation**: Easy to run and extend.
- **Modular Design**: Separate scripts for audio capture, processing, and transcription.
- **Customizable**: Adaptable to different languages or models.

## Project Structure

- **app.py** – Main application entry point.
- **text_embedding.py** – Utilities for embedding and semantic processing.
- **llm.html** – Frontend interface for interacting with the model.
- **requirements.txt** – List of dependencies.
- **Basic_Home_Remedies.pdf** – Example document for testing QA features.
- **LICENSE** – MIT License.

## Getting Started

### Prerequisites
- Python 3.10+
- Pip (latest version)

### Installation
```bash
git clone https://github.com/DRAVINAS/voice-to-text-infosys.git
cd voice-to-text-infosys
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

---

## Usage

1. **Run the embedding script** (if using document QA):
   ```bash
   python text_embedding.py
   ```

2. **Start the application**:
   ```bash
   python app.py
   ```

3. **Open the frontend**:
   - Navigate to `http://127.0.0.1:5000` (or the port shown in terminal).
   - Use the interface in `llm.html` to test speech-to-text or document QA.

## How It Works

- **Audio Capture**: Records speech input.
- **Processing**: Cleans and prepares audio for recognition.
- **Transcription**: Converts speech into text using ML models.
- **Embedding + QA**: Optional step to query documents with semantic search.

This project is licensed under the MIT License. See the LICENSE file for details.
```

Would you like me to also add **badges** (e.g., Python version, license, build status) and a **screenshot section** to make the README more visually appealing?
