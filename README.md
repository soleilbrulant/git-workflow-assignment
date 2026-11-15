# Git & GitHub Workflow Assignment

**Course Assignment:** Git & GitHub Workflow (Module Evaluation)  
**Student:** Shashwat Verma  
**Roll Number:** 10360  
**Repository URL:** [https://github.com/soleilbrulant/git-workflow-assignment](https://github.com/soleilbrulant/git-workflow-assignment)

---

## Overview

This repository demonstrates a complete, end-to-end Git version control workflow executed entirely on a local environment and integrated with GitHub. It covers:
1. Local repository initialization with core web assets (`index.html`, `about.html`).
2. Iterative version control commits and isolated feature branching (`feature` branch).
3. Non-fast-forward branch merging (`--no-ff`) to preserve branch history and topology.
4. `.gitignore` configuration excluding runtime logs (`*.log`) and temporary build directories (`temp/`).
5. Non-destructive Git undo operation (`git revert`) providing full historical accountability.
6. Remote synchronization with GitHub under public visibility.
7. Complete command reference documentation in `git_commands.txt`.

---

## Repository Structure

```text
git-workflow-assignment/
├── .gitignore           # Ignores *.log and temp/
├── index.html           # Home page with navigation & overview
├── about.html           # About page with team details & mission
├── git_commands.txt     # Complete log of Git commands with explanations
└── README.md            # Repository documentation and verification guide
```

---

## Commit History Graph

```text
* Add README.md repository overview
* Add git_commands.txt documenting all workflow commands and explanations
* Revert "Add experimental configuration file"
* Add experimental configuration file
* Add .gitignore to exclude log files (*.log) and temp/ directory
*   Merge branch 'feature' into main
|\  
| * Update about.html: Add navigation, team overview, and contact info
|/  
* Update index.html: Add navigation bar and key capabilities section
* Initial commit: Add index.html and about.html
```
