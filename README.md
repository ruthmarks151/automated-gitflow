# automated-gitflow
Automate key aspects of a gitflow workflow with Github actions


## Features
- When an issue is tagged as 'hotfix' or 'in progress': a branch gets created
- When a PR gets opened for a `hotfix/` or `feature/` branch: Populate the PR description with the issue's content, and comment on the issue with a link to the PR
- When new code lands on `main`: Open a backmerge PR to develop

