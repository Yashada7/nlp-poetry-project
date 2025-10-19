# NLP Project

This repository is for our NLP-based poetry generation project using fine-tuned transformer models (BART, BLOOM).

## Folder structure
- data/ – datasets (raw & processed)
- notebooks/ – Jupyter notebooks for EDA and experiments
- src/ – core source code (data, models, evaluation)
- experiments/ – experiment logs, configs, checkpoints
- configs/ – YAML/JSON configuration files
- scripts/ – helper shell scripts
- docs/ – documentation & reports
- tests/ – unit/integration tests

## Collaboration / Getting started

1. Clone:
   git clone https://github.com/YashadaTembe/nlp-poetry-project.git
   cd nlp-poetry-project

2. Create environment:
   conda env create -f environment.yml
   conda activate poetry-nlp

3. Update main before working:
   git checkout main
   git pull origin main

4. Create a branch:
   git checkout -b feature/<your-feature>

5. Work, commit, push:
   git add .
   git commit -m "Brief description"
   git push origin feature/<your-feature>

6. Open a Pull Request on GitHub and request a review.
