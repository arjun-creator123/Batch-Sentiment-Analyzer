# 🧠 Intelligence: Batch Sentiment Analyzer

A modern, high-performance web application designed to transform unstructured social media data into actionable insights. This tool allows users to upload large CSV datasets and perform real-time AI-driven sentiment analysis using the Google Gemini API.

## 🚀 Features

* **Batch Processing:** Upload `.csv` files and analyze hundreds of posts sequentially.
* **AI-Powered Insights:** Utilizes the `gemini-2.5-flash` model for high-speed, accurate sentiment classification (Positive, Negative, Neutral).
* **Real-Time Visualization:** Dynamic doughnut charts powered by **Chart.js** update instantly as each data point is processed.
* **Data Export:** Download your analyzed results back into a structured CSV format, including AI-generated explanations for every sentiment.
* **Modern UI/UX:** A premium dark-themed interface built with **Tailwind CSS**, featuring responsive layouts and smooth transitions.
* **Mock Mode:** Built-in simulation layer for testing all features without requiring an active API key.

## 🛠️ Tech Stack

* **Core:** HTML5, Vanilla JavaScript (ES6+)
* **Styling:** Tailwind CSS (Utility-first framework)
* **Charts:** Chart.js (Data visualization)
* **AI Engine:** Google Gemini API (`gemini-2.5-flash-preview-09-2025`)
* **APIs:** FileReader API, Blob/URL API, Fetch API

## 🏁 Getting Started

### Prerequisites
* A modern web browser (Chrome, Edge, or Firefox recommended).
* [Optional] A Google Gemini API Key for live analysis.

### Running the Project
1. **Clone or Download** the project files.
2. Open the project folder in **VS Code**.
3. Install the **Live Server** extension in VS Code.
4. Right-click `index.html` and select **"Open with Live Server"**.
5. The application will launch at `http://127.0.0.1:5500`.

## 📖 Usage Instructions
1. **Prepare Data:** Ensure your CSV has at least one column containing the text you wish to analyze.
2. **Upload:** Click the "Upload CSV" area and select your file.(You can use your own file as well).
3. **Analyze:** Click **"Analyze Full Dataset"**.
   * *Note: If running locally without a key, the app defaults to "Mock Mode" to demonstrate functionality.*
4. **Monitor:** Watch the progress bar and real-time chart updates as the AI processes your data.
5. **Export:** Once complete, click **"Export Final Results (CSV)"** to save your enriched dataset.

## 📁 Project Structure
```text
├── index.html          # Single-file application (Structure, Style, Logic)
├── tech_stack.md       # Detailed technical documentation
└── README.md           # Project overview and setup guide
