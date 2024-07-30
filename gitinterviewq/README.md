# devops-git-commands-playground
A repository to document my learning journey of Git commands, essential for DevOps practices. This repo will contain practice exercises, scripts, and notes as I master the art of version control.


Developer creates a new feature branch:
Bash
git checkout -b feature-new-feature
Use code with caution.

Developer makes changes and commits:
Bash
git add .
git commit -m "Added new feature"
Use code with caution.

Developer pushes changes to remote repository:
Bash
git push origin feature-new-feature
Use code with caution.

CI/CD pipeline triggers build and test:
Pulls code from the feature branch.
Builds and tests the application.
Deploys the application to a test environment.
Developer merges feature branch into main branch:
Bash
git checkout main
git merge feature-new-feature
Use code with caution.

CI/CD pipeline triggers deployment to production:
Deploys the application to the production environment.
