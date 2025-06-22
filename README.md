# ALXprodev-advanced_git

## Overview

This project is part of the ALX Software Engineering curriculum and focuses on mastering advanced Git concepts with a strong emphasis on the Git-Flow branching model. The goal is to set up, understand, and practice collaborative workflows in real-world software development environments.

---

## Objectives

- Initialize a Git repository and set up Git-Flow.
- Understand and apply the Git-Flow branching strategy.
- Learn how to manage `feature`, `release`, and `hotfix` branches.
- Collaborate effectively using structured branching and merging techniques.

---

## Git-Flow Branch Types

- **main**: Contains stable, production-ready code.
- **develop**: Integration branch for ongoing development.
- **feature/**: Used for new feature development from `develop`.
- **release/**: Prepares code from `develop` for deployment to `main`.
- **hotfix/**: Directly fixes bugs on `main` and merges back into both `main` and `develop`.

---

## Project Setup Steps

1. Install Git-Flow if not already available.
2. Create and clone an empty repository named `ALXprodev-advanced_git`.
3. Create and push a `develop` branch.
4. Initialize Git-Flow using default settings with `git flow init -d`.
5. Create an empty `README.md` file and commit it to the `develop` branch.

---

## Git-Flow Commands Cheat Sheet

```bash
git flow init                     # Initialize Git-Flow with default branch settings
git flow feature start <name>    # Start a new feature branch
git flow feature finish <name>   # Finish feature and merge back into develop
git flow release start <version> # Create a release branch from develop
git flow release finish <version> # Merge release into main and develop
git flow hotfix start <version>  # Start a hotfix from main
git flow hotfix finish <version> # Merge hotfix into main and develop
