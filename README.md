# Google Apps Script Documentation

## Overview

This Google Apps Script automates the process of updating a README.md file in a GitHub repository with data retrieved from a Google Spreadsheet. It retrieves data from the spreadsheet, formats it into Markdown format, and updates the README.md file on GitHub using the GitHub API.

## Functions

### `updateReadme()`

- **Description**: This function is the main entry point for the script. It orchestrates the process by retrieving data from the spreadsheet, generating Markdown content, and updating the README.md file on GitHub.

### `generateMarkdownTable(data)`

- **Description**: This function takes the data retrieved from the spreadsheet and formats it into Markdown format for a table.

- **Parameters**:
  - `data`: 2D array containing the data retrieved from the spreadsheet.

- **Returns**:
  - A string containing the Markdown-formatted table.

### `updateReadmeOnGithub(token, repoOwner, repoName, content)`

- **Description**: This function updates the README.md file in the specified GitHub repository with the provided content.

- **Parameters**:
  - `token`: GitHub personal access token for authentication.
  - `repoOwner`: Owner of the GitHub repository.
  - `repoName`: Name of the GitHub repository.
  - `content`: Content to be written to the README.md file.

## Usage

1. **Set up Google Apps Script**:
   - Open your Google Spreadsheet.
   - Go to `Extensions` > `Apps Script` to open the Google Apps Script editor.
   - Copy and paste the provided code into the script editor.

2. **Configure Variables**:
   - Replace placeholder values (`YOUR_SPREADSHEET_ID`, `YOUR_GITHUB_TOKEN`, etc.) with your actual values.
   - Ensure that the correct sheet name and range are specified in the `rangeName` variable.

3. **Run the Script**:
   - Run the `updateReadme` function from the Google Apps Script editor.
   - Verify that the script executes successfully without errors.

4. **Schedule the Script** (Optional):
   - Set up a trigger to schedule the script to run at specific intervals.
   - Go to `Edit` > `Current project's triggers` in the Google Apps Script editor to create a new trigger.

## Dependencies

- This script relies on the Google Sheets API and the GitHub API for retrieving data from the spreadsheet and updating the README.md file, respectively.
- Ensure that the necessary scopes and permissions are granted for accessing the Google Sheets API and the GitHub API.

## Notes

- Keep your GitHub personal access token secure and avoid sharing it publicly.
- Test the script thoroughly before deploying it to production to ensure it behaves as expected.

## Sample

| Company Name                        | Role                                             |
|------------------------------------|--------------------------------------------------|
| Company Name | Roles |
| Amazon | SDE Intern |
| Goldman Sachs | Summer Analyst |
| PayPal | Software Engineer - 2024 Summer Intern |
| IBM | Research Intern-Quantum |
| IBM | Research Intern-Hybrid Cloud |
| IBM | Research Intern-Security |
| Baker Hughes | Summer Internships 2024 |
| GE Careers | Research intern |
| Barclays | Technology Summer Intern Programme 2024 EG |
| MasterCard | BizOps Engineer I (R-205850) |
| HP | Software Engineer(Systems) Intern (1160551) |
| Mercedes Benz | Intern - ITP/ID Team Software development platform AWS-MER0002ADA |
| Seagate | Intern III- Python Automation (8816)  |
| Seagate | Intern III- Python Automation (8834) |
| Seagate | V- HR Business Partners and Site Support (8788) |
| Sophos | Intern (Software Testing) |
| Unacademy | Hiring Intern (WFO) |
| Matrice.ai | System Engineering Intern |
| Upstox | UI Intern (2023 - 2024) |
| Scalar | SDE Intern |
| AdaGrad | DevOps Engineer - Intern |
| Intel | Student Intern Technical |
| HP | Intenral Audit Intern |
| Comprinno Technologies Pvt. Ltd. | DevOps Engineer |
| IBM | Intern Software Engineer |
| Intel | Student Intern  |
| Walmart | Grad Intern |
| Xiaomi | Performance Intern |
| Baker Hughes | Early Career Trainee - DT |
| Siemens Healhineers | Technical - Intern |
| ZF Jobs | Graduate Engineer Trainee- B.Tech/ B.E - Data Science/ IT/ CS |
| Intuit | University Hiring |
| SalesForce | Infrastructure Engineer, Site Reliability Intern |
| Seagate | Intern- Machine Learning (Gen AI) (9366) |
| Seagate | Intern - Big Data (9560)  |
| Delottie | USI-CampusFY25-R&FA-Analyst Trainee-OTN |
| Intel | JR0255021 - Graduate Technical Intern |
