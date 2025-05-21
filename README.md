# The Lead List 🗂️  
Multithreaded data aggregation tool for collecting business leads from public sources.
![Demo GIF](pic02.gif)
---

## ⚙️ Features
- Multithreaded data aggregation from public directories
- PostgreSQL integration for data persistence and deduplication
- Thread-safe database writes using locks
- HTML parsing and HTTP retry handling
- Prioritized scraping based on population ordering

---


## 🗃️ Database
Data is stored in a PostgreSQL database with unique ID checks to prevent duplicates.  
An additional carrier database is used to associate business phone numbers with carrier metadata.

---

## 🔒 Disclaimer
Certain files and logic have been intentionally omitted to protect proprietary material owned by W&M Leads LLC.  
This public version demonstrates the architecture and techniques used in the original production system.

---

## 🛠 Technologies Used
- Python 3
- BeautifulSoup
- Requests
- Threading & Concurrency
- PostgreSQL (via psycopg2)
