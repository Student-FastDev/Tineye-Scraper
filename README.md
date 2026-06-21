# TinEye-Scraper

Automating reverse image searches on the TinEye website.

## Prerequisites

To run the script, ensure you have the following installed:

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

## Usage

1. **Run the Python Script:**

    Execute the script from the command line, specifying the image file you wish to search:

    ```bash
    python tineyes.py [image_file_name]
    ```

2. **Configure Settings:**

    If you wish to use proxies for enhanced anonymity, edit or create a `proxy.txt` file to include your proxies in the following format:

    ```plaintext
    IP:PORT:USER:PASS
    ```

    The script randomly selects a proxy from this file for each session, ensuring varied IP addresses for different scraping tasks.

## Notes

- **Proxy Configuration:** Utilize proxies to mask IP addresses and prevent IP bans. Configure proxies by adding them to a `proxy.txt` file in the format `IP:PORT:USER:PASS`, one per line. The script randomly selects a proxy for each session.
- **Compliance & Security:** Handle your proxy information securely to prevent unauthorized access. Ensure that your usage of the bot complies with TinEye's Terms of Service to avoid potential legal issues.

---

<div align="center">  
    <img src="https://www.maltego.com/images/uploads/tineye-logo.png" alt="Tineye Logo" width="50px">
</div>
