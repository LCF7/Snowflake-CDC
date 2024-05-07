# Snowflake CDC Process for the NATION Table

## Overview

This repository houses the essential SQL scripts and detailed setup instructions for executing a Change Data Capture (CDC) process specifically designed for the NATION table in Snowflake. This includes the creation of staging tables, CDC tables, and the automation infrastructure like streams and tasks necessary for efficient data capture and historical tracking.

## Repository Contents

- **SQL Scripts:** Contains all necessary scripts for establishing tables, streams, and tasks required for the CDC process.
- **Documentation:** Provides a detailed guide and screenshots demonstrating the final setup and operation.

## Features

- **CDC Implementation:** Efficiently tracks and logs all changes (inserts, updates, deletes) to the NATION table, ensuring data integrity and continuity.
- **Data Staging:** Utilizes a staging table (`stg_active_nation`) to effectively manage and reconcile changes before they are committed to the main table.
- **Historical Tracking:** Maintains a dedicated historical changes table (`nation_historic_changes`) which archives every change made to the data along with precise timestamps, facilitating detailed analysis and auditing.

## Getting Started

To initiate this project:

1. Clone this repository to your local machine.
2. Log into your Snowflake account and set up an environment suitable for executing the provided scripts.
3. Modify the SQL scripts to adapt to your specific Snowflake setup, including account details and configurations.

### Prerequisites

- A Snowflake account with permissions sufficient to create and manage databases, tables, streams, and tasks.
- Familiarity with SQL and Snowflake’s specific features such as streams and tasks is beneficial.
- Follow the exercise in my repo: https://github.com/LCF7/snowflake-set-up.

### Setup Instructions

1. **Database and Table Setup:**
   - Run the scripts to create necessary staging and CDC tables.
   - Configure streams and tasks to automate data capture.

2. **Monitoring and Maintenance:**
   - Regularly check the operation of streams and tasks.
   - Update configurations as needed based on operational feedback and system performance.

## Additional Resources

- [Snowflake Documentation](https://docs.snowflake.com): Extensive resources on setting up and managing CDC processes in Snowflake.
- [Snowflake Community Support](https://community.snowflake.com): Engage with other Snowflake users and experts to enhance your CDC implementation.

## Contributors

- **Luis Franco**: Project Lead and main contributor.



