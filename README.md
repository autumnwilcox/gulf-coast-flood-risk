# Real-Time Prediction of Hurricane and Tidal Flood Risk in the Gulf Coast Using Big Data

This repository contains a Quarto-based research proposal developed for **IDC 6145 – Big Data Applications** at the **University of West Florida**. The project explores the use of **big data technologies** and **machine learning** to improve **real-time prediction of hurricane and tidal flood risk** along the U.S. Gulf Coast.

## Overview

The Gulf Coast faces recurring hurricane and tidal flood events that cause major disruption to communities, infrastructure, and ecosystems. Traditional prediction systems often rely on delayed or isolated data sources, limiting their ability to respond to changing conditions.

This project proposes scalable **big data framework** that integrates:

-   Live data from **NOAA**, **USGS**, and **satellite imagery**

-   **Real-time ingestion** using Apache Kafka

-   **Parallel analytics** using Apache Spark Streaming

-   **Machine learning models** for short-term flood forecasting

The goal is to enhance situational awareness, support early warning systems, and reduce disaster impacts through data-driven decision support.

## Project Structure

``` bash
gulf-coast-flood-risk/
├── paper.qmd            # Main Quarto document (proposal)
├── _quarto.yml          # Quarto project configuration
├── references.bib       # References for citations
├── data/                # Example data or sample datasets
├── scripts/             # Supporting R or Python scripts
├── figs/                # Output figures and visualizations
├── README.md            # Project documentation
└── .gitignore
```

## Setup

1.  Clone the repository

    ``` bash
    git clone https://github.com/<yourusername>/gulf-coast-flood-risk.git
    cd gulf-coast-flood-risk
    ```

2.  Open in RStudio (recommended)

    ``` bash
    quarto render
    ```

3.  Optional reproducibility

    ``` r
    install.packages("renv")
    renv::init()
    ```

## Technologies

-   **Quarto** - for writing and rendering the proposal

-   **RStudio** - development environment

-   **Apache Kafka** - real-time data ingestion

-   **Apache Spark Streaming** - distributed data processing

-   **Cloud storage** (e.g., AWS S3 or Google Cloud Storage) - scalable data handling

## Author

**Autumn S. Wilcox**

Graduate Student, Data Science: Analytics and Modeling

University of West Florida
