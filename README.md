# salary-discussion-analytics
An end-to-end data engineering project leveraging Snowflake, dbt, Terraform, Rivery, and Looker to analyze and visualize salary discussions from r/dataengineering  on Reddit.

## Overview

This project aims to provide insights into salary discussions within a specified subreddit on Reddit. The data is scraped, processed, and analyzed, with the results presented through interactive dashboards using Looker.

## Table of Contents

- [Features](#features)
- [Setup](#setup)
- [Data Pipeline](#data-pipeline)
- [Visualizations](#visualizations)
- [How to Contribute](#how-to-contribute)
- [Acknowledgements](#acknowledgements)

## Features

- **Web Scraping:** Utilizes Rivery to scrape salary discussions from a specified subreddit.
- **Data Transformation:** dbt is used to transform raw data into a structured analytics layer stored in Snowflake.
- **Infrastructure as Code (IaC):** Terraform scripts define and manage the necessary infrastructure, ensuring reproducibility.
- **Data Visualization:** Looker is employed to create interactive dashboards, providing insights into average compensation, regional variations, and more.

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/salary-discussion-analytics.git
   ```
