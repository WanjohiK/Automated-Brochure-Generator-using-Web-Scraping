# Automated-Brochure-Generator-using-Web-Scraping

## Overview

BronchureMaking is a Python-based project that automates the process of collecting information from the web and converting it into a professionally formatted brochure.

The notebook performs two main tasks:

1. Web Scraping – Extracts company or product information from target websites.

2. Brochure Generation – Uses the scraped content to automatically create a brochure (PDF, DOCX, or HTML) with structured sections such as company overview, services, and contact details.

This project demonstrates how data automation and AI can streamline marketing or content creation workflows.

## Key Features

🌐 Automated Web Scraping: Extracts key text, links, and metadata from company websites.

🧠 Content Cleaning & Structuring: Filters and organizes information into usable sections.

📰 Brochure Creation: Converts structured content into a ready-to-share brochure format.

🧩 Customizable Templates: You can modify the brochure design or add branding.

📄 Multi-format Output: Save the final brochure as PDF or DOCX.

## Project Workflow

        ┌────────────────────────┐
        │   Input Website URL    │
        └────────────┬───────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │  Web Scraping Layer │
          │ (BeautifulSoup, etc.)│
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ Data Processing &   │
          │ Text Structuring    │
          └──────────┬──────────┘
                     │
                     ▼
          ┌─────────────────────┐
          │ Brochure Generation │
          │ (ReportLab / DOCX)  │
          └─────────────────────┘

## Tech Stack

| Component               | Description                                |
| ----------------------- | ------------------------------------------ |
| **Language**            | Python 3.x                                 |
| **Web Scraping**        | BeautifulSoup, Requests                    |
| **Document Generation** | ReportLab / python-docx                    |
| **Data Handling**       | Pandas / re / json                         |
| **Notebook**            | Jupyter Notebook (`BronchureMaking.ipynb`) |


## Example Use Cases


<img width="578" height="404" alt="image" src="https://github.com/user-attachments/assets/5472f058-8d0a-494a-9260-89ba92dc0973" />





