# NewsAPI Sentiment Analyzer

## Overview
The **NewsAPI Sentiment Analyzer** is a Python-based application that fetches news articles from the [NewsAPI](https://newsapi.org/) and analyzes their sentiment using Natural Language Processing (NLP) techniques. The tool helps users gauge the general sentiment of news articles related to specific topics, sources, or keywords.

## Features
- Fetches real-time news articles using NewsAPI.
- Performs sentiment analysis using a pre-trained NLP model.
- Categorizes sentiment into Positive, Neutral, and Negative.
- Provides a summary visualization of sentiment distribution.



### Setup Instructions

1. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
2. Obtain an API key from [NewsAPI](https://newsapi.org/) and add it to a `.env` file:
   ```sh
   NEWSAPI_KEY=your_api_key_here
   ```

## Usage
Run the script to fetch news articles and analyze their sentiment:
```sh
python main.py --query "technology" --language "en"
```
Options:
- `--query` : Keyword or topic to search for.
- `--language` : Language of the news articles (default: `en`).

## Output
- **Sentiment Summary**: Displays the number of positive, neutral, and negative articles.
- **Visualization**: A bar chart or pie chart summarizing sentiment distribution.
- **Detailed Report**: Sentiment scores and summaries for individual articles.

## Technologies Used
- **Python**
- **NewsAPI** for fetching news articles
- **Hugging Face Transformers** / **NLTK** / **VADER** for sentiment analysis
- **Streamlit** (optional) for interactive web-based analysis

## Future Enhancements
- Implement a web-based interface for better usability.
- Integrate multiple sentiment analysis models for comparison.
- Add multilingual support.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## Author
**Upasna Agrawal** -

