# Open_Assistant

## Overview
Open_Assistant is an innovative voice assistant that leverages the power of open-source projects to provide an array of functionalities, from answering queries to managing smart devices, all through voice commands. It is designed to enhance user interaction with technology by offering a customizable and modular voice-controlled interface. The assistant is split into three main scripts for modularity and ease of development:
- **Ears**: Utilizes Whisper from OpenAI for voice recognition.
- **Brain**: Leverages LM Studio for processing natural language and generating responses.
- **Voice**: Uses OpenVoice for generating spoken responses.

## Features
- Advanced voice recognition and processing.
- Modular architecture for easy customization and expansion.
- Integration capabilities with smart home technologies.
- Expandable with user-created modules for various tasks.

## Installation

### Prerequisites
- Python 3.6 or newer.
- pip for Python package management.

### Steps

1. **Install OpenVoice**:
   - Follow the installation guide for OpenVoice from its official repository or documentation page. This typically involves cloning the OpenVoice repository and installing its dependencies.

2. **Integrate Open_Assistant**:
   - Clone this repository:
     ```bash
     git clone https://github.com/stephenschoettler/Open_Assistant.git
     ```
   - Navigate to the Open_Assistant directory:
     ```bash
     cd Open_Assistant
     ```
   - Install required Python dependencies. It's important to do this after setting up OpenVoice, as there might be dependencies that are common or that need specific versions:
     ```bash
     pip install -r requirements.txt
     ```

## Usage

To launch Open_Assistant, execute the main script from the terminal:

```bash
python assistant.py
