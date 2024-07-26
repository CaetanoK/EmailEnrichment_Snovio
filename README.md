# Email Profile Enrichment with Snov.io

This script automates the process of enriching email profiles by fetching additional information from the Snov.io API and saving the results to an Excel file.

## Overview

The script performs the following steps:

1. **Read Excel File:** Reads an input Excel file containing email addresses and other related data.
2. **Authentication:** Authenticates with the Snov.io API using provided client ID and client secret to obtain an access token.
3. **Fetch Profile Information:** For each email address in the Excel file, the script queries the Snov.io API to retrieve detailed profile information.
4. **Extract Relevant Data:** Extracts specific details such as LinkedIn profile links, first names, last names, and current job positions from the fetched profile data.
5. **Enrich Data:** Enriches the original data with the additional profile information.
6. **Save to Excel:** Saves the enriched data to a new Excel file.

## Requirements

- Python 3.x
- pandas
- requests

## Usage

1. Update the script with your Snov.io `client_id`, `client_secret`, and the path to your input Excel file.
2. Run the script.
3. The enriched data will be saved to a specified output Excel file.
