# Scholar-Connect

A platform to help students effortlessly find and apply for scholarships. Scholar-Connect aggregates opportunities and streamlines the application process, making scholarship search smarter, faster, and more accessible.

---

## Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [MongoDB Setup](#mongodb-setup)
- [Import Scraped Scholarship Data](#import-scraped-scholarship-data)
---

## About

**Scholar-Connect** (formerly ScholarSeek) is an open-source project designed to bridge the gap between deserving students and scholarship opportunities. By leveraging web scraping, data aggregation, and a user-friendly interface, our platform makes it easy for students to discover relevant scholarships and track their applications. This project was collaboratively developed by M. Abhiram, A. Eshanth Reddy, S. Rishikesh, and K. Raghavendra Reddy.

---

## Features

- 🔎 **Scholarship Finder:** Search and filter scholarships based on eligibility, deadlines, and more.
- 📋 **Aggregated Data:** Collects opportunities from multiple sources to provide a comprehensive list.
- 🛠️ **Backend API:** Powers the platform with fast, scalable data serving using JavaScript (Node.js).
- 📂 **Data Storage:** Maintains structured JSON data in MongoDB for efficient scholarship management.

---

## Tech Stack

- **Backend:** JavaScript (Node.js)
- **Web Scraping:** Python (Jupyter Notebook)
- **Frontend:** HTML, CSS, JavaScript
- **Database:** MongoDB
- **Data Format:** JSON

---

## Getting Started

### Prerequisites

- Node.js
- Python 3.x
- npm
- Jupyter Notebook (for web scraping scripts)
- MongoDB (Community Server)

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/Abhiram0703/Scholar-Connect.git
cd Scholar-Connect
```

2. **Backend Setup**

```bash
cd backend
npm install
npm start
```

3. **Frontend Setup**

Open a new terminal and run:

```bash
cd scholarship-finder
npm install
npm run dev
```

4. **Web Scraping**

- Navigate to the `webscrapping` folder.
- Open Jupyter Notebook.
- Run the web scraping scripts to fetch/update scholarship data.
- Data is stored in `Scholarseek.scholarships.json`.

---

## Folder Structure

```
Scholar-Connect/
│
├── backend/                    # Backend API code (Node.js)
│
├── webscrapping/               # Web scraping scripts (Jupyter Notebook/Python)
│
├── scholarship-finder/         # Frontend code (HTML, CSS, JavaScript)
│
├── Scholarseek.scholarships.json   # Aggregated scholarships data
│
├── README.md                   # Project documentation
└── .DS_Store                   # OS-generated file (safe to ignore)
```

---

## MongoDB Setup

Ensure MongoDB is installed and running on your system.

- Download from: [MongoDB Community Server](https://www.mongodb.com/try/download/community)
- Start the MongoDB server.

---

## Import Scraped Scholarship Data

1. Open **MongoDB Compass**.
2. Connect to: `mongodb://localhost:27017`.
3. Create a new database named: `Scholarseek`.
4. Create a new collection named: `scholarships`.
5. Click on **"Add Data"** → **"Import JSON"**.
6. Select the file: `Scholarseek.scholarships.json`.
7. Click **Import**.

---

## Contributing

Contributions are welcome! Please open issues and submit pull requests for improvements, bug fixes, or new features.

1. Fork the repo.
2. Create your feature branch (`git checkout -b feature/FeatureName`).
3. Commit your changes (`git commit -m 'Add some FeatureName'`).
4. Push to the branch (`git push origin feature/FeatureName`).
5. Open a pull request.



## Contact

  - [Abhiram](https://github.com/Abhiram0703)
  - [Rishikesh](https://github.com/Rishi-rky06)
  - [Eshanth Reddy](https://github.com/Eshanthreddy130705)

---
