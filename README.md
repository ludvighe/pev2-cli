# PEV2 CLI

This is a simple hack and utility for [pev2 by dalibo](https://github.com/dalibo/pev2).

## Setup

Run the setup script to fetch and setup the html file to use.

## Usage

_Note that this uses environment variable $BROWSER to open pev2._

Analyze a query from file.

```sql
-- analysis.sql
SELECT * FROM your_table;
```

```sh
psql-analyze analysis.sql
```

Open pev2 with generated analysis in browser.

```sh
pev2 analysis.json
```
