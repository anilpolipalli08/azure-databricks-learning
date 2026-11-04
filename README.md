# azure-databricks-learning
# Crypto Market Analytics Platform

## Overview

A secure, metadata-driven data engineering platform built using Databricks, PySpark, Delta Lake, dbt, and Git.

The project ingests live and reference cryptocurrency data, processes it through Bronze, Silver, and Gold layers, and creates a Star Schema using Fact and Dimension tables.

## Architecture

Source Systems
        ↓
Secure Ingestion
        ↓
Control Table
        ↓
Metadata-Driven Pipeline
        ↓
Bronze
        ↓
Silver
        ↓
Gold
        ↓
dbt
        ↓
Fact + Dimension
        ↓
Star Schema
        ↓
BI Dashboard

## Git Environments

- DEV → dev branch
- UAT → uat branch
- PROD → main branch

Promotion flow:

DEV → UAT → PROD

## Key Features

- Live data ingestion
- Multiple data sources
- Metadata-driven processing
- Control table
- Reusable pipeline
- Bronze/Silver/Gold architecture
- Tumbling-window processing
- Incremental processing
- Watermarking
- Data quality checks
- Error handling and retries
- Audit logging
- Schema evolution
- Duplicate handling
- dbt transformations
- Star Schema
- Fact and Dimension tables
- Security and access control
- Git-based CI/CD

## Security

- No hardcoded credentials
- Secrets kept outside source code
- Environment-specific configuration
- Least-privilege access
- Data access controls
- Secure API connections
- Sensitive-data protection
- Git secret protection

## Project Status

Project initialization.