# Dev Assessment - Action Repo

This repository is used with the webhook receiver. GitHub webhooks are configured here to send Push, Pull Request, and Merge events to the webhook-repo endpoint.

*******************

## Setup

* Push this repository to GitHub and create a webhook in **Settings → Webhooks → Add webhook**.

* **Payload URL**: Your webhook-repo URL + `/webhook` (e.g. `https://your-app.ngrok-free.dev/webhook`)

* **Content type**: `application/json`

* **Events**: Select **Pushes** and **Pull requests**.

*******************
