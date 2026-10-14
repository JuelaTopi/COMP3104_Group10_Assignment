# COMP3104_Group10_Assignment

## Project Description
This project demonstrates collaborative Git and GitHub workflows for COMP3104 DevOps. It includes individual branches, commits, pull requests, and a basic GitHub Actions workflow.

## Group Members
- Leader: Juela Topi, 101087887, https://github.com/JuelaTopi
- Almas Sultana: 101568934, https://github.com/almas1990
- Arcadio Vega: student ID and GitHub link to be added by Arcadio.

## Setup Instructions
Clone the repository:
    git clone https://github.com/JuelaTopi/COMP3104_Group10_Assignment.git

Enter the project folder:
    cd COMP3104_Group10_Assignment

Create your branch using your own student ID and name:
    git switch -c STUDENTID-Name
    git push -u origin STUDENTID-Name

No application dependencies are required for this text-based assignment.

## Required Files
Each member creates three files directly in the repository root:
- STUDENTID_gb.txt: Information about George Brown College.
- STUDENTID_devops.txt: Information about the DevOps course.
- STUDENTID_sdlc.txt: Importance of DevOps in the software development lifecycle.

Each member makes at least 10 meaningful commits locally and contributes to this README.

## Continuous Integration
The GitHub Actions workflow is stored in .github/workflows/ci.yml.
It runs on pushes and pull requests using an Ubuntu runner.
Echo commands demonstrate that the workflow executes.
This workflow does not test an application or deploy a website.

## Branching Strategy
Each member works on a personal branch named STUDENTID-Name.
Juela's branch is 101087887-Juela.
Changes are reviewed through pull requests before merging into main.
Use merge commits to preserve individual commit history.

## Keeping Your Branch Updated
While on your personal branch, commit your current work, then run:
    git fetch origin
    git merge origin/main

If conflicts occur, review and resolve them, stage the corrected files, and complete the merge.
Push your updated branch to GitHub.

## Pull Requests
The template is stored in .github/PULL_REQUEST_TEMPLATE.md.
Each member describes their changes and completes applicable checklist items.
All file edits and commits are made locally.

## Submission
The leader submits a PDF or DOCX containing the repository link and screenshots from each member showing:
- Local repository setup.
- Git commit history.
- Branch structure.
- CI pipeline status.
