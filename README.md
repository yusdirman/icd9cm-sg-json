# ICD-9-CM Procedure Search System

A lightweight, lightning-fast static web application for searching, viewing, and copying ICD-9-CM procedure codes. This tool is built entirely with HTML, CSS, and Vanilla JavaScript, requiring zero backend server to run.

## IMPORTANT!

The json data was extracted from the PDF decoumentation and generated using AI, but no human verification has been done. 
If you need to use this coding tools for ICD9CM procedures, please create a pull request to verify the json file against the pdf file.

Thank you.


## Features

* 🔍 **Fuzzy Searching:** Powered by [Fuse.js](https://fusejs.io/), the search bar tolerates typos and minor misspellings (e.g., searching "lapro" will still find "laparoscopic").

* ⚡ **Real-Time & Debounced:** Search results update instantly as you type, with built-in debouncing to ensure smooth performance even on older devices.

* 📖 **Detailed Context:** Click on any procedure code to instantly view its full title, inclusion terms, exclusion terms, and special coding notes.

* 📋 **One-Click Copy:** Easily copy the selected ICD-9 code directly to your system clipboard for use in other applications.

* 🚀 **Zero-Backend:** Runs 100% in the browser. No databases or Node.js servers to maintain.

## Tech Stack

* **HTML5 & CSS3** (Responsive design, custom UI)

* **Vanilla JavaScript** (ES6+)

* **Fuse.js** (Client-side fuzzy search)

* **JSON** (Data storage)

## File Structure

```text
├── index.html               # Main application interface and logic
├── icd9cm_procedures.json   # The raw dataset containing all ICD-9-CM codes
├── icd9cm_chapters.json     # The raw dataset containing all ICD-9-CM chapters 
├── icd9cm.pdf               # The source document for this project
└── README.md                # Project documentation
```

## Screen Shot
<img width="1413" height="789" alt="Screenshot from 2026-04-27 13-40-26" src="https://github.com/user-attachments/assets/5a2fde3e-da04-4261-ac84-c09a0d2258bc" />
