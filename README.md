# LangChain-Scraper
LangChain-Scraper is a sophisticated web scraping tool that integrates the power of modern language models to extract and process specific information from web pages. Using a combination of web scraping techniques and advanced language models, this project enables efficient extraction of structured data from unstructured web content.

# Web Scraper and Data Processor with LLM

## Overview

This project demonstrates how to:
1. **Scrape web content** from specified URLs.
2. **Extract and clean** the body content from HTML.
3. **Split the content** into manageable chunks.
4. **Use a Language Model (LLM)** to parse and extract specific information based on a given prompt.

The project utilizes the `requests` library for web scraping, `BeautifulSoup` for HTML processing, and `langchain_ollama` to interact with a Language Model (LLM).

## Project Structure
- `GenAI_web_scraper.ipynb`: Jupyter Notebook that demonstrates the usage of `SmartScraper` and LLM integration.
    - class `SmartScraper`: class for web scraping, content extraction,  cleaning and processing content with an LLM.

## Setup Instructions

### Prerequisites

Ensure you have the following installed:
- Python 3.7 or later
- [Ollama](https://ollama.com/) server running and accessible


### Installation

Clone the repository and install the required packages:

```bash
git clone https://github.com/yourusername/web-scraper-llm.git
cd web-scraper-llm
pip install -r requirements.txt ```



