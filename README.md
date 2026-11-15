# FireLedger Database

SQLite database repository for the FireLedger NASA Space Apps prototype.

## Structure

- `Database/fireledger.db` — generated SQLite database synchronized by the Kaggle notebook.
- The Kaggle notebook is the single intended writer for this prototype.

## Data

The database stores harmonized MODIS and VIIRS fire observations and AI request/response records.

Do not commit access tokens, API keys, or other credentials to this repository.

## Kaggle configuration

Create a fine-grained GitHub token with repository Contents read/write access and store it in Kaggle Secrets as `GITHUB_TOKEN`.
