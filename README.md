# Google Maps Easy Scrape

A Chrome extension that makes it easy to scrape Google Maps search results and export them to CSV format.

## Project Overview

Google Maps Easy Scrape is a powerful Chrome extension designed to automatically collect business data from Google Maps search results. The extension automates the process of scrolling through search results and gathering information like business names, ratings, reviews, phone numbers, websites, and Google Maps links.

## Features

- **Auto-scrolling**: Automatically scrolls through Google Maps search results to collect all available data
- **Data Collection**: Extracts comprehensive business information including:
  - Business title/name
  - Rating
  - Number of reviews
  - Phone number
  - Website URL
  - Direct Google Maps link
- **CSV Export**: Export collected data to CSV format with one click
- **Configurable Filename**: Customize the filename for your exported CSV files
- **Real-time Display**: View collected data in a clean, organized table format
- **Smart Detection**: Automatically detects when you're on a Google Maps search page

## Installation Instructions

Follow these steps to install the Google Maps Easy Scrape extension in Chrome:

### Step 1: Download or Clone the Repository
- **Option A**: Download the repository as a ZIP file and extract it to your desired location
- **Option B**: Clone the repository using Git:
  ```bash
  git clone <repository-url>
  ```

### Step 2: Open Chrome Extensions Page
- Open Google Chrome
- Navigate to `chrome://extensions/` in the address bar
- Alternatively, go to Chrome menu (three dots) → More tools → Extensions

### Step 3: Enable Developer Mode
- In the top right corner of the Extensions page, toggle on **"Developer mode"**
- This will reveal additional options for developers

### Step 4: Load the Extension
- Click the **"Load unpacked"** button that appears in the top left
- A file selection dialog will open
- Navigate to and select the extension directory (the folder containing manifest.json)
- Click "Select Folder"

### Step 5: Verify Installation
- The Google Maps Easy Scrape extension should now appear in your extensions list
- The extension icon (🗺️) should appear in your Chrome toolbar
- If you don't see the icon, click the puzzle piece icon in the toolbar and pin the extension

## How to Use

1. **Navigate to Google Maps**: Go to [Google Maps](https://www.google.com/maps/) and perform a search for businesses or places
2. **Open the Extension**: Click the Google Maps Easy Scrape icon in your Chrome toolbar
3. **Start Scraping**: Click the "Scrape Google Maps" button
4. **Wait for Collection**: The extension will automatically scroll through the results and collect data
5. **Review Results**: View the collected data in the table that appears
6. **Export Data**: 
   - Enter a custom filename (optional) in the input field
   - Click "Download as CSV" to save the data to your computer

## Technical Details

This extension is built using modern web technologies:

- **Manifest V3**: The latest Chrome extension manifest version for improved security and performance
- **HTML**: Semantic markup for the popup interface
- **Inline CSS**: Embedded styling for a clean, responsive user interface
- **Vanilla JavaScript**: Pure JavaScript without external dependencies for fast performance
- **Chrome Extensions API**: Uses the `chrome.scripting` and `chrome.tabs` APIs for content injection and tab management

## Export Feature

The CSV export functionality allows you to:

- **Custom Filenames**: Enter your desired filename before downloading (defaults to a timestamp if no name is provided)
- **Complete Data**: Export all collected business information in a structured CSV format
- **Immediate Download**: Files are downloaded directly to your default downloads folder
- **Spreadsheet Compatible**: The exported CSV files can be opened in Excel, Google Sheets, or any spreadsheet application

The CSV export includes all the following columns:
- Title
- Rating
- Reviews
- Phone
- Website
- Google Maps Link

## Requirements

- Google Chrome browser (version 88 or higher for Manifest V3 support)
- Access to Google Maps search results

## Troubleshooting

- **Extension not working**: Ensure you're on a Google Maps search page (URL should contain `google.com/maps/search`)
- **No data collected**: Make sure there are search results visible on the page before starting
- **Download not working**: Check that your browser allows downloads and that no popup blockers are interfering

---

Created by [Mike Powers](https://www.youtube.com/@itsmikepowers) | [Support the developer](https://www.buymeacoffee.com/itsmikepowers)
