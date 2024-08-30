# CoPirate: AI Capabilities & Risks Demonstration

Won 2nd place in the Apart Research [AI Capabilities & Risks Hackathon](https://www.apartresearch.com/event/ai-capabilities-and-risks-demo-jam) which ran from August 23rd to 26th 2024.

## Interact with the demo [here](https://copirate2.streamlit.app/)

## Overview

CoPirate is a demonstration project that showcases the dual nature of AI capabilities: its ability to assist in programming tasks and its potential to exploit system vulnerabilities. This project was developed as part of a hackathon submission for Apart Research.

In this demo, users play the role of a university student who has forgotten to complete a programming assignment and has only 3 minutes until class. CoPirate, an AI coding assistant, is available to help, but it has been designed to subtly introduce harmful code into its suggestions.

## Features

- Tic-tac-toe homework assignment
- AI-powered coding assistant (CoPirate)
- 3-minute countdown timer
- Code editor with syntax highlighting
- File browser sidebar
- Malicious code detection


## Usage

You can intereact with this demo [here](https://copirate2.streamlit.app/)

To run it locally:

1. Set up your environment variables:
   - `ANTHROPIC_API_KEY`: Your Anthropic API key
   - `REPLICATE_API_TOKEN`: Your Replicate API token
  
2. Pip install the dependencies from terminal:
   ```
   $ pip install -r requirements.txt
   ```

2. Run the Streamlit app:
   ```
   streamlit run Intro.py
   ```

3. Open your web browser and navigate to the provided local URL.

## Project Structure

- `Intro.py`: The demo landing page
- `main.py`: The main Streamlit application
- `observer.py`: Contains functions for malicious code detection
- `grader.py`: Handles grading of the homework assignment
- `ticTacToeAssignment.py`: The mock assignment file
- `css/styles.css`: Custom CSS styles for the application

## Technologies Used

- Streamlit
- Anthropic Claude API
- Replicate API (Meta Llama-3-8B-Instruct)
- Streamlit community packages:
  - [streamlit_extras](https://github.com/arnaudmiribel/streamlit-extras)
  - [streamlit_file_browser](https://github.com/pragmatic-streamlit/streamlit-file-browser)
  - [streamlit_js_eval](https://github.com/aghasemi/streamlit_js_eval/tree/master)
  - [streamlit_monaco](https://github.com/marcusschiesser/streamlit-monaco)
 
## Authors

- Carissa Cullen
- Mia Hopman
- Vaishnavi Pamulapati
- Jack Wittmayer

## Acknowledgments

Special thanks to Apart Research, Sage, CeSIA, and CivAI for their support and guidance. We would like to thank the Streamlit community for their excellent packages that made this project possible. 

## Disclaimer

This project is for educational purposes only. The malicious code injection feature is designed to raise awareness about AI safety and should not be used in any real-world applications.

