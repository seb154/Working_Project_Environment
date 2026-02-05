# Recipe to New Working Project Environment

1. Create a new project environment or clone an existing repo
2. Create a codespace on GitHub if you don't already have one
3. Open local VS Code and "Connect to.." the codespace
4. In your terminal, create a virtual environment and activate it ("python -m venv .venv" and activate: "source .venv/bin/activate")
5. Install Jupyter and Python packages (+ additional required packages)
6. Create and save all packages to requirements.txt
7. Run requirements.txt ("pip install -r requirements.txt")
8. Commit changes and push to GitHub repo (git status ; git add ; git commit -m "message"; git push)
