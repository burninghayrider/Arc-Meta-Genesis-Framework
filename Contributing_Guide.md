# Contributing Guide for ArcMGF

## Introduction
Thank you for your interest in contributing to ArcMGF! This guide will help you set up your environment, follow coding standards, and submit contributions effectively.

## Setting Up Development Environment
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-org>/ArcMGF.git
   cd ArcMGF
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. (Optional) Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```

## Code Style and Standards
- Follow **PEP 8** guidelines for Python code.
- Use descriptive variable names and docstrings for all functions.
- Ensure modularity and readability.

## Adding New Features
- Create a new branch for your feature:
   ```bash
   git checkout -b feature/<feature-name>
   ```
- Add new modules or synthesis logic under `modules/`.
- Update configuration templates if required.

## Adding Observational Anchors
- Place new datasets in `data/anchors/`.
- Update `config/anchors.yaml` with dataset details.
- Ensure compatibility with `run_arc.py` observational mode.

## Testing and Validation
- Write unit tests for new features in `tests/`.
- Validate predictive arcs and entropy calibration.
- Run:
   ```bash
   pytest
   ```

## Submitting Pull Requests
1. Push your branch:
   ```bash
   git push origin feature/<feature-name>
   ```
2. Open a Pull Request (PR) on GitHub.
3. Include a detailed description of changes and validation steps.

## Community and Collaboration Guidelines
- Be respectful and constructive in discussions.
- Use GitHub Issues for bug reports and feature requests.
- Join our community Slack/Discord for collaboration.

