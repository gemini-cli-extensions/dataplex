# Gemini CLI Extension - Dataplex

This Gemini CLI extension provides a set of tools to interact with [Dataplex](https://cloud.google.com/dataplex/docs) instances. It allows you to manage your data lakes, zones, and assets directly from the [Gemini CLI](https://google-gemini.github.io/gemini-cli/), using natural language prompts.

## Why Use the Dataplex Extension?

* **Natural Language Management:** Stop wrestling with complex commands. Explore schemas and query data by describing what you want in plain English.
* **Seamless Workflow:** As a Google-developed extension, it integrates seamlessly into the Gemini CLI environment. No need to constantly switch contexts for common database tasks.
* **Code Generation:** Accelerate development by asking Gemini to generate data classes and other code snippets based on your table schemas.

## Prerequisites

Before you begin, ensure you have the following:

* [Gemini CLI](https://github.com/google-gemini/gemini-cli) installed.
* A Google Cloud project with the **Dataplex API** enabled.
* IAM Permissions:
  * Dataplex Data Reader (`roles/dataplex.dataReader`): For reading data from the underlying assets (e.g., to run analytics queries).
  * Service Usage Consumer (`roles/serviceusage.serviceUsageConsumer`)

## Installation

To install the extension, use the command:

```bash
gemini extensions install github.com/gemini-cli-extensions/dataplex
```

## Configuration

* `DATAPLEX_PROJECT`: The GCP project ID.

## Usage Examples

Interact with Dataplex using natural language right from your IDE:

* **Explore Catalog and Metadata:**
  * "Find all catalog entries related to 'customer orders'."
  * "Which columns look similar across marketing and sales datasets?"
  * "Show me the description and owner for the 'customer_pii' entry."
  
* **Perform Ad-hoc Analysis:**
  * "Calculate the total 'customer orders' this month."

## Supported Tools

* `search_entries`: Use this tool to search for entries in Dataplex Catalog based on the provided search query.
* `lookup_entry`: Use this tool to retrieve a specific entry from Dataplex Catalog.
* `search_aspect_types`: Use this tool to find aspect types relevant to the query.

## Additional Extensions

Find additional extensions to support your entire software development lifecycle at [github.com/gemini-cli-extensions](https://github.com/gemini-cli-extensions).

## Troubleshooting

* "cannot execute binary file": Ensure the correct binary for your OS/Architecture has been downloaded. See [Installing the server](https://googleapis.github.io/genai-toolbox/getting-started/introduction/#installing-the-server) for more information.
