# AI Web Scraper

## Overview
This project is an AI-powered web scraper built using Python that runs locally on your machine. The application takes a URL as input, scrapes the website's DOM content, and uses a local large language model (LLM) to extract specific information based on a prompt provided by the user. By running the LLM locally, you can avoid the need to purchase tokens from external services.

The project handles large amounts of data by breaking it into manageable batches to avoid character limits, ensuring efficient and effective data processing. The technical implementation utilizes tools such as Selenium, BeautifulSoup, LangChain, and more.

## Demo
https://github.com/user-attachments/assets/66a4a4ac-841b-494d-bc45-f189b8840d0c


## Table of Contents
1. [Features](#features)
2. [Technology Stack](#Technology-Stack)
3. [Prerequisites](#Prerequisites)
4. [Setup and Installation](#Setup-and-Installation)
5. [Credits](#Credits)


## Features
- Input a URL to scrape
- AI-powered extraction of specific information from the scraped content
- Utilizes **LLaMA 3.1** for advanced AI capabilities
- Uses tools like Selenium and BeautifulSoup for web scraping


## Technology Stack
- **Python**: Writing the functionality and application code.
- **Streamlit**: Builds interactive web applications to showcase and interact with the scraper.
- **Selenium**: Automates web browser interaction to scrape dynamic web content.
- **BeautifulSoup**: Parses HTML and XML documents to extract data from web pages.
- **Langchain**: Integrates with language models to facilitate natural language processing tasks.
- **Ollama**: Provides access to the **LLaMA 3.1** model for advanced AI-powered data extraction.


## Prerequisites
Before installing and running the project, make sure you have the following:

- **Python** (version 3.10 or higher)
- **Google Chrome** (Latest available version)
- **A web driver** for Selenium (e.g., you can find the latest version of ChromeDriver for your device [here](https://googlechromelabs.github.io/chrome-for-testing/#stable))
- **Virtual environment** (`venv`)
- **Ollama** - You can find the download [here](https://ollama.com/download)
- **LLaMA 3.1** model for Ollama


## Setup and Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/k4n4v/AI-Web-Scraper.git
    ```

2. Navigate to the project folder:
    ```bash
    cd AI-Web-Scraper
    ```

3. Create a Python virtual environment:
    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:
    - On macOS/Linux:
    ```bash
    source venv/bin/activate
    ```
    - On windows:
    ```bash
    source venv/bin/activate
    ```

5.  Install project dependencies:
    ```bash
    pip install requirements.txt
    ```

6. Update and save `chrome_driver_path` in /scrape.py based on the location of your web driver.


## Usage

1. Active virtual environment

2. Run application:
    ```bash
    streamlit run main.py
    ```

3. Enter a website URL in the text input field and press "Scrape Site" button to scrape! 


## Credits
This project was inspired by various resources on AI and web scraping. Credit to the [Tech With Tim YouTube video](https://youtu.be/Oo8-nEuDBkk?si=bQZ3l6ODU6rn5Bzo) for providing insights and guidance.