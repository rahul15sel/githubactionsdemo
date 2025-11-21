🚀 Pipeline Overview

The pipeline is triggered automatically on every push to the repository.

It contains the following stages:

Code – Initial stage

Lint Check – Code quality checks

Build – Build or compile the project

Testing – Run automated tests

Deploy – Deploy to an environment

Release – Final release stage

Each stage runs only after the previous stage is completed using the needs: dependency.

🔗 CI/CD Stage Flow

This workflow follows a strict sequential order:

Code → Lint Check → Build → Testing → Deploy → Release
The needs: keyword ensures that each job runs only after the previous stage completes successfully.

📌 Key Features

✔ Fully automated pipeline
✔ Sequential stage execution
✔ Simple and easy to understand
✔ Good base template for real-world CI/CD workflows
✔ Uses Ubuntu GitHub-hosted runners

📚 How to Use

Create the folder:

.github/workflows/


Create a file inside it, for example:

cicd-demo.yml


Paste the workflow code.

Commit and push the file — the pipeline will start automatically.
