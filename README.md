# Factiva News Downloader

This project provides a streamlined approach for downloading and managing news articles from Factiva using automated web scraping powered by Selenium and Python.

## 🚀 Features

- **Automated News Search**: Generate a comprehensive set of news article links based on custom search criteria.
- **Automated Article Downloading**: Fetch and save news articles efficiently.
- **Data Management**: Organize results neatly into Excel or CSV files for further analysis.

## 📁 Project Structure

```
factiva_download/
├── data/
│   ├── news_output.xlsx
│   ├── search_results_with_duplicates.xlsx
│   ├── search_results_with_urls.xlsx
│   └── search_term.xlsx
└── factiva_download.ipynb
```

## ⚙️ How to Use

### 🔧 Step 1: Setup your search terms
- Modify `search_term.xlsx` to include your desired keywords and date ranges.

### 🌐 Step 2: Generate News Links
- In `factiva_download.ipynb`, replace the placeholder URL with your Factiva shared article link to automatically generate links for articles.

### 📥 Step 3: Download and Save Articles
- Run the corresponding cells in the notebook to automate login and download news articles as Excel/CSV.

## 🛠️ Installation & Dependencies

Install required Python libraries:
```bash
pip install pandas selenium openpyxl
```

- **Selenium WebDriver**: Ensure you have installed the appropriate WebDriver (e.g., ChromeDriver) matching your browser.

## 📝 Prerequisites

- A valid Factiva account with permissions to access news articles.
- Google Chrome browser (recommended) and corresponding ChromeDriver.

## 🤖 Libraries Used
- **pandas**: Data processing and Excel file handling.
- **selenium**: Automated browser actions and web scraping.
- **openpyxl**: Excel file manipulation.

## ⚠️ Disclaimer

Please comply with Factiva’s Terms of Service. Use responsibly for research and educational purposes only.

## 🤝 Contribution
Feel free to submit:
- Bug reports and feature requests.
- Pull requests for improvements.

## 📜 License
This project is licensed under the MIT License.

## 📧 Contact
- **Your Name:** your.email@example.com

Happy data scraping! 🚀📑

