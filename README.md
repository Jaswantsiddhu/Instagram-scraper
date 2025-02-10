# Instagram Image Scraper

This project is an **Instagram Image Scraper** built using **Selenium** and **Python**. It automates the process of logging into Instagram, searching for a keyword, scrolling through the results, extracting image URLs, and downloading images to a local directory.

## Features
- **Automated Instagram Login**: Logs into Instagram using Selenium.
- **Keyword-based Search**: Searches for any keyword provided by the user.
- **Scrolling Functionality**: Scrolls down to load more posts.
- **Image Extraction**: Extracts image URLs from Instagram search results.
- **Image Downloading**: Saves extracted images to a folder with the keyword name.

## Prerequisites
To run this project, you need:
- **Python 3.x** installed.
- **Google Chrome** installed.
- **Chromedriver** (Ensure it matches your Chrome version).
- Required Python libraries:
  ```sh
  pip install selenium wget
  ```

## Installation & Setup
1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-username/instagram-image-scraper.git
   cd instagram-image-scraper
   ```

2. **Update Credentials**:
   - Open the script and replace `USERNAME` and `PASSWORD` with your Instagram credentials.

3. **Run the Script in Jupyter Notebook**:
   ```sh
   jupyter notebook
   ```
   - Open the `.ipynb` file and run all cells.

## Usage
- The script logs into Instagram, searches for a keyword, scrolls through the page, extracts images, and downloads them into a folder named after the keyword.

## Notes
- **Use Responsibly**: Scraping Instagram is against its Terms of Service. Use this script for educational purposes only.
- **Two-Factor Authentication (2FA)**: If your Instagram account has 2FA enabled, you might need to enter the OTP manually.
- **Dynamic Class Names**: Instagram frequently updates its HTML structure, so some XPath or CSS selectors might need updating.

## License
This project is licensed under the MIT License.

---


