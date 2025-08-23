## Web Search Task

This project contains a simple web crawler and search tool implemented in Python, located in `web-search-task-main/main.py`.

### main.py Overview

`main.py` provides the following features:

- **WebCrawler class**: Crawls web pages starting from a given URL, collects text content, and builds an index.
- **Search functionality**: Allows searching for a keyword in the crawled pages and returns URLs that do not contain the keyword.
- **Result printing**: Displays search results in a readable format.
- **Unit tests**: Includes tests for crawling, error handling, searching, and result printing using Python's `unittest` framework.

#### How to Use

1. Run the script to crawl a starting URL and search for a keyword:
	```bash
	python web-search-task-main/main.py
	```
2. The script will crawl `https://example.com` by default and search for the keyword `test`.
3. Unit tests are included and will run automatically when executing the script.

#### Requirements

- Python 3.x
- `requests` and `beautifulsoup4` libraries

Install dependencies with:
```bash
pip install requests beautifulsoup4
```