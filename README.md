# TinEye Image Search Bot

This Python script, utilizing Selenium, automates image searching on TinEye. It is designed to upload an image and scrape search results while using proxies for anonymity.

## Table of Contents
- [Introduction](#introduction)
  - [Purpose](#purpose)
  - [Safety and Privacy](#safety-and-privacy)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
  - [Running the Script](#running-the-script)
  - [Configuration](#configuration)
- [Troubleshooting](#troubleshooting)

## Introduction

### Purpose
The TinEye Image Search Bot automates the process of searching for images on TinEye. It's particularly useful for reverse image searches in bulk or automated scenarios.

### Safety and Privacy
The script uses proxies, enhancing privacy. Users should adhere to the terms of service of the websites they access.

## Prerequisites
Before installation, ensure you have the following:
- Python
- Google Chrome
- Git

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/Student-FastDev/Tineye-Scraper
   ```
2. Navigate to the script directory:
   ```
   cd Tineye-Scraper
   ```
3. Install required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

### Running the Script

Execute the script from the command line:

   ```
   python tineyes.py [name of the image file in the same directory]
   ```

### Configuration

After the first run, edit `proxy.txt`:

   ```
   IP:PORT:USER:PASS
   ```

The script randomly selects a proxy from this file for each session, ensuring varied IP addresses for different scraping tasks.
After the finish of the program, the image file is deleted.

## Troubleshooting
- Ensure all dependencies are installed.
- Check if Google Chrome is updated to the latest version.
- Verify the format of the proxies if used.

For any other issues, refer to the error messages provided by the script for guidance.
