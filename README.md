# scrapy-motorcycle

# Setting up a Scrapy Environment

This guide will help you set up a Python environment and install Scrapy for web scraping.

## Prerequisites

Before you get started, ensure you have the following prerequisites installed on your system:

- [Python 3](https://www.python.org/downloads/)
- [pip](https://pip.pypa.io/en/stable/installing/)

## Step 1: Create a Virtual Environment (Optional)

It's recommended to create a virtual environment to isolate your Scrapy project from other Python packages. Run the following commands to create and activate a virtual environment:

```bash
# Create a virtual environment (replace 'scrapy_env' with your preferred name)
python3 -m venv scrapy_env

# Activate the virtual environment (Linux/macOS)
source scrapy_env/bin/activate

# Activate the virtual environment (Windows)
scrapy_env\Scripts\activate

# Install Scrapy
pip install scrapy

# Confirm Scrapy Installation
scrapy version

```

## Step 2: Create a Scrapy Project

```bash
# Create a Scrapy Project
scrapy startproject chocolatescraper

# Create a Spider
scrapy genspider chocolatespider chocolate.co.uk

```

## Step 3: Run a Spider

```bash
# Run a Spider
scrapy crawl chocolatespider -O mydata.json

```

