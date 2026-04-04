# ingest-flatfiles-adls-adf

## Project Overview

This project demonstrates ingestion of flat files such as CSV and JSON using Azure Data Factory into ADLS Gen2 (raw layer).

## Architecture

Flat Files → Azure Data Factory → ADLS Gen2 (Raw Layer)

## Key Features

* Support for CSV and JSON formats
* Schema handling and flexible ingestion
* Parameterized pipelines
* Scalable file-based ingestion

## Tech Stack

* Azure Data Factory
* Azure Data Lake Storage Gen2

## Structure

* adf/ → Pipelines, datasets, linked services
* source_config/ → File configuration
* config/ → Environment configuration

## Output

Files are ingested and stored in ADLS Gen2 raw layer.
