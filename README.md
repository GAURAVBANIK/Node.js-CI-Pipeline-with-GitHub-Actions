🚀 Node.js CI Pipeline with GitHub Actions

This project demonstrates a Continuous Integration (CI) pipeline for a Node.js application using GitHub Actions.
The pipeline automatically installs dependencies, runs tests, and executes the application on every push to the main branch.

📌 Project Purpose

The goal of this project is to learn and implement:

GitHub Actions workflows

CI automation for Node.js

YAML workflow structure

Job and step execution in CI pipelines

This is a CI-only pipeline (no deployment yet).

⚙️ Workflow Features

✔ Runs on every push to main
✔ Sets up Node.js environment
✔ Installs dependencies using npm
✔ Runs test scripts
✔ Runs the application

🛠 Tech Stack

Node.js

npm

GitHub Actions

YAML

📁 Project Structure
.
├── index.js
├── test.js
├── package.json
└── .github
    └── workflows
        └── ci.yml

🔁 GitHub Actions Workflow

The workflow file is located at:

.github/workflows/ci.yml


It performs the following steps:

Checkout repository

Setup Node.js (v18)

Install dependencies

Run tests

Run application

▶️ How to Run Locally
npm install
npm test
npm start

🧪 Sample Output
Tests passed successfully!
Node CI pipeline working!

📊 CI Pipeline Status

Every push triggers the workflow automatically in GitHub Actions.

You can view runs in:

GitHub Repo → Actions tab

🚀 Future Improvements

Add Docker build stage

Add Trivy security scan

Add deployment stage

Upload build artifacts

📖 Learning Outcome

This project helped me understand:

How CI pipelines are structured

How jobs and steps work

Difference between uses and run

How GitHub Actions automates builds

🙌 Author

Gaurav Banik
Learning DevOps | CI/CD | GitHub Actions
