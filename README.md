# poc-nocodb

Proof of concept for **Self-Hosting NocoDB: Replace Airtable with Your Own No-Code Database Platform**.

Live demo: https://nocodb.poc.ardotconsulting.com

Blog post: https://www.ardotconsulting.com/blog/2026/10/22/self-hosting-nocodb-replace-airtable-with-your-own-no-code-database-platform/

## What

[NocoDB](https://github.com/nocodb/nocodb) is a self-hosted, no-code database platform that turns any database into a smart spreadsheet. It runs as a single container with embedded SQLite — no external database required.

## Run locally

```bash
docker build -t nocodb-poc .
docker run -d -p 8080:8080 nocodb-poc
```

Open http://localhost:8080 to access the dashboard.
