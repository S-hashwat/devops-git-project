# DevOps Git Project Documentation

## Objective

To build and manage a version-controlled DevOps project using Git and GitHub, following industry best practices.

## Tools Used

- Git
- GitHub
- Node.js
- Markdown

## Project Setup

A basic Node.js application was created from scratch using the following steps:

1. Initialized a new Node.js project using `npm init -y`.
2. Created a simple HTTP server using Node.js in `index.js`.
3. Created a `.gitignore` file to exclude `node_modules/` and other unnecessary files.

## Git Repository Initialization

1. Initialized a local Git repository using `git init`.
2. Committed initial project files.
3. Created a new GitHub repository and connected it to the local repository using a remote URL.
4. Pushed the `main` branch to GitHub.

## Branching Strategy

The following Git branching model was implemented:

- main – stable production-ready code
- dev – integration branch for development
- feature/homepage – feature-specific development branch

**Branches were created using:**
git checkout -b branch_name

**Pull Requests and Merging **
Feature branch changes were pushed to GitHub.

A pull request (PR) was created from feature/homepage to dev. After review, the PR was merged into the dev branch. A final PR was created and merged from dev into main.

**Project Documentation**
Two markdown files were added to the project:

README.md: Describes the project purpose, features, and usage instructions.
TASKS.md: Lists all tasks completed during the project in a clear bullet-point format.

**Versioning**
A Git tag v1.0 was created to mark the first stable release of the project using:
git tag -a v1.0 -m "Initial stable release"
git push origin v1.0

**Conclusion**
The project successfully demonstrates Git best practices, including branching, pull requests, tagging, and markdown documentation, 
while also delivering a functional Node.js application.

# Tasks

- Initialize Node.js app
- Setup GitHub repository
- Create dev, feature, and main branches
- Use pull requests for merging
- Add a proper README.md file
- Create a .gitignore file
- Use Git tags for versioning
- Document all tasks using markdown



