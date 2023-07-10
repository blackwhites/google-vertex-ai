# 🧭 Project Overview 

This project is centered around the innovative Google Vertex AI Palm2 platform. We have developed a research assistant for Google Scholar using a Streamlit application. The application is designed to take user search specifications and scour Google Scholar across multiple pages. The result is a comprehensive dataframe of all scraped papers and a selection of all downloadable PDF documents. The selected papers can then be downloaded and utilized in conjunction with Vertex AI and Langchain. 

## 🚧 Prerequisites

Before you get started with this project, you need to have the following:

- Python 3.6 or later
- Streamlit
- Google Vertex AI Access Credentials
- Langchain

## 🎛 Project Setup

To set up the project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies using pip install -r requirements.txt.
3. Run the Streamlit application using streamlit run app.py.

## 📦 Project Structure

The project is structured as follows:
```bash
├── credentials.py
├── main.py
├── pages/
│   ├── vertex_agent.py
│   ├── vertex_langchain.py
│   └── vertex_researcher.py
├── papers/
│   └── paper_name.pdf
├── participant-sa-xx-ghc-xxx.json
├── requirements.txt
├── README.md
└── searches/
    └── scholar_results_yyyy-mm-dd_hh-mm-ss.csv
````

## 🗄️ Data

The data used in this project is scraped from Google Scholar based on the user's search specifications. The resulting dataframe of papers and the PDF papers are stored locally, sorted by dates, and the papers are renamed with their title.

## 📚 References

- [Google Vertex AI](https://cloud.google.com/vertex-ai)
- [Langchain](https://python.langchain.com/docs/get_started/introduction.html)
- [Streamlit](https://streamlit.io/)

## 🏆 Conclusion

This project provides a powerful tool for researchers, enabling them to easily search for and download academic papers from Google Scholar. The integration with Google Vertex AI and Langchain further enhances its capabilities, allowing users to create a knowledge base from the downloaded papers and answer questions regarding the content.

## 🤝 Contributions

Contributions, issues, and feature requests are welcome! 
