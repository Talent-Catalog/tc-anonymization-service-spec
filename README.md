# tc-anonymization-service-spec

This repository contains the OpenAPI specification for the Talent Catalog Anonymization Service API.

To browse the spcification using ReDoc, follow these steps:

### Step 1. Install `openapi-cli`

First, you need to install `openapi-cli` if you haven’t already. This tool requires **Node.js** and 
**npm**.

1. **Install Node.js** (if you don't have it installed):
    - Download from [Node.js](https://nodejs.org/).
    - Installing Node.js also installs `npm`.


2. **Install `openapi-cli`** globally via npm:

   ```bash
   npm install -g @redocly/cli
   ```

   This command installs `openapi-cli` globally on your system, so you can use it from any directory.

### Step 2. Preview API specification 

- To preview the Open API specification in a browser with ReDoc, use this command from the project 
  root folder:

  ```bash
  openapi preview-docs ./openapi.yaml
  ```

  This will starts a local server that renders the API documentation using ReDoc, allowing you to 
  view it as users would.

