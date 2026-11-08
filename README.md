# Happy Diwali

An interactive Diwali greeting page with animated fireworks and diyas.

## Run locally

Open [index.html](./index.html) in a browser. No build tools or dependencies are required.

## Deploy to GitHub Pages

The repository includes a GitHub Actions workflow at
`.github/workflows/deploy-pages.yml`. It publishes the site whenever changes
are pushed to the `main` branch.

To enable deployment in a repository:

1. Create a GitHub repository and push this project to its `main` branch.
2. Ensure **Settings → Actions → General → Workflow permissions** allows
   workflows to read and write repository contents.
3. Open the **Actions** tab to monitor the deployment. The workflow requests
   Pages enablement automatically.
4. If your organization disables automatic Pages enablement, open
   **Settings → Pages**, choose **GitHub Actions**, and rerun the workflow.

The published URL will appear in the workflow run summary and under
**Settings → Pages**.
