# Gemini CLI Extension - Dataplex

> [!NOTE]
> This extension is currently in beta (pre-v1.0), and may see breaking changes until the first stable release (v1.0).

This Gemini CLI extension provides a set of tools to interact with [Dataplex](https://cloud.google.com/dataplex/docs) instances. It allows you to manage your data lakes, zones, and assets directly from the [Gemini CLI](https://google-gemini.github.io/gemini-cli/), using natural language prompts.

Learn more about [Gemini CLI Extensions](https://github.com/google-gemini/gemini-cli/blob/main/docs/extensions/index.md).
> [!IMPORTANT]
> **We Want Your Feedback!**
> Please share your thoughts with us by filling out our feedback [form][form]. 
> Your input is invaluable and helps us improve the project for everyone.

[form]: https://docs.google.com/forms/d/e/1FAIpQLSfEGmLR46iipyNTgwTmIDJqzkAwDPXxbocpXpUbHXydiN1RTw/viewform?usp=pp_url&entry.157487=dataplex

## Why Use the Dataplex Extension?

* **Natural Language Management:** Stop wrestling with complex commands. Explore schemas and query data by describing what you want in plain English.
* **Seamless Workflow:** As a Google-developed extension, it integrates seamlessly into the Gemini CLI environment. No need to constantly switch contexts for common database tasks.
* **Code Generation:** Accelerate development by asking Gemini to generate data classes and other code snippets based on your table schemas.


## Prerequisites

Before you begin, ensure you have the following:

* [Gemini CLI](https://github.com/google-gemini/gemini-cli) installed with version **+v0.6.0**.
* Setup Gemini CLI [Authentication](https://github.com/google-gemini/gemini-cli/tree/main?tab=readme-ov-file#-authentication-options).
* A Google Cloud project with the **Dataplex API** enabled.
* Ensure [Application Default Credentials](https://cloud.google.com/docs/authentication/gcloud) are available in your environment.
* IAM Permissions:
  * Dataplex Data Reader (`roles/dataplex.dataReader`): For reading data from the underlying assets (e.g., to run analytics queries).
  * Service Usage Consumer (`roles/serviceusage.serviceUsageConsumer`)

## Getting Started

### Installation

To install the extension, use the command:

```bash
gemini extensions install https://github.com/gemini-cli-extensions/dataplex
```

### Configuration

Set the following environment variables before starting the Gemini CLI. These variables can be loaded from a `.env` file.

* `DATAPLEX_PROJECT`: The GCP project ID.

Ensure [Application Default Credentials](https://cloud.google.com/docs/authentication/gcloud) are available in your environment.

### Start Gemini CLI

To start the Gemini CLI, use the following command:

```bash
gemini
```

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

Use `gemini --debug` to enable debugging.

Common issues:

* "failed to find default credentials: google: could not find default credentials.": Ensure [Application Default Credentials](https://cloud.google.com/docs/authentication/gcloud) are available in your environment. See [Set up Application Default Credentials](https://cloud.google.com/docs/authentication/external/set-up-adc) for more information.
* "✖ Error during discovery for server: MCP error -32000: Connection closed": The database connection has not been established. Ensure your configuration is set via environment variables.
* "✖ MCP ERROR: Error: spawn /Users/USER/.gemini/extensions/dataplex/toolbox ENOENT": The Toolbox binary did not download correctly. Ensure you are using Gemini CLI v0.6.0+.
* "cannot execute binary file": The Toolbox binary did not download correctly. Ensure the correct binary for your OS/Architecture has been downloaded. See [Installing the server](https://googleapis.github.io/genai-toolbox/getting-started/introduction/#installing-the-server) for more information.
