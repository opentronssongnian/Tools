# <span style="color: #0069ff;">📚 Opentrons Literature Summary Tool - User Guide</span>

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

## <span style="color: #0069ff;">Introduction</span>

The **Opentrons Literature Summary Tool** is a powerful literature review tool designed specifically for researchers, helping you efficiently organize, browse, and filter scientific literature. Through an intuitive web interface, you can:

- <span style="color: #0069ff;">🔄</span> Quickly import literature data
- <span style="color: #00c1d4;">🔍</span> Filter by year, research field, and more
- <span style="color: #00c1d4;">🔎</span> Full-text search to find specific content
- <span style="color: #00aa55;">📑</span> View detailed information for each paper
- <span style="color: #ffaa00;">⭐</span> Star important papers and export them
- <span style="color: #9900ff;">🎨</span> Customize the interface to optimize your reading experience

This tool is especially suited for literature review work involving large volumes of research papers, helping researchers save time and improve efficiency.

## <span style="color: #0069ff;">Excel File Preparation</span>

Before using this tool, you'll need to prepare an Excel file containing your literature data. The Excel file should include the following key fields:

| Field              | Description                       | Required                                                         |
| ------------------ | --------------------------------- | ---------------------------------------------------------------- |
| **Title**          | Paper title                       | <span style="color: #00aa55;">✅ Yes</span>                      |
| **Date**           | Publication date                  | <span style="color: #00aa55;">✅ Yes</span> (for year filtering) |
| **Authors**        | Author information                | <span style="color: #ffaa00;">Recommended</span>                 |
| **Category/Field** | Research areas or categories      | <span style="color: #ffaa00;">Recommended</span>                 |
| **Application**    | Application areas                 | Optional                                                         |
| **Summary**        | Paper abstract or content summary | <span style="color: #ffaa00;">Recommended</span>                 |
| **Paper link**     | Link to the original paper        | Optional                                                         |

You can also add other custom fields as needed, and all fields will be displayed on the details page.

## <span style="color: #0069ff;">Importing Excel Data</span>

Follow this step-by-step workflow to import your literature data into the tool:

| <span style="background-color: #f0f4ff; padding: 2px 5px;">Step</span> | <span style="background-color: #f0f4ff; padding: 2px 5px;">Action</span> | <span style="background-color: #f0f4ff; padding: 2px 5px;">Description</span> |
| :--------------------------------------------------------------------: | ------------------------------------------------------------------------ | ----------------------------------------------------------------------------- |
|                                   1️⃣                                   | **Open HTML File**                                                       | Open the `Publication Summary Tool_Final.html` file in your web browser       |
|                                   2️⃣                                   | **Locate Upload Section**                                                | Find the "Choose File" button at the top of the page                          |
|                                   3️⃣                                   | **Select Excel File**                                                    | Click and select your prepared Excel file (`.xlsx` or `.xls` format)          |
|                                   4️⃣                                   | **Import Data**                                                          | Click the "Load Excel File" button to start importing                         |
|                                   5️⃣                                   | **Wait for Processing**                                                  | The system will process your data (usually takes just seconds)                |
|                                   6️⃣                                   | **Success Confirmation**                                                 | You'll see: "Successfully loaded X publications"                              |

After importing data, the tool automatically extracts all year and category information and generates corresponding filter buttons for easy navigation.

## <span style="color: #0069ff;">Filtering and Searching</span>

### <span style="color: #00c1d4;">Filtering by Year</span>

To filter papers by publication year:

1. Find the year buttons list in the "Year" section
2. Click one or more years of interest (blue indicates selected) - <span style="color: #00aa55; font-weight: bold;">✓ Multi-selection is supported!</span>
3. The paper list will update in real-time to show only papers from the selected years
4. To clear year filters, click the "Reset Year Filter" button

The multi-selection capability allows you to compare research trends across different time periods simultaneously.

![Year Filtering Illustration](./year.png)

### <span style="color: #00c1d4;">Filtering by Research Category</span>

Similar to year filtering, you can filter papers by research area or category:

1. Find the category buttons in the "Category/Field" section
2. Click one or more research areas that interest you - <span style="color: #00aa55; font-weight: bold;">✓ Multi-selection is supported!</span>
3. The paper list will update to show only papers that include the selected categories
4. To clear category filters, click the "Reset Category Filter" button

Each category button has a unique color identifier, making it easy to distinguish different research areas. The multi-selection feature is particularly useful when you're interested in papers that span multiple research domains.

### <span style="color: #00c1d4;">Text Search Function</span>

To search for specific content across all papers:

1. Enter keywords or phrases in the search box
2. The system will search all fields in real-time (including titles, authors, abstracts, etc.)
3. Papers matching your search criteria will immediately appear in the list
4. Clear the search box to restore the display of all papers

You can combine text searching with year and category filtering to further narrow your search scope.

## <span style="color: #0069ff;">Viewing Paper Details</span>

### <span style="color: #00c1d4;">Detail Table Field Descriptions</span>

Click any paper title to open a detail modal window and view complete paper information:

| Field                                                             | Description                         | Display Features                                  |
| ----------------------------------------------------------------- | ----------------------------------- | ------------------------------------------------- |
| <span style="color: #0069ff;">Date</span>                         | Publication date                    | Always shown at the top of the details table      |
| <span style="color: #0069ff;">Title</span>                        | Complete paper title                | Shown in full                                     |
| <span style="color: #00c1d4;">Authors</span>                      | Complete author list                | Displayed in original format                      |
| <span style="color: #00c1d4;">Category/Field</span>               | Research areas                      | Displayed as colored tags for easy identification |
| <span style="color: #00aa55;">Application</span>                  | Application background              | Maintains original formatting                     |
| <span style="color: #00aa55;">Summary</span>                      | Paper content summary               | Preserves original formatted lists                |
| <span style="color: #ffaa00;">Additional Notes/Highlights</span>  | Key points or additional notes      | Preserves formatting                              |
| <span style="color: #ffaa00;">Paper link</span>                   | Direct link to original paper       | Clickable link                                    |
| <span style="color: #9900ff;">Customer info/lab page links</span> | Related lab or customer information | Clickable links                                   |

The system automatically recognizes URLs in text and converts them to clickable hyperlinks, making it easy to access related resources directly.

### <span style="color: #00c1d4;">Navigation Features</span>

In the detail modal window, you can use the navigation buttons at the bottom to browse through the filtered paper list:

- Click "<span style="color: #0069ff;">← Previous</span>" to view the previous paper
- Click "<span style="color: #0069ff;">Next →</span>" to view the next paper

This allows you to review multiple papers' detailed information without closing the detail page.

![Paper Detail Navigation](./paper.png)

## <span style="color: #0069ff;">Paper Starring Function</span>

### <span style="color: #ffaa00;">Starring Papers</span>

To mark and star important papers:

1. Click the star icon (<span style="color: #ffaa00;">⭐</span>) in the top right corner of the paper
2. When successfully starred, the paper card will be highlighted with a light yellow background
3. You can also double-click the paper card to toggle the star status

The starring feature helps you mark papers that deserve special attention among a large number of literature items for later review.

### <span style="color: #ffaa00;">Exporting Starred Papers</span>

To export information about all your starred papers:

1. Find the "<span style="color: #0069ff;">Download Starred Papers (TXT)</span>" button at the bottom of the page
2. Click this button, and the system will generate a text file containing detailed information about all starred papers
3. The file will automatically download to your computer with the filename `starred_papers.txt`

If you want to clear all star markers, you can click the "<span style="color: #0069ff;">Clear All Stars</span>" button.

## <span style="color: #0069ff;">Interface Customization</span>

### <span style="color: #9900ff;">View Mode Toggle</span>

<div style="background-color: #f8f9fa; padding: 10px; border-left: 4px solid #0069ff; margin-bottom: 15px;">
The tool offers two different view modes to suit different reading preferences:

1. <b>List View</b> (default): A compact list format, suitable for quickly browsing through large numbers of papers
2. <b>Card View</b>: Each paper is displayed as a card, providing a better visual experience
</div>

Find the view toggle switch in the top right corner of the page. The left icon (list) represents list view, and the right icon (grid) represents card view.

### <span style="color: #9900ff;">Light/Dark Theme Toggle</span>

<div style="background-color: #f8f9fa; padding: 10px; border-left: 4px solid #9900ff; margin-bottom: 15px;">
Based on your reading environment and personal preferences, you can choose between light or dark themes:

1. <b>Light Mode</b>: Light background, suitable for daytime use
2. <b>Dark Mode</b>: Dark background, reduces screen brightness, suitable for nighttime use
</div>

Find the theme toggle switch in the top right corner of the page. The left icon (sun) represents light mode, and the right icon (moon) represents dark mode.

### <span style="color: #9900ff;">Color Customization</span>

For further interface color personalization:

1. Click the palette icon in the bottom right corner of the page
2. In the customization panel that appears, you can adjust the following colors:
   - <span style="color: #0069ff;">Primary Color</span>: Main color (buttons, links, etc.)
   - <span style="color: #00c1d4;">Accent Color</span>: Emphasis color
   - <span style="color: #00aa55;">Background Start/End</span>: Background gradient colors
3. After adjusting, click "Apply Theme" to apply the changes
4. To restore default settings, click "Reset to Default" button

You can also toggle the particle background effect using the atom icon in the bottom right corner to enhance the visual experience.

## <span style="color: #0069ff;">Frequently Asked Questions</span>

<div style="background-color: #f0f4ff; padding: 15px; border-radius: 5px; margin-bottom: 15px;">
<p><b>Q: Why can't I import my Excel file correctly?</b><br>
A: Make sure your Excel file contains at least the "Title" and "Date" fields and is in .xlsx or .xls format. If there are date format issues, try saving in YYYY-MM-DD or MM/DD/YYYY format.</p>

<p><b>Q: How can I use multiple filtering conditions simultaneously?</b><br>
A: You can first select year filters, then category filters, and then enter keywords in the search box. The system will automatically combine these conditions and only display papers that meet all criteria.</p>

<p><b>Q: Is there a quick way to view filtered results?</b><br>
A: Yes, after applying filter conditions, the "Active Filters" area appears at the top of the page, listing all current effective filter conditions, and the bottom of the page shows "Showing X of Y results" information.</p>

<p><b>Q: How can I quickly locate specific sections in the details page?</b><br>
A: The details page defaults to placing the "Date" field at the top. You can scroll directly to find fields of interest. For longer detail pages, the system automatically scrolls to the top when loading.</p>

<p><b>Q: Does the export format preserve all formatting?</b><br>
A: The exported text file (.txt) contains all field data but in plain text format. If you need to preserve formatting, consider copying specific information directly from the detail view.</p>
</div>

---

<div style="text-align: center; color: #888; font-style: italic; margin-top: 30px;">
This guide was last updated: March 23, 2025
</div>
