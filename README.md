# LeadLoom Business Email Extractor 

### Project Overview
LeadLoom Business Email Extractor is a high-performance Chrome Extension built to automate lead generation and eliminate manual data scraping. Instead of clicking through endless web pages, LeadLoom scans domain structures in real-time to extract valid business contact emails instantly.

It is lightweight, secure, and designed for marketers, sales teams, and developers who need clean data fast.

### Key Features

* **Smart Deep Scan Architecture:** Unlike basic scrapers that only read the current view, LeadLoom actively looks for high-probability sub-pages (e.g., /contact, /about-us, /team, /support) and crawls them asynchronously to catch deeply embedded emails.
* **Regex-Driven Filtering & Cleanup:** Equipped with automated sanitization rules that detect and filter out junk data, image paths masquerading as text, and dummy strings (like test@test.com), leaving you with genuine outreach leads.
* **Intelligent Self-Exclusion:** The script automatically detects and ignores your own active session email addresses during the extraction process, ensuring your target list remains 100% external.
* **Persistent Chrome Storage (Local-First):** Utilizes chrome.storage.local so your collected data is never lost on browser restarts, page refreshes, or sudden crashes. Your leads stay secure right on your machine.
* **Streamlined Export Hub:** Format-ready dataset extraction. Compile and download your entire filtered leads list into a clean, universally compatible .txt data stream with a single click.
* **Asynchronous Dashboard (Dark Mode UI):** A modern, high-contrast dark interface built with responsive HTML/CSS. Features live counter components that update in real-time as the extension scans active domains.

### Installation
* **1.Clone or Download:**<br>
Step 1. Download this repository as a ZIP file and extract it, or clone it directly to your local workspace using git.

* **2.Open Chrome Extensions:**<br>
Step 2. Launch Google Chrome and navigate to chrome://extensions/ by typing it into your URL address bar.

* **3.Toggle Developer Mode:** <br>
Step 3. Locate the Developer mode toggle switch in the top-right corner of the page and switch it ON.

* **4.Load Unpacked Manifest:**<br>
Step 4. Click the Load unpacked button in the top-left corner. Select the root folder of this project (the directory containing the manifest.json file).Once loaded, pin LeadLoom to your Chrome toolbar, navigate to any business website, and launch the dashboard to start scanning.

### Support & Consultation
* **Feedback:** If you find any bugs or have new ideas, feel free to open an issue in the repository.
* **Free Help:** I am available for any technical advice or help regarding this project **completely free of cost**.




