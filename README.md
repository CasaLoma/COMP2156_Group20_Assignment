# COMP 2156 DevOps for System Administration Group Assignment

**Course:** COMP 2156
**Institution:** George Brown College
**Submission Deadline:** Sunday Feb 22 2026
**Total Weight:** 14%

## Group 20 Members
* Brandon: 101570879
* Tristan: 101569571
* Sean: 101553249
* Ryan: 101571326

## Project Description
This repository contains the individual contributions for the DevOps Group Assignment 1. Each member has created specific text files related to:
* George Brown College (`*_gb.txt`)
* DevOps Course Information (`*_devops.txt`)
* Software Development Life Cycle (`*_sdlc.txt`)

## Setup Instructions
To view this project locally follow these steps:
1. Open your terminal.
2. Clone the repository using `git clone https://github.com/CasaLoma/COMP2156_Group20_Assignment.git`
3. Navigate into the directory using `cd COMP2156_Group20_Assignment`

## CI/CD Information
This repository utilizes GitHub Actions for Continuous Integration. A workflow file (`.github/workflows/main.yml`) is configured to run automated checks whenever code is pushed to the repository ensuring integration success.

## Branching Strategy
This project follows a feature-branch workflow.
1. **Creation:** Each member creates a dedicated branch using the format `STUDENTID-Name`.
2. **Development:** All individual file creation and commits occur on these local branches.
3. **Integration:** Branches are merged into the `main` branch via GitHub Pull Requests.
4. **Syncing:** After a Pull Request is accepted all members pull the updated `main` branch to their local machines to resolve conflicts and keep all branches identical.