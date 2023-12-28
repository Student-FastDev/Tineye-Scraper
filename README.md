# TinEye Image Search Bot

This Python script, utilizing Selenium, automates image searching on TinEye. It is designed to upload an image and scrape search results while optionally using proxies for anonymity.

## Table of Contents
- [Introduction](#introduction)
  - [Purpose](#purpose)
  - [Safety and Privacy](#safety-and-privacy)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
  - [Initial Setup](#initial-setup)
  - [Running the Script](#running-the-script)
- [Proxy Management](#proxy-management)
- [Troubleshooting](#troubleshooting)

## Introduction

### Purpose
The TinEye Image Search Bot automates the process of searching for images on TinEye. It's particularly useful for reverse image searches in bulk or automated scenarios.

### Safety and Privacy
The script offers an option to use proxies, enhancing privacy. Users should adhere to the terms of service of the websites they access.

## Prerequisites
Before installation, ensure you have the following:
- Python installed on your system.
- Google Chrome browser.
- Basic understanding of Python and command-line operations.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/YourUsername/TinEye-Image-Search-Bot
   ```
2. Navigate to the script directory:
   ```
   cd TinEye-Image-Search-Bot
   ```
3. Install required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

### Initial Setup
1. Prepare a list of proxies in `proxy.txt`, if using the proxy feature. Format each proxy as `ip:port:username:password`.

### Running the Script
1. Run the script via command line:
   ```bash
   python main.py
   ```
2. Enter the filename of the image you want to search when prompted.
3. The script will navigate to TinEye, upload the image, and display the search results.

## Proxy Management
If using proxies, the script will select one at random from `proxy.txt`. Make sure the proxies are valid and in the correct format.

## Troubleshooting
- Ensure all dependencies are installed.
- Check if Google Chrome is updated to the latest version.
- Verify the format of the proxies if used.

For any other issues, refer to the error messages provided by the script for guidance.
