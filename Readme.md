### Introduction
This guide outlines how to update the Vidal Health chatbot by making new releases on GitHub and describes how the provided script dynamically fetches and deploys the latest version of the chatbot on the Vidal Health website.

### Making a New Release on GitHub
To make a new release of the chatbot, follow these steps:

### Prepare the Release:

Ensure all changes for the chatbot (including updates to main.js and main.css) have been merged into the appropriate branch (either chatbot-prod for production or chatbot-build for other environments).
Tag the Release:

Navigate to the repository on GitHub (vidal-health/chatbot-prod for production releases, vidal-health/chatbot-build for others).
Click on "Releases" > "Draft a new release".
Tag the release following semantic versioning (for example, v1.0.1). The tag should be created on the branch that contains the latest code.
Add release notes summarizing the changes.
Publish the Release:

Once all details have been filled in, click "Publish release".
This action makes the new version of the files available under the newly created tag.

Reference for making the release: https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository
