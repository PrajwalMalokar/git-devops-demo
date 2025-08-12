## DevOps Git Workflow Demo

This repository showcases a simple Flask app (login, home, profile pages) and a clean Git branching workflow practiced during the internship task.

### What I Did
1. Initialized a new Git repository with the default `main` branch.
2. Created a long‑lived integration branch: `dev`.
3. Created feature branches one by one to isolate work:
	- `feature/home` – added the home page (`index.html`).
4. Pushed each feature branch to GitHub.
5. Opened separate pull requests (PRs) from each `feature/*` branch into `dev` and merged them after review.
6. After all features were integrated, created a PR from `dev` into `main` and merged it – promoting the combined work to the main branch.

### Branching Model
- `main`: Stable / production-ready code.
- `dev`: Integration / staging branch.
- `feature/*`: Short‑lived branches for individual changes.

### Pages Implemented
- Home page: simple landing screen.

### Git Concepts Practiced
- Repository initialization
- Branch creation & isolation of work
- Feature branching strategy
- Pull requests & merge flow
- Promotion from feature → dev → main

### How to Run (Local)
```bash
pip install flask
python app.py
```
Visit: http://localhost:5000/

---
Author: Prajwal Malokar
