# Complyance Modes Manager API Documentation

This repository contains the documentation for the Complyance Modes Manager API - your gateway to global tax compliance automation.

## Features

- **API Reference** - Complete documentation for all integration endpoints
- **SDK Guide** - Java SDK documentation and examples
- **Core Concepts** - Understanding integrations, field mapping, and document types
- **Getting Started** - Quick start guide and authentication setup

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```bash
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```bash
mintlify dev
```

The documentation will be available at `http://localhost:3000`

## Publishing Changes

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard. 

## Project Structure

- `mint.json` - Mintlify configuration file
- `introduction.mdx` - Main introduction page
- `api-reference/` - API endpoint documentation
- `sdk/` - SDK guides and examples
- `concepts/` - Core concept explanations

## Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
- For support, contact: support@complyance.io
