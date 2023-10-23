# TimeSeriesShiny (In Progress)
This project is a part of the Fetch Machine Learning Take-Home Test. It features an ML model that combines ARIMA and XGBoost, and an RShiny App for running inference. The RShiny app is packaged in a Docker container, making it easy to build and run locally via Docker Hub.

## Overview

### Problem Statement
In this project, I tackled a critical business challenge at Fetch, focusing on monitoring the daily number of scanned receipts, a key performance indicator (KPI) for the company.  With an eye on predictive analytics, I aimed to forecast the number of scanned receipts for future months, providing valuable insights for planning and decision-making.

### Solution:

To address this business challenge, I devised a comprehensive solution:
1. **Data Source and Preparation:** I began by collecting and preparing historical data. The dataset contained the daily counts of scanned receipts throughout the year 2021, serving as a valuable source of information.

2. **Machine Learning Models:** I developed a predictive algorithm that blends two robust machine learning models, ARIMA (AutoRegressive Integrated Moving Average) and XGBoost. These models were fine-tuned to effectively forecast the monthly counts for the year 2022.

3. **RShiny Web Application:** To facilitate user-friendly access to the predictive capabilities, I built an interactive RShiny web application. This application enables users to run inference procedures and obtain predictions for the scanned receipt counts.

4. **Docker Containerization:** For ease of deployment and utilization, I packaged the RShiny app within a Docker container. This approach simplifies the process of building and running the application locally, utilizing Docker Hub.

By combining these elements, I created a robust solution that not only predicts future scanned receipt counts but also streamlines the prediction process for users, ensuring that Fetch can make data-driven decisions with confidence.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

List the main features of your project. What can users do with it?

## Prerequisites

Specify any prerequisites that users need to have installed or configured before using your project. This could include software, libraries, or dependencies.

## Installation

Provide step-by-step instructions for installing your project. Include any command-line instructions, configuration steps, or setup that might be needed.

## Usage

Explain how to use your project. Provide code examples, screenshots, or any other relevant information to help users understand how to make the most of your project.

## Contributing

If you want to encourage contributions from other developers, provide guidelines on how to contribute to your project. This could include information on how to report issues, how to propose new features, or how to submit code changes.

## License

Specify the project's license and provide a link to the full text of the license if necessary.

## Acknowledgments

You can give credit to individuals, projects, or resources that have been helpful in the development of your project.

## Contact

Provide contact information for users to reach out for questions, issues, or further assistance.

---

**Note**: Feel free to modify or expand on these sections as needed to provide comprehensive documentation for your specific project.
