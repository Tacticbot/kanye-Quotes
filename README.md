# Kanye Says...

This Python application uses the Kanye.rest API to fetch random Kanye West quotes and display them in a graphical user interface.

## Overview

Kanye Says is a fun project that retrieves random quotes from the [Kanye.rest API](https://kanye.rest/) and presents them in a graphical window using Python and Tkinter library.

## How It Works

1. **Dependencies**: The application relies on the `requests` library to make API calls.
2. **Interface**: The GUI includes a window displaying a background image with a section dedicated to presenting the quote. Additionally, there's a button with Kanye West's image, triggering the quote-fetching process.
3. **Fetching Quotes**: Clicking the Kanye image button sends a request to the Kanye.rest API, retrieves a random quote, and updates the display area with the fetched quote.

## Installation

### Clone the Repository

```bash
git clone https://github.com/Tacticbot/kanye-Quotes.git
cd kanye-Quotes
```

### Install Dependencies

```bash
pip install requests
```

### Usage

#### Run the application

```bash
python main.py
```
Click the Kanye Image to fetch a new quote


