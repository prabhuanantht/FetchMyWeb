# FetchMyWeb

FetchMyWeb is an AI-powered web scraping tool that allows users to provide a website URL and a specific prompt to fetch exactly the data they need. Leveraging tools like Selenium, BeautifulSoup, and LangChain, this web scraper intelligently interacts with the website, scrapes dynamic content, and extracts relevant data based on user instructions.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- **AI-powered scraping**: Specify a prompt and FetchMyWeb scrapes exactly what you want from the site.
- **DOM parsing**: Scrapes the full DOM content from dynamic websites.
- **Handles complex websites**: Supports websites with CAPTCHAs, pop-ups, and IP blocking mechanisms.
- **Streamlined output**: Extracts data and formats it into clean CSV or JSON files.

## Installation

To set up **FetchMyWeb** on your local machine, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/YourUsername/FetchMyWeb.git
    cd FetchMyWeb
    ```

2. Create a virtual environment (optional):
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Install **ChromeDriver**:
    Download it from [here](https://googlechromelabs.github.io/chrome-for-testing/).

5. Set up the required API key for AI tools such as **LangChain** or **Ollama** in a .env file.

## Usage

### Quick Start

1. Run the tool using:
   ```bash
   python3 main.py
   ```

2. Provide the website URL and specify what data to scrape:
  - Enter a URL like: https://www.youtube.com
  - Specify your prompt: "Scrape the names of all videos, their like counts, creator name".

3. FetchMyWeb will scrape the site using AI, handle dynamic content, and deliver results in a clean format.

### Technologies Used

- **Python**: Core language for the tool.
- **Selenium**: For interacting with dynamic website
- **BeautifulSoup**: For parsing static HTML
- **LangChain**: For utilizing AI-driven prompts
- **Ollama**: A lightweight AI model for local language parsing
- **Streamlit**: (Optional) For building a UI to interact with the scraper


### Contributing

We welcome contributions! If you'd like to improve FetchMyWeb, feel free to:

- Fork this repository.
- Create your feature branch
```bash
git checkout -b feature/my-new-feature
```
- Commit your changes
```bash
git commit -m 'Add some feature'
```
- Push to the branch
```bash
git push origin feature/my-new-feature
```
- Create a new Pull Request.

### License

This project is licensed under the MIT License - see the LICENSE file for details.
