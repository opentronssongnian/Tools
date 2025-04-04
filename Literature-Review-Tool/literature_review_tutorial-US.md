# 📚 Opentrons Literature Summary Tool - User Guide

## Table of Contents

- [Introduction](#introduction)
- [Excel File Preparation](#excel-file-preparation)
- [Importing Excel Data](#importing-excel-data)
- [Filtering and Searching](#filtering-and-searching)
  - [Filtering by Year](#filtering-by-year)
  - [Filtering by Research Category](#filtering-by-research-category)
  - [Text Search Function](#text-search-function)
- [Viewing Paper Details](#viewing-paper-details)
  - [Detail Table Field Descriptions](#detail-table-field-descriptions)
  - [Navigation Features](#navigation-features)
- [Paper Starring Function](#paper-starring-function)
  - [Starring Papers](#starring-papers)
  - [Exporting Starred Papers](#exporting-starred-papers)
- [Interface Customization](#interface-customization)
  - [View Mode Toggle](#view-mode-toggle)
  - [Light/Dark Theme Toggle](#lightdark-theme-toggle)
  - [Color Customization](#color-customization)
- [Frequently Asked Questions](#frequently-asked-questions)

## Introduction

The **Opentrons Literature Summary Tool** is a powerful literature review tool designed specifically for researchers, helping you efficiently organize, browse, and filter scientific literature. Through an intuitive web interface, you can:

- 🔄 Quickly import literature data
- 🔍 Filter by year, research field, and more
- 🔎 Full-text search to find specific content
- 📑 View detailed information for each paper
- ⭐ Star important papers and export them
- 🎨 Customize the interface to optimize your reading experience

This tool is especially suited for literature review work involving large volumes of research papers, helping researchers save time and improve efficiency.

## Excel File Preparation

Before using this tool, you'll need to prepare an Excel file containing your literature data. The Excel file should include the following key fields:

| Field              | Description                       | Required                    |
| ------------------ | --------------------------------- | --------------------------- |
| **Title**          | Paper title                       | ✅ Yes                      |
| **Date**           | Publication date                  | ✅ Yes (for year filtering) |
| **Authors**        | Author information                | Recommended                 |
| **Category/Field** | Research areas or categories      | Recommended                 |
| **Application**    | Application areas                 | Optional                    |
| **Summary**        | Paper abstract or content summary | Recommended                 |
| **Paper link**     | Link to the original paper        | Optional                    |

You can also add other custom fields as needed, and all fields will be displayed on the details page.

## Importing Excel Data

Follow this step-by-step workflow to import your literature data into the tool:

| Step | Action                    | Description                                                          |
| :--: | ------------------------- | -------------------------------------------------------------------- |
|  1️⃣  | **Open HTML File**        | Open the `Untitled-1.html` file in your web browser                  |
|  2️⃣  | **Locate Upload Section** | Find the "Choose File" button at the top of the page                 |
|  3️⃣  | **Select Excel File**     | Click and select your prepared Excel file (`.xlsx` or `.xls` format) |
|  4️⃣  | **Import Data**           | Click the "Load Excel File" button to start importing                |
|  5️⃣  | **Wait for Processing**   | The system will process your data (usually takes just seconds)       |
|  6️⃣  | **Success Confirmation**  | You'll see: "Successfully loaded X publications"                     |

After importing data, the tool automatically extracts all year and category information and generates corresponding filter buttons for easy navigation.

## Filtering and Searching

### Filtering by Year

To filter papers by publication year:

1. Find the year buttons list in the "Year" section
2. Click one or more years of interest (blue indicates selected) - **✓ Multi-selection is supported!**
3. The paper list will update in real-time to show only papers from the selected years
4. To clear year filters, click the "Reset Year Filter" button

The multi-selection capability allows you to compare research trends across different time periods simultaneously.

![Year Filtering Illustration](./year.png)

### Filtering by Research Category

Similar to year filtering, you can filter papers by research area or category:

1. Find the category buttons in the "Category/Field" section
2. Click one or more research areas that interest you - **✓ Multi-selection is supported!**
3. The paper list will update to show only papers that include the selected categories
4. To clear category filters, click the "Reset Category Filter" button

Each category button has a unique color identifier, making it easy to distinguish different research areas. The multi-selection feature is particularly useful when you're interested in papers that span multiple research domains.

### Text Search Function

To search for specific content across all papers:

1. Enter keywords or phrases in the search box
2. The system will search all fields in real-time (including titles, authors, abstracts, etc.)
3. Papers matching your search criteria will immediately appear in the list
4. Clear the search box to restore the display of all papers

You can combine text searching with year and category filtering to further narrow your search scope.

## Viewing Paper Details

### Detail Table Field Descriptions

Click any paper title to open a detail modal window and view complete paper information:

| Field                        | Description                         | Display Features                                  |
| ---------------------------- | ----------------------------------- | ------------------------------------------------- |
| Date                         | Publication date                    | Always shown at the top of the details table      |
| Title                        | Complete paper title                | Shown in full                                     |
| Authors                      | Complete author list                | Displayed in original format                      |
| Category/Field               | Research areas                      | Displayed as colored tags for easy identification |
| Application                  | Application background              | Maintains original formatting                     |
| Summary                      | Paper content summary               | Preserves original formatted lists                |
| Additional Notes/Highlights  | Key points or additional notes      | Preserves formatting                              |
| Paper link                   | Direct link to original paper       | Clickable link                                    |
| Customer info/lab page links | Related lab or customer information | Clickable links                                   |

The system automatically recognizes URLs in text and converts them to clickable hyperlinks, making it easy to access related resources directly.

### Navigation Features

In the detail modal window, you can use the navigation buttons at the bottom to browse through the filtered paper list:

- Click "← Previous" to view the previous paper
- Click "Next →" to view the next paper

This allows you to review multiple papers' detailed information without closing the detail page.

![Paper Detail Navigation](./paper.png)

## Paper Starring Function

### Starring Papers

To mark and star important papers:

1. Click the star icon (⭐) in the top right corner of the paper
2. When successfully starred, the paper card will be highlighted with a light yellow background
3. You can also double-click the paper card to toggle the star status

The starring feature helps you mark papers that deserve special attention among a large number of literature items for later review.

### Exporting Starred Papers

To export information about all your starred papers:

1. Find the "Download Starred Papers (TXT)" button at the bottom of the page
2. Click this button, and the system will generate a text file containing detailed information about all starred papers
3. The file will automatically download to your computer with the filename `starred_papers.txt`

If you want to clear all star markers, you can click the "Clear All Stars" button.

## Interface Customization

### View Mode Toggle

The tool offers two different view modes to suit different reading preferences:

1. **List View** (default): A compact list format, suitable for quickly browsing through large numbers of papers
2. **Card View**: Each paper is displayed as a card, providing a better visual experience

Find the view toggle switch in the top right corner of the page. The left icon (list) represents list view, and the right icon (grid) represents card view.

### Light/Dark Theme Toggle

Based on your reading environment and personal preferences, you can choose between light or dark themes:

1. **Light Mode**: Light background, suitable for daytime use
2. **Dark Mode**: Dark background, reduces screen brightness, suitable for nighttime use

Find the theme toggle switch in the top right corner of the page. The left icon (sun) represents light mode, and the right icon (moon) represents dark mode.

### Color Customization

For further interface color personalization:

1. Click the palette icon in the bottom right corner of the page
2. In the customization panel that appears, you can adjust the following colors:
   - Primary Color: Main color (buttons, links, etc.)
   - Accent Color: Emphasis color
   - Background Start/End: Background gradient colors
3. After adjusting, click "Apply Theme" to apply the changes
4. To restore default settings, click the "Reset to Default" button

You can also toggle the particle background effect using the atom icon in the bottom right corner to enhance the visual experience.

## Frequently Asked Questions

**Q: Why can't I import my Excel file correctly?**  
A: Make sure your Excel file contains at least the "Title" and "Date" fields and is in .xlsx or .xls format. If there are date format issues, try saving in YYYY-MM-DD or MM/DD/YYYY format.

**Q: How can I use multiple filtering conditions simultaneously?**  
A: You can first select year filters, then category filters, and then enter keywords in the search box. The system will automatically combine these conditions and only display papers that meet all criteria.

**Q: Is there a quick way to view filtered results?**  
A: Yes, after applying filter conditions, the "Active Filters" area appears at the top of the page, listing all current effective filter conditions, and the bottom of the page shows "Showing X of Y results" information.

**Q: How can I quickly locate specific sections in the details page?**  
A: The details page defaults to placing the "Date" field at the top. You can scroll directly to find fields of interest. For longer detail pages, the system automatically scrolls to the top when loading.

---

_This guide was last updated: March 23, 2025_
