# TinEye Image Search Bot

**TinEye Image Search Bot** is a Python script that leverages Selenium to automate image searches on [TinEye](https://tineye.com/). Designed for efficiency and anonymity, the bot uploads images, scrapes search results, and utilizes proxies to maintain privacy during bulk or automated reverse image search tasks.

## Features

- **Automated Image Upload:** Seamlessly upload images to TinEye for reverse image searching.
- **Result Scraping:** Extract and store search results for further analysis.
- **Proxy Support:** Utilize proxies to mask IP addresses and enhance anonymity.
- **Bulk Processing:** Handle multiple image searches efficiently in automated scenarios.
- **Image Management:** Automatically delete images after processing to maintain a clean workspace.

## Prerequisites

Before setting up the **TinEye Image Search Bot**, ensure you have the following installed:

- **Python:** Version 3.6 or higher.
- **Google Chrome:** Latest version recommended.
- **Git:** For cloning the repository.
- **Proxies:** A list of working proxies in the format `IP:PORT:USER:PASS` (optional for anonymity).

## Installation

1. **Clone the Repository:**

    ```sh
    git clone https://github.com/Student-FastDev/Tineye-Scraper
    cd Tineye-Scraper
    ```

2. **Install Required Packages:**

    Install the necessary Python packages using `pip`:

    ```sh
    pip install -r requirements.txt
    ```

3. **Set Up WebDriver:**

    Ensure that the Chrome WebDriver version matches your installed Google Chrome version. You can download the appropriate WebDriver from [here](https://sites.google.com/a/chromium.org/chromedriver/downloads).

    - **Add WebDriver to PATH:**
      
      Place the downloaded `chromedriver` executable in a directory that's included in your system's PATH, or specify its location in the script if necessary.

## Usage

### Running the Script

Execute the script from the command line, specifying the image file you wish to search:

```bash
python tineyes.py [image_file_name]
```

**Example:**

```bash
python tineyes.py sample_image.jpg
```

### Configuration

1. **Proxy Configuration:**

    If you wish to use proxies for enhanced anonymity, edit the `proxy.txt` file to include your proxies in the following format:

    ```plaintext
    IP:PORT:USER:PASS
    ```

    **Example:**

    ```plaintext
    192.168.1.100:8080:username:password
    203.0.113.50:3128:proxyuser:proxypass
    ```

    The script randomly selects a proxy from this file for each session, ensuring varied IP addresses for different scraping tasks.

2. **Image Management:**

    After processing, the script automatically deletes the image file to maintain a clean directory. Ensure that the image file you want to search is located in the same directory as the script or provide the correct path.

## Notes

- **Asynchronous Efficiency:** While the current version uses Selenium for automation, future updates may incorporate asynchronous programming to handle multiple searches concurrently, further enhancing efficiency.
  
- **Proxy Reliability:** Using high-quality and reliable proxies is crucial to prevent IP bans and ensure smooth operation.

- **Security:** Handle your proxy information securely to prevent unauthorized access.

- **Compliance:** Ensure that your usage of the bot complies with TinEye's [Terms of Service](https://tineye.com/legal) to avoid potential legal issues.

---

<div align="center">  
    <img src="https://www.maltego.com/images/uploads/tineye-logo.png" alt="Tineye Logo" width="50px">
</div>
