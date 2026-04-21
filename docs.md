# ADO-README – Azure DevOps README and md files for Confluence

## Overview
ADO-README allows you to display Markdown (.md) files from Azure DevOps repositories directly inside Confluence pages.

This helps teams keep documentation in sync with their codebase and avoid manual copy-paste.

---

## Features
- Display Markdown (.md) files from Azure DevOps in Confluence
- Supports organization, project, repository, branch, and file path selection
- Always loads the latest version of the file from the repository
- Securely stores Azure DevOps Personal Access Token (PAT) using Atlassian Forge

---

## Installation
1. Install the app from the Atlassian Marketplace  
2. Open a Confluence page  
3. Insert the Okami Labs macro  
4. Configure your Azure DevOps settings  

---

## Configuration
Provide the following:

- **Organization** – Your Azure DevOps organization  
- **Project** – Project name  
- **Repository** – Repository name  
- **Branch** – Default is `main`  
- **File path** – Must point to a `.md` file  
- **Personal Access Token (PAT)** – Required for access  

The PAT is stored securely using Atlassian Forge.

---

## Supported Files
Only Markdown files are supported.

---

## Usage
Once configured, the app will:

- Fetch the Markdown file from Azure DevOps  
- Render it directly in the Confluence page  
- Allow reloading to fetch the latest version  

---

## Security
- Uses a shared Azure DevOps Personal Access Token (PAT)  
- PAT is securely stored via Atlassian Forge encrypted storage  
- No repository content is stored outside Atlassian infrastructure  
- No data is shared with third parties  

---

## Troubleshooting

**Common issues:**

- Invalid organization, project, or repository  
- Incorrect file path  
- Missing or invalid PAT  

**Fix:**
- Verify all inputs  
- Ensure PAT has repository access  
- Ensure file path ends with `.md`  

---

## Support
For support, contact:

**support@okamilabs.dev**
