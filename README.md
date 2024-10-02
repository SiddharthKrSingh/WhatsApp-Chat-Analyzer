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
https://whatsapp-chat-analyzer-j9p2.onrender.com/


## File Structure

1. ### app.py:
   The main file that runs the Streamlit app. It handles file uploads, calling helper functions, and displaying results.
   
2. ### helper.py:
   Contains functions to compute statistics, activity timelines, and heatmaps.
   
3. ### preprocessor.py:
   Preprocesses the raw WhatsApp chat data by extracting date-time information, users, and messages.


## How to Use

1. Export your WhatsApp chat without media.
   
3. Upload the exported .txt file using the file uploader in the app.
   
5. Select a user (or "Overall" for group analysis).
   
7. Click "Show Analysis" to see detailed insights and visualizations.


## Example Insights

1. Monthly and Daily Activity: Visualize message trends over time.
   
3. Busy Users: Identify the most active participants in a group chat.
   
5. Activity Heatmap: Get a heatmap of the most active days and hours.
   
7. Message Stats: View the number of messages, words, media, and links shared.


## Dependencies

1. ### streamlit:
    Web application framework.
2. ### pandas:
   Data analysis library for handling chat data.
3. ### matplotlib & seaborn:
    Visualization libraries for creating charts and plots.
