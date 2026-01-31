# 🚀 SmartReach AI: Intelligent Cold Email Generator

**SmartReach AI** is a cutting-edge tool designed to revolutionize recruitment outreach for services companies. Leveraging the power of **Groq**, **LangChain**, and **Streamlit**, this application automates the process of crafting hyper-personalized cold emails.

Simply input the URL of a company's careers page, and SmartReach AI extracts job listings, analyzes requirements, and matches them with your relevant portfolio links sourced from a vector database. The result? Tailored, high-impact emails that get replies.

![App Screenshot](imgs/img.png)

## 🏗️ Architecture
The system utilizes a modern AI stack to process data efficiently:
1.  **Web Scraping**: EXTRACTS job descriptions from target URLs.
2.  **Vector Database**: RETRIEVES the most relevant portfolio case studies.
3.  **LLM (Groq)**: GENERATES personalized email drafts based on the job-portfolio match.

![Architecture Diagram](imgs/architecture.png)

## 🛠️ Tech Stack
-   **Frontend**: Streamlit
-   **LLM Integration**: LangChain
-   **Inference Engine**: Groq API
-   **Vector Store**: ChromaDB
-   **Language**: Python 3.10+

## 🚀 Getting Started

### Prerequisites
-   Get a Groq API Key: [console.groq.com](https://console.groq.com/keys)
-   Update `app/.env` with your key: `GROQ_API_KEY=your_key_here`

### Installation

1.  **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

2.  **Run the Application**:
    ```bash
    streamlit run app/main.py
    ```


