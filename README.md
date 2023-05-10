# Automated Email for Top News Stories on Hacker News

This is a Python script that extracts the top news stories from Hacker News and sends an automated email to the recipient(s) with the news stories listed in the email.

## Background

In today's fast-paced world, staying up-to-date with the latest news can be challenging. Many people rely on online news sources to keep them informed about current events. One such source is Hacker News, a social news website that focuses on computer science and entrepreneurship.

However, constantly checking for updates can be time-consuming. This Python script automates the process by extracting the top news stories from Hacker News and sending them directly to your email inbox.

## How it works

The script uses the Requests and BeautifulSoup4 libraries to extract the top news stories from the Hacker News website. It then formats the news stories into an email using the MIMEText and MIMEMultipart libraries. Finally, the script uses the smtplib library to send the email to the recipient(s).

## Getting Started

### Prerequisites

* Python 3.x
* Requests library
* BeautifulSoup4 library
* smtplib library

### Installing

* Clone this repository using `git clone https://github.com/<username>/<repository_name>.git`
* Install the required libraries using `pip install -r requirements.txt`

### Usage

* Update the following variables in the code:
  * `FROM` - your email id from which the email will be sent
  * `TO` - email id(s) of the recipient(s) separated by commas
  * `PASS` - your email id's password
* Run the script using `python hacker_news.py`
* Check your email inbox for the email with top news stories from Hacker News.



## Acknowledgments

* [Hacker News](https://news.ycombinator.com/)
* [Google](https://www.google.com/) - for providing low app access settings
* [Python](https://www.python.org/) - for providing the libraries to automate the email and web scraping process.
