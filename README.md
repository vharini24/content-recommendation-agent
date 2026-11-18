
# 🔎 Content Recommendation Agent

An AI-powered content research agent that helps users explore topics by searching the web and presenting relevant content in an organized format.

The application retrieves web search results using the Serper API and displays content with summaries, relevance scores, and sentiment information through an interactive Streamlit interface.

## ✨ Features

- **Web Search:** Fetches relevant organic search results using the Serper API.
- **Content Exploration:** Allows users to research any topic through a simple search interface.
- **AI Integration:** Uses LangChain and OpenAI for language-model-based content analysis.
- **Content Summarization:** Includes functionality to generate concise summaries of search results.
- **Relevance Analysis:** Supports relevance scoring to help evaluate search results.
- **Sentiment Analysis:** Includes sentiment classification for analyzed content.
- **Interactive Interface:** Provides a clean and user-friendly Streamlit interface.
- **Source Access:** Displays links to the original web sources.

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Frontend | Streamlit |
| Backend Framework | FastAPI |
| Programming Language | Python |
| Web Search API | Serper API |
| AI Framework | LangChain |
| Language Model | OpenAI GPT-3.5 Turbo |
| Data Validation | Pydantic |

## ⚙️ How It Works

1. **User Input:** The user enters a topic they want to research.
2. **Web Search:** The application sends the topic to the Serper API.
3. **Result Extraction:** Relevant search results, titles, links, and snippets are retrieved.
4. **Content Analysis:** The project includes an AI-based summarization and ranking function using LangChain and OpenAI.
5. **Result Presentation:** Search results are displayed through Streamlit with source links and content information.

## 📁 Project Structure

```text
content-recommendation-agent/
│
├── ai_agent.py          # Search logic and AI integration
├── frontend.py          # Streamlit user interface
├── requirements.txt     # Project dependencies
├── .gitignore           # Git ignore configuration
│
└── .streamlit/
    └── secrets.toml     # API key configuration (create locally)
```

## 🚀 Getting Started

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/vharini24/content-recommendation-agent.git
```

### 2. Navigate to the Project Directory

```bash
cd content-recommendation-agent
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Keys

The application requires API keys for Serper and OpenAI.

Create a `.streamlit` folder in the project directory and add a file named `secrets.toml`.

Add your API keys:

```toml
SERPER_API_KEY = "your_serper_api_key"
OPENAI_API_KEY = "your_openai_api_key"
```

**Note:** Replace the placeholder values with your actual API keys. Never share or commit your API keys to GitHub.

### 5. Run the Application

Start the Streamlit application using:

```bash
python -m streamlit run frontend.py
```

The application will open in your browser.

## 🔑 API Requirements

- **Serper API:** Used to retrieve web search results.
- **OpenAI API:** Used for language-model integration and content analysis.

Make sure both API keys are configured before running the application.

## 🎯 Project Objective

The goal of this project is to simplify online content exploration by bringing web search and AI-assisted content analysis together in one application.

Instead of manually navigating through multiple search results, users can explore a topic through a single interface and access the original sources.

## 👩‍💻 Author

**Harini V**

GitHub: [@vharini24](https://github.com/vharini24)

---

⭐ If you find this project interesting, consider giving the repository a star!

