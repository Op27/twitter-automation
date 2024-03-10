# Twitter Automation for Inspiring Phrases

## Introduction
This project automates the posting of inspiring phrases from famous people to a Twitter account. It uses Make.com to connect Google Sheets, where the phrases are stored, to Twitter, enabling scheduled tweets and efficient social media management.

## Technologies Used
- Make.com for workflow automation
- Google Sheets for storing tweet data
- Twitter API for posting tweets

## Problem Statement
Consistent engagement on Twitter requires regular posting, which can be time-consuming and requires daily attention. This project aims to automate the process, ensuring a steady stream of quality content with minimal manual intervention.

## Solution Overview
The solution involves a Make.com automation that triggers tweets based on a schedule defined in a Google Sheet. Each row in the sheet contains a quote, the name of the person who said it, and the scheduled posting time. The automation checks for new entries and posts them to Twitter accordingly.

## How It Works
1. **Google Sheets Setup**: A spreadsheet is set up with columns for the quote, author, and scheduled posting time.
2. **Make.com Automation**: The automation is configured to watch for new rows in the Google Sheet and post the content to Twitter at the specified times.
3. **Twitter Posting**: Tweets are automatically created and posted to the configured Twitter account according to the schedule.

## Setup and Installation
To replicate this project, you'll need:
1. A Google Sheets document with your content.
2. A Make.com account to create the automation.
3. Access to the Twitter API by creating a Twitter developer account and setting up an application.

Sample: List of contents created in Google Sheets

  <img width="659" alt="Sample Google Sheet" src="https://github.com/Op27/twitter-automation/assets/39921621/c5e8ac8d-f767-4988-898b-0736a989c7c8">

Sample: Scenario applied in Make.com

  <img width="659" alt="Scenario applied for Make com " src="https://github.com/Op27/twitter-automation/assets/39921621/c5376329-0604-4efe-9269-4319cd57f3fa">


Detailed steps:
- [Google Sheets Template](#) (Link to a template or setup guide)
- [Make.com Automation Setup](#) (Link to detailed setup instructions)
- [Twitter API Access Guide](#) (Link to Twitter API setup instructions)

## Challenges and Solutions
**Date and Time Formatting**: Ensuring the date and time in Google Sheets match Twitter's requirements was solved by using the ISO 8601 format directly in the spreadsheet.

## Future Enhancements
- Expanding the content library with more quotes.
- Automating the contents generation by connecting with AI text generators, e.g. ChatGPT
- Including images with tweets.
- Analyzing tweet engagement to optimize posting times.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
