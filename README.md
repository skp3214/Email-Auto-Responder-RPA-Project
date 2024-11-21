# 📧 Email Auto Responder Project

## 🚀 Project Overview

This UiPath automation project creates an intelligent email auto-responder system that automatically processes and replies to incoming emails based on predefined keywords and responses.

![image](https://github.com/user-attachments/assets/96aa7566-1851-4e73-bbe6-b8acf4eee3bf)

## ✨ Key Features

- **Automatic Email Retrieval**: Fetches unread emails from Gmail inbox
- **Keyword-Based Response**: Analyzes email content against a predefined keyword matrix
- **Smart Filtering**: Handles emails with subject "Help Desk"
- **Customizable Responses**: Uses Excel spreadsheet to manage keywords and replies
- **SMTP Email Sending**: Automatically sends appropriate responses

## 🛠 Technical Architecture

### Components
- **IMAP Mail Retrieval**: Fetches latest unread emails
- **Excel Keyword Mapping**: Stores response templates
- **Conditional Processing**: Matches email content with keywords
- **SMTP Email Sending**: Sends automated responses

### Workflow Logic
1. Retrieve unread emails from Gmail
2. Filter emails with "Help Desk" subject
3. Check email body against keyword spreadsheet
4. Send appropriate response
   - Matching keyword: Custom predefined response
   - No match: Generic "cannot help" message

## 📋 Prerequisites

- UiPath Studio
- Gmail Account
- Excel Spreadsheet (KeywordAndResponses.xlsx)
- Internet Connection

## 🔧 Configuration

1. Update Gmail credentials in IMAP/SMTP activities
2. Modify `KeywordAndResponses.xlsx` with your keywords and responses
3. Adjust file path in "Read Range" activity

## 💡 Usage Instructions

1. Open project in UiPath Studio
2. Configure credentials and file paths
3. Run the workflow
4. Monitor automated email responses

## 🔒 Security Notes

- Use app-specific passwords for Gmail
- Keep credentials secure
- Recommended: Use environment variables or secure credential storage

## 📊 Performance Metrics

- Processes up to 5 unread emails per execution
- Configurable timeout settings
- Supports SSL/TLS secure connections

## 🌟 Potential Enhancements

- Add logging mechanism
- Implement more advanced NLP for keyword matching
- Create a more sophisticated response generation system

## 👥 Contributors

- Sachin Prajapati
- Azhar
- Akmal
- Shashwat
---

**Made with ❤️ using UiPath**
