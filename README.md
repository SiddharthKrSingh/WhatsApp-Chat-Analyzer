#  WhatsApp-Chat-Analyzer

A Streamlit-based web application to analyze WhatsApp chat data, generating various insights like user statistics, activity timelines, and more. This project processes exported WhatsApp chats and provides a detailed analysis of the messages exchanged in a group or individual chat.

## Features

1. ### Overall Statistics:
   Total messages, total words, media shared, and links shared.
   
3. ### Activity Analysis:
   
    a. Monthly and daily timelines of chat activity.
   
    b. Most active users and word clouds.
   
    c. Busy days and most active hours.
   
    d. Weekly and hourly activity heatmaps.
   
5. ### User-Level Analysis:
   Filter data based on individual users or view overall group activity.

## Live Demo

You can access the live version of the application here:


## File Structure
1. ### app.py:
   The main file that runs the Streamlit app. It handles file uploads, calling helper functions, and displaying results.
   
2. ### helper.py:
   Contains functions to compute statistics, activity timelines, and heatmaps.
   
3. ### preprocessor.py:
   Preprocesses the raw WhatsApp chat data by extracting date-time information, users, and messages.


