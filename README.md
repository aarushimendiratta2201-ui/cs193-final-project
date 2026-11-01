# CS 193 Final Project: GitHub Streak Keeper

## Project Goal
To automate daily GitHub profile contributions using a lightweight scheduled background script.

## Problem Statement
I want to solve the problem of updating my github portfolio everyday to make my activity seem consistent. Developers cannot always update their github everyday or forget to commit some changes. I want my GitHub contribution graph (those green squares) to stay active every day.

## MVP Scope
The minimum viable product consists of a Bash script that adds a blank line to `README.md`, paired with a GitHub Actions workflow configured to run automatically once per day at 11:00 pm.

## Future Plans
* Add logic to automatically skip commits when a commit has already been made.
* Randomize the daily commit time so updates look more natural
* Alternate between adding and removing spaces so as to not add too much extra space
  
## Tech Stack
* **Language:** Bash (Shell Scripting), YAML (GitHub Actions Workflow)
* **Shell Commands:** `bash`, `echo`, `git config`, `git add`, `git commit`, `git push`, `chmod`
* **Automation Platform:** GitHub Actions (`cron` scheduled trigger)
* **Data Storage:** Flat markdown file (`README.md`)
