# Extractive-Text-Summarization

Text summarization in an important application of Natural Language Processing which aims to procude a concise summary of the original text while retaining key information. This project focuses on one of the two methods of summarizing text, that is Extractive Summarization.

Here is the Deployed version of the project Heroku:https://textsummary12.herokuapp.com/


TExt_Summarisation Code : [Praveen Dubey] link for his portfolio:  https://gist.github.com/edubey/cc41dbdec508a051675daf8e8bba62c5

# Prerequisites for the project
You must have following python libararies(Specified-vesrion) installed on your machine. Please refer to requirements.txt file for more details about the packages .
- Flask (for creating web application)
- NLTK (for Natural Language Processing)
- Networkx (for using graph based algorithms)

# Project Structure
The projects has following major parts:
1. app.py : Contains Flask APIs that receive inputs through GUI, calls the main python script for processing and returns the output.
2. textsummarizer.py : Contains python code to generate text summary from original/source text.
3. templates : Contains HTML files that allow user to interact with the application.

# Running the Project in Local Machine
1. Open Ananconda command prompt and move to your project home directory.
2. Run app.py using below command to start Flask API
python app.py
3. Navigate to the localhost to view the application home page. Localhost:  http://127.0.0.1:5000/ or http://localhost:5000
4. Enter the text to summarize in the texbox and hit Summarize button.
5. If everything goes well, you should be able to see the summarized version of the text on the results page.



