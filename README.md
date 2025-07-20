# Literature Search Toolkit

A Python toolkit with Jupyter notebooks for refining literature searches and exporting results from NCBI, Scopus, arXiv, and more via APIs. Streamlines systematic reviews and CSV creation for analysis.

## Overview

This repository provides Jupyter notebooks and utilities to help researchers:

- **Refine keyword search strategies** for systematic literature reviews.
- **Download and export search results** as CSV files from APIs such as PubMed, IEEE, Scopus, and arXiv.
- **Future plans:** Add support for more APIs and tools to generate PRISMA flowcharts.

## Getting Started

### Prerequisites

- **Python 3.10+**
- **Jupyter Notebook**
- **API keys** (obtain for databases requiring authentication, e.g., NCBI, Scopus, IEEE)
- **ASreview** (for screening CSVs after download)

#### Optional

- **Visual Studio Code** for local code editing and execution
- **Postman** for testing API queries

### Installation

#### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/literature-search-toolkit.git
cd literature-search-toolkit
```

#### 2. Set Up Environment Variables

A template file, `.env.example`, is provided in the repository's root directory.

**To configure your environment:**

- **Copy** `.env.example` to a new file named `.env`:
  ```bash
  cp .env.example .env
  ```
- **Edit** `.env` and fill in your personal API keys and adjust folder paths as appropriate for your machine.
  - Both Windows and Mac path examples are provided as comments in the file. Choose and edit the one for your operating system.

> **Note:** The `.env` file **must not** be committed to the repository (it is already excluded by `.gitignore`).  
> Each user should maintain their own `.env` locally for security and privacy.

#### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## Reminder for Users

> **Important:**  
> You must create and edit your own `.env` file based on `.env.example` before running any notebooks or scripts.  
> This ensures that your API keys and storage paths remain private.

