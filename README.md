# Gemini CLI Extension - Dataplex

This Gemini CLI extension provides a set of tools to interact with [Dataplex](https://cloud.google.com/dataplex/docs) instances. It allows you to manage your data lakes, zones, and assets directly from the [Gemini CLI](https://google-gemini.github.io/gemini-cli/), using natural language prompts.

## Features

*   **Integrated with Gemini CLI:** As a Google-developed extension, it integrates seamlessly into the Gemini CLI environment, making security an accessible part of your workflow.
*   **Connect to Dataplex:** Securely connect to your Dataplex instances.
*   **Explore Data Assets:** List lakes, zones, and assets.

## Supported Tools

🟢 dataplex_search_entries: Use this tool to search for entries in Dataplex Catalog based on the provided search query.
🟢 dataplex_lookup_entry: Use this tool to retrieve a specific entry from Dataplex Catalog.
🟢 dataplex_search_aspect_types: Use this tool to find aspect types relevant to the query.

## Prerequisites

Before you begin, ensure you have the following:

*   [Gemini CLI](https://github.com/google-gemini/gemini-cli) installed.
*   A Google Cloud project with the **Dataplex API** enabled.
*   IAM Permissions

## Installation

To install the extension, use the `gemini extensions install` command:

```bash
gemini extensions install github.com/gemini-cli-extensions/dataplex.git
```

## Configuration

*   `DATAPLEX_PROJECT`: The GCP project ID.


## Usage

* Explore Data Assets


## Security

This extension executes commands against your Dataplex service. Always review the commands before execution.

## Disclaimer

This is not an officially supported Google product. This extension is under active development, and breaking changes may be introduced.