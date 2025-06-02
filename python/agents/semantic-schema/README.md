# BigQuery Semantic Schema Generations

## Overview

The Agent can automatically enriches BigQuery table with a right semantic layer, describing not just the schema but the business meaning of the data.
This semantic metadata generation unlocks two powerful capabilities: an intuitive, concept-based search for tables and a significant boost in the accuracy of NL2SQL tools, enabling analysts to get to deeper insights, faster.

## Setup and Installation

1.  **Install Dependencies**

    ```bash
    python -m venv venv
    source venv/bin/activate
    pip install -e .[all]
    ```


2.  **Run Agents**

Run agent in CLI:
    ```bash
    adk run semantic_schema
    ```

Run agent with ADK Web UI:
    ```bash
    adk web
    ```

