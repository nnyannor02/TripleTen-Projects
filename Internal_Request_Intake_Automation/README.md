## Overview
This project automates the intake of internal requests by connecting Google Forms to Google Sheets using Zapier.
Each form submission automatically creates a new row in a centralized request log, eliminating manual data entry.

## Tools Used
- Google Forms
- Zapier
- Google Sheets

## Workflow
1. A user submits a request through a Google Form
2. Zapier detects a new form response
3. Zapier creates a new row in a Google Sheets request tracker with mapped fields

## Challenges & Debugging
While building this automation, several issues were encountered:

- Zapier cached outdated test data, causing runs to appear successful without inserting new rows
- Old sample records were reused until the trigger was refreshed and the Zap republished
- Manual field mapping was required to prevent empty row inserts when headers already existed

These issues were resolved by refreshing the trigger, re-testing with live form submissions, and explicitly mapping all fields.

## Outcome
- Fully automated intake process
- Reliable real-time data ingestion
- Scalable workflow suitable for internal operations and request tracking

## Demo
A short walkthrough video demonstrating the workflow and troubleshooting process is located in this file.
