# Git and GitHub Test Project

## Overview

This project is designed to provide practical experience with Git and GitHub, focusing on repository initialization, branching, merging, and conflict resolution.

## Getting Started

### Prerequisites

Before you begin, ensure you have Git installed on your machine. Additionally, you'll need a GitHub account.

### Repository Initialization and Push

1. **Install Git:**
   If you haven't installed Git, download and install it from [git-scm.com](https://git-scm.com/).

2. **GitHub Account:**
   Create a GitHub account at [github.com](https://github.com/) if you don't have one.

3. **Local Repository Initialization:**
   Choose an existing project and initialize a Git repository in its directory:

   ```bash
   git init

4. **Clone the Repository:**
   ```bash
   git clone https://github.com/akhilesh-sahu12/gitGithubTest.git
   cd gitGithubTest

5. **Add, Commit, and Push:**
   These commands add changes, commit them with a descriptive message, and push the changes to the master branch on GitHub.

   ```bash
   git add .
   git commit -m "Initial commit"
   git push -u origin master

### Branching and Creating Merge Conflicts

1. **Create Branches:**

   ```bash
   git branch feature1
   git branch feature2

2. **Merge Branches:**

   ```bash
   git checkout master
   git merge branch1
   git merge branch2

3. **Generate Merge Conflict:**
Intentionally make different changes in the same file on both feature1 and feature2 to create a merge conflict.

### Resolving Merge Conflicts
1. **Identify Conflicting Changes:**

   ```bash
   git status
Use git status to identify files with conflicts.

2. **Resolve Conflicts:**
   Open the conflicted file(s) in your preferred text editor. Manually resolve conflicts, then:

    ```bash
    git add .
    git commit -m "Resolve merge conflict" 
These commands mark conflicts as resolved and commit the changes.

3. **Push Resolved Changes:**

   ```bash
   git push origin master 


## Screenshots

![App Screenshot](https://miro.medium.com/v2/resize:fit:1400/1*mtsk3fQ_BRemFidhkel3dA.png)