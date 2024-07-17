# Article Summarizer and Query API

This project provides a Flask-based API to summarize or query articles from a given URL using a specified language model.

## Features

- Fetch and summarize articles from a URL.
- Query articles with specific questions.
- RESTful API endpoints for summarization and querying.
- Command-line interface for direct usage.

## Requirements

- Python 3.7+
- Flask
- Requests
- argparse
- llm_chat_api (custom module)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/yourrepository.git
    cd yourrepository
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

### Command-Line Interface

You can use the script directly from the command line to summarize or query an article.

#### Summarize an Article

```sh
python app.py --summarize --model <MODEL_NAME> <ARTICLE_URL>
