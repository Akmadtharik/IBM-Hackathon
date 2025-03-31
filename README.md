# AI-Powered Workflow Assistant

A chat-based productivity tool built for a hackathon, leveraging IBM watsonx.ai's Granite-13B-Instruct model and Streamlit for a sleek frontend. This assistant helps users prioritize tasks, summarize meetings, and generate follow-up emails—all in a simple, interactive interface.

## Features
- *Task Prioritization*: Input a task list with deadlines, get a prioritized order with reasoning.
- *Meeting Summarization*: Paste a meeting transcript, receive a concise 2-3 sentence summary.
- *Follow-Up Generation*: Request an email follow-up, get a professional, actionable draft.

## Tech Stack
- *Backend*: IBM watsonx.ai (Granite-13B-Instruct model)
- *Frontend*: Streamlit (Python-based web app)
- *Dependencies*: ibm-watson-machine-learning, streamlit

## Prerequisites
- Python 3.8+
- An IBM Cloud account with watsonx.ai access
- API key and Project ID from watsonx.ai (see [IBM Cloud Docs](https://cloud.ibm.com/docs))

## Setup
1. *Clone the Repository*:
   bash
   git clone https://github.com/Akmadtharik/IBM-Hackathon
   cd ai-workflow-assistant
   

2. *Install Dependencies*:
   bash
   pip install -r requirements.txt
   

3. *Configure watsonx.ai Credentials*:
   - Open app.py and replace the placeholders:
     - API_KEY = "your-api-key-here"
     - PROJECT_ID = "your-project-id-here"

4. *Run the App*:
   bash
   streamlit run app.py
   
   - Open your browser to http://localhost:8501 to use the assistant.

## Usage
- Launch the app and type your request in the chat input box.
- Examples:
  - "Prioritize these tasks: 1) Call client (due tomorrow), 2) Finish slides (due today)"
  - "Summarize: Alice: Budget due Friday. Bob: I’ll review it."
  - "Write a follow-up for Bob about the budget."

## Project Structure

ai-workflow-assistant/


├── workflow.py              # Streamlit frontend and watsonx.ai integration


├── requirements.txt    # Python dependencies


└── README.md           # This file


## Demo
Built for a hackathon, this tool showcases productivity gains with a clean UI and powerful AI. Try it out and streamline your workflow!

## Notes
- Tested with Granite-13B-Instruct on March 30, 2025.
- Ensure your IBM Cloud account has watsonx.ai credits or a trial active.

## License
MIT License - feel free to adapt and share!
