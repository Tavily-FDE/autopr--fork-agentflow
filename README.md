# 🤖 Autonomous AI Market Research Agency

This repository contains a fully functional, autonomous multi-agent system built with **CrewAI** and powered by the **Google Gemini** LLM. 

Instead of relying on outdated internal knowledge, these agents are equipped with custom web-search tools to browse the live internet, gather real-time data, and autonomously collaborate to generate comprehensive business reports.

## 🌟 Key Features
* **Hierarchical Process**: The system is managed by an AI Manager who dynamically delegates tasks and reviews outputs, ensuring high-quality results.
* **Live Web Access**: Integrated with DuckDuckGo Search (`ddgs`) to pull the latest real-world data.
* **100% Free to Run**: Uses the generous free tier of Google Gemini API (no credit card required).
* **Markdown Reports**: Outputs clean, structured, and professional business reports.

## 👥 Meet the AI Crew
1. **The Manager**: Oversees the entire project, decides who does what, and approves the final results.
2. **Internet Researcher**: Uses custom Python tools to scrape search engines for specific data points.
3. **Market Analyst**: Processes the raw text found by the researcher, identifying key players, trends, and obstacles.
4. **Report Director**: Formats the analytical data into a beautiful, easy-to-read Markdown document.

## 🚀 How to Run This Project

### 1. Prerequisites
You will need Python installed on your machine (or just run it directly in a Google Colab notebook). You also need a free Google Gemini API Key, which you can get from [Google AI Studio](https://aistudio.google.com/).

### 2. Installation
Clone this repository and install the required dependencies:

```bash
git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
cd YOUR_REPOSITORY_NAME
pip install -r requirements.txt
