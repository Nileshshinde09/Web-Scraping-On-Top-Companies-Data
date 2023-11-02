

# Web Scraping Project: Company Information from AmbitionBox
![maxresdefault](https://github.com/Nileshshinde09/Web-Scraping-On-Top-Companies-Data/assets/90444068/9cea2e10-6d7a-42db-95c2-9acfea7557e9)

This project is a web scraping script to collect company information from the AmbitionBox website. It extracts details such as company name, rating, type, number of employees, and more, for companies listed on the website. The scraped data is then stored in CSV and pickle formats.

## Prerequisites
```bash
pip install beautifulsoup4
pip install requests
pip install pandas
```

Before you can run this web scraping script, you need to install the required Python libraries. You can install them using the following commands:
## Getting Started

To get started with the web scraping script, follow these steps:

1. Clone this repository to your local machine:

    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:

    ```bash
    cd <repository-folder>
    ```

3. Open the Python script (`company_scraper.py`) in your code editor and ensure that you have updated the script as needed.

4. Run the script to start scraping company data:

    ```bash
    python company_scraper.py
    ```

## Usage

The script will start scraping company data from AmbitionBox and store it in CSV and pickle formats. You can modify the script to change the number of pages to scrape or add more data fields.

## Data Fields

The following fields are scraped for each company:

- **Name**: The name of the company.
- **Rating**: The rating of the company on AmbitionBox.
- **Company Type**: The type of the company (e.g., IT Services & Consulting).
- **Employees**: The number of employees working at the company.
- **Public or Private**: Whether the company is publicly traded or private.
- **Age of the Company**: The age of the company in years.
- **Headquarter Location**: The location of the company's headquarters.
- **Number of Branches**: The number of branches the company has.
- **Highly Rated For**: Aspects of the company highly rated by employees.
- **Critically Rated For**: Aspects of the company critically rated by employees.
- **Number of Reviews**: The number of reviews posted by employees.
- **Number of Salaries**: The number of salary reports.
- **Number of Interviews**: The number of interview experiences shared.
- **Number of Jobs**: The number of job openings at the company.
- **Number of Benefits**: The number of benefits reviews.
- **Logo URL**: The URL to the company's logo.

## Example Data

Here's an example of the scraped data for a company:

```python
{
  'Name': ['TCS'],
  'Rating': ['3.8'],
  'Company Type': ['IT Services & Consulting '],
  'Employees': [' 1 Lakh+ Employees '],
  'Public or Private': [' Public '],
  'Age of the Company': [' 55 years old '],
  'Headquarter Location': ['Mumbai'],
  'Number of Branches': [303],
  'Highly Rated For': ['Job Security, Work Life Balance, Company Culture'],
  'Critically Rated For': ['Promotions / Appraisal, Salary & Benefits'],
  'Number of Reviews': ['67k'],
  'Number of Salaries': ['737.1k'],
  'Number of Interviews': ['5.6k'],
  'Number of Jobs': ['278'],
  'Number of Benefits': ['11.3k'],
  'Logo URL': ['https://static.ambitionbox.com/alpha/company/photos/logos/tcs.jpg']
}
```

[companies_dataset.csv](https://github.com/Nileshshinde09/Web-Scraping-On-Top-Companies-Data/files/13236283/companies_dataset.csv)
