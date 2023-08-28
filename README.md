YouTube Transcript Summarization with GPT-3

This repository contains code to automatically summarize the transcript of a YouTube video using OpenAI's GPT-3 language model. It takes a YouTube video URL as input, downloads the transcript, and generates a summary using GPT-3.

Prerequisites:

Before running the code, you need to install the required Python packages:

- pip install openai youtube_transcript_api scrapingbee

Additionally, you need to have API keys for both ScrapingBee and OpenAI.

Usage:

1. Clone the repository:

   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

2. Set up your API keys:

   Replace the placeholders bee_key and openai_key in the main.py file with your actual API keys.

3. Run the script:

   python main.py

4. Provide a YouTube video URL:

   Enter the URL of the YouTube video you want to summarize.

5. Output:

   The script will generate a summarized version of the transcript and save it to a file. If the summary is too long, it will further summarize the summary.

Files:

- main.py: The main script that interacts with the APIs and performs summarization.
- prompt_summary.txt: A template for the GPT-3 prompt used for summarization.
- prompt_rewrite.txt: A template for the GPT-3 prompt used for rewriting the summary.
- gpt3_logs/: A directory to store log files for GPT-3 responses.

Note:

This code is meant for educational purposes and serves as a basic example of how to use OpenAI's GPT-3 for text summarization. It may require further customization and error handling for production use.

Disclaimer: Be aware of the costs associated with using APIs like ScrapingBee and OpenAI. Make sure to review the terms and conditions of these services before using them extensively.

