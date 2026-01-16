# Architecture Overview

This project implements an end-to-end data engineering pipeline using Microsoft Fabric.

## High-Level Architecture

The solution follows a lakehouse approach with clear separation of concerns:

- **Data ingestion** orchestrated via Fabric Data Pipelines
- **Raw data storage** in the Bronze layer
- **Transformations** implemented using PySpark notebooks
- **Curated datasets** stored in Silver and Gold layers within the Lakehouse

The architecture is designed to be simple, maintainable, and aligned with analytics engineering best practices.

## Architecture Diagram

![Architecture Diagram](../images/architecture_overview.png)
