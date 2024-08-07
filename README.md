# Amazon Web Scraper
=====================

A Python script that uses Selenium and BeautifulSoup to scrape product information from Amazon.

## Table of Contents
-----------------

* [Features](#features)
* [Requirements](#requirements)
* [Installation](#installation)
* [Usage](#usage)
* [Configuration](#configuration)
* [Troubleshooting](#troubleshooting)
* [Disclaimer](#disclaimer)

## Features
--------

* Scrapes product information from Amazon, including:
	+ Product title
	+ Price
	+ Rating
	+ Image URL
	+ Description
* Handles pagination to scrape multiple pages of results
* Uses Selenium to render JavaScript-heavy pages
* Uses BeautifulSoup to parse HTML content

## Requirements
------------

* Python 3.6+
* Selenium
* BeautifulSoup
* Pandas
* ChromeDriver (for Selenium)

## Installation
------------

1. Install the required packages using pip:
```bash
pip install selenium beautifulsoup4 pandas
```
## Installation
------------

### Step 1: Download ChromeDriver

Download the ChromeDriver executable from the official [ChromeDriver website](https://chromedriver.chromium.org/downloads) and save it to a directory on your system.

### Step 2: Add ChromeDriver to System's PATH

Add the directory where you saved the ChromeDriver executable to your system's PATH environment variable.

### Usage
-----

### Run the Script

Run the script using Python:
```bash
python amazon_scraper.py
```