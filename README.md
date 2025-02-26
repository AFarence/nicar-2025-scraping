# Cutting-edge web scraping techniques

This one hour workshop will be presented at [NICAR 2025](https://www.ire.org/training/conferences/nicar-2025/) on Saturday March 8th from 11:30am to 12:30pm in Gray's Bay, 8th floor.

> Interested in new and effective advanced web scraping techniques? Join this session to learn about:
>
> - Video scraping: a new technique where you take a screen capture video and feed it into Google's Gemini models to turn it into structured data.
> - Using image models such as Gemini, GPT-4o and Claude 3.7 Sonnet are also extremely effective. It's possible to extract structured data from images, or poorly structured PDF files
> - Other modern scraping techniques using libraries like Playwright - a modern alternative to Selenium - for browser automation. Browser automation becomes a lot less complicated if you combine it with video or image analysis models.
>
> This session is good for: journalists with some web scraping experience. Attendees will need to bring their own laptop (no tablets).

## Tools and resources

This repository is **in development**. Expect it to change a whole lot prior to the workshop.

- [git-scraper-template](https://github.com/simonw/git-scraper-template) is a tool for quickly getting started with [Git scraping](https://simonwillison.net/2020/Oct/9/git-scraping/) - see [my blog](https://simonwillison.net/2025/Feb/26/git-scraper-template/) for details.
- [shot-scraper-template](https://github.com/simonw/shot-scraper-template) is a similar tool, described in [Instantly create a GitHub repository to take screenshots of a web page](https://simonwillison.net/2022/Mar/14/shot-scraper-template/). 

## Installation

Run these commands (ideally in a virtual environment created using your preferred mechanism):

```bash
pip install -r requirements.txt
shot-scraper install
```

I create my virtual environments like this:

```bash
python -m venv venv
source venv/bin/activate
```
