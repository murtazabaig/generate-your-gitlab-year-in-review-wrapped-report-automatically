

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# Generate your GitLab year-in-review wrapped report automatically

Advanced n8n automation for Generate your GitLab year-in-review wrapped report automatically.

## Overview
- Category: Engineering
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
Generate a personalized GitLab Wrapped year-in-reviewauto-fork, run CI/CD, and publish shareable stats for GitLab.com or self-hosted.

## Included Files
- `workflow.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `n8n-nodes-base.code`
- `n8n-nodes-base.formTrigger`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.if`
- `n8n-nodes-base.merge`
- `n8n-nodes-base.noOp`
- `n8n-nodes-base.set`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.wait`

## Author

Murtaza Baig

## License
MIT License. See `LICENSE`.