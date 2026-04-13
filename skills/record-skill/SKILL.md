---
name: record-skill
description: Start a Flingoos workflow recording session by opening the recording page in the browser. Use this skill whenever the user says /record, 'start recording', 'record a workflow', 'record session', or wants to begin capturing a workflow in Flingoos.
---

# Record Workflow

When this skill is triggered, open the Flingoos recording page in the browser.

## Step 1: Open the recording page

Use the `open_url` tool to open: https://flingoos.com/sessions?autoRecord=workflow

Always use `open_url` — it's the most reliable method since it opens a new Chrome tab directly without needing an existing tab context. Do not use `navigate` or other browser tools unless `open_url` is unavailable.

## Step 2: Confirm

Tell the user that the recording page has been opened in their browser. If they are not already logged in, they will be prompted to sign in first.
