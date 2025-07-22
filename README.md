# ChatFlow Insights

## 🌟 Overview

ChatFlow Insights is a simple, browser-based web application designed to analyze your WhatsApp chat data. Upload your chat history, and the app will provide insightful metrics and visualizations about your conversation patterns, message balance, reply times, emoji usage, and overall conversation frequency. It's built to offer a deeper understanding of your digital relationships and bonding, inclusive of all relationship types (boy-girl, girl-boy, boy-boy, girl-girl).

## ✨ Features

* **Chat Data Upload:** Easily upload your WhatsApp `.txt` chat export file.
* **Dynamic Analysis:** Automatically parses your chat to extract key communication metrics.
* **Love Score Calculation:** Generates a "Love Score" percentage based on factors like reply speed, message balance, emoji usage, and consistency.
* **Detailed Metrics Overview:** Displays total messages, average reply time, and media count.
* **Dynamic Time Units:** Reply times are intelligently displayed in minutes, hours, days, months, or years for easy understanding.
* **Reply Time Distribution Chart:** Visualizes how frequently different reply speeds occur in your chat using an interactive Plotly chart.
* **Emoji Usage Chart:** Shows a breakdown of the most used emojis in your conversation.
* **Conversation Frequency Chart:** Provides a daily overview of message exchanges from the start of the chat to the current date.
* **Live Processing Logs:** See real-time updates and debug messages directly on the UI as the analysis progresses.
* **Clear Error Handling:** User-friendly messages guide you through file format issues or missing data.

## 🚀 How to Use

1.  **Export Your Chat:**
    * **WhatsApp (Mobile App):** Open the chat > Tap three dots/contact name > More/Export Chat > Choose "Without Media." This will generate a `.txt` file.
    * **Instagram:** Instagram does not directly export `.txt` chat files. You can request a full data download (usually JSON or HTML) from your Instagram settings, and then manually extract the messages if needed.
2.  **Open the Application:** Navigate to the hosted application URL (e.g., your Vercel deployment link).
3.  **Upload File:** Click on the "Upload your chat file" section and select your `.txt` chat export.
4.  **Start Analysis:** Click the "Start Analysis" button.
5.  **View Insights:** The application will process your chat and display the analysis results, including your Love Score and various charts.

## 🛠️ Tech Stack

* **HTML5:** For the page structure.
* **CSS3:** For styling and layout.
* **JavaScript (Vanilla JS):** Powers the chat parsing, data analysis, and UI interactions.
* **Plotly.js:** A robust JavaScript graphing library used for interactive data visualizations.