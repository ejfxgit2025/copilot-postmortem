# Copilot Postmortem CLI

A practical demonstration project built for the GitHub Copilot CLI Challenge, showcasing how GitHub Copilot can be used directly from the command line to explain commands and analyze errors.

## Project Overview

This project focuses on real-world terminal usage, where developers encounter command-line errors and use GitHub Copilot CLI to understand what went wrong and how to fix it. The goal is to demonstrate Copilot CLI as a learning and productivity tool inside the terminal.

## Objectives

- Demonstrate GitHub Copilot CLI usage in the command line
- Explain terminal and Git commands using Copilot
- Analyze real error messages generated during development
- Keep the project simple and focused on Copilot CLI interaction

## Technologies Used

- GitHub Copilot CLI
- GitHub CLI (`gh`)
- Windows Command Prompt (CMD)
- Git
- GitHub

## Project Structure

```

copilot-postmortem/
├── postmortem.bat
└── README.md

````

## Files

- `postmortem.bat`  
  A simple Windows batch script used as a runnable artifact for demonstration purposes.

- `README.md`  
  Documentation describing the project and Copilot CLI usage.

## How GitHub Copilot CLI Was Used

GitHub Copilot CLI was used to:
- Explain Windows CMD commands such as `dir`, `cd`, and `mkdir`
- Explain Git commands like `git status`, `git push`, and `git branch`
- Analyze real command-line error messages
- Provide guidance on fixing common terminal and Git errors
- Assist during repository setup and troubleshooting

## Example Copilot CLI Commands

### Explaining an Error
```bash
gh copilot -i "explain The system cannot find the path specified"
````

### Explaining a Command

```bash
gh copilot -i "explain git push"
```

## Design Decision

This project is intentionally minimal to ensure that GitHub Copilot CLI usage is clearly demonstrated without additional application complexity.

## Conclusion

This repository demonstrates how GitHub Copilot CLI can turn terminal errors into learning opportunities by providing clear explanations and guidance directly in the command line.

```
```
