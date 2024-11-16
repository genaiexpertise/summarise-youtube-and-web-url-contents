# YouTube Video and Web Content Summarizer
***

A web application built with LangChain, Streamlit, and Python that summarizes the content of YouTube videos and websites from provided URLs.


## Table of Contents 

- Introduction 
- Features 
- Requirements 
- Installation 
- Usage 
 
     

## Introduction 

This application uses LangChain to fetch content from YouTube videos and websites, then summarizes the extracted data. The summary is displayed in a user-friendly format using Streamlit's interactive interface. 

## Features 

- Summarizes YouTube video descriptions and titles
- Extracts text summaries from website content (HTML, JSON-LD, etc.)

    

## Requirements 

- Python 3.8+
- Streamlit library (pip install streamlit)
- LangChain library (pip install langchain)
- YouTube Data API v3 (pip install google-api-python-client)
     

## Installation 

- Clone this repository: git clone https://github.com/your-username/youtube-summarizer.git
- Install dependencies: pip install -r requirements.txt

     

## Usage 

Running the Application 

To run the application, execute streamlit run app.py in your terminal. 
Providing a URL 


Enter a URL when prompted to summarize its content. The application will display the summary on the screen. 