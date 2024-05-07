# Snowflake CDC Process for the NATION Table

## Overview

This repository contains the SQL scripts and setup instructions for implementing a Change Data Capture (CDC) process in Snowflake for the `NATION` table. The setup includes the creation of staging tables, CDC tables, and the necessary streams and tasks to automate the data capture and history tracking processes.

## Repository Contents

- **SQL Scripts**: Contains all scripts for creating tables, streams, and tasks.
- **Documentation**: Includes screenshot of the final result.

## Features

- **CDC Implementation**: Tracks changes (inserts, updates, deletes) to the `NATION` table.
- **Data Staging**: Utilizes a staging table (`stg_active_nation`) to manage and merge changes.
- **Historical Tracking**: Maintains a historical changes table (`nation_historic_changes`) to store a log of all changes along with timestamps.


