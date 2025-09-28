👥 Team Portfolio Collaboration Guide

Welcome to the Team Portfolio Project 🎉
This project will help us learn GitHub collaboration while building a simple portfolio website that shows all our team members.

✅ Steps to Collaborate
1. Accept Invite

Check your email or GitHub notifications.

Accept the invitation to join this repository as a Collaborator.

2. Clone Repository
   
git clone <repo-link>
cd team-portfolio

4. Create Your Branch

👉 Always work in a separate branch (not directly in main).

    git checkout -b feature/<your-name>


Example:

     git checkout -b feature/vedant

4. Add Your Profile

Open index.html (or the profile folder if given).

Add your profile card using this template:


5. Commit Your Changes
git add .
git commit -m "Added <your-name> profile card"

6. Push Your Branch
git push origin feature/<your-name>

7. Open a Pull Request (PR)

Go to the repository on GitHub.

Click Compare & pull request.

Add a short description → "Added my profile card".

Click Create Pull Request.

8. Review & Merge

Wait for the Team Leader to review your PR.

Once approved, it will be merged into main.

9. Update Your Local Repo

After merge, always sync your local repo:

git checkout main
git pull origin main

⚡ Notes

Don’t push directly to main. Always use a feature branch.

Use meaningful commit messages.

If you face merge conflicts, ask the leader for guidance.

✨ Congratulations! You’ve learned the basics of GitHub Collaboration 🚀
