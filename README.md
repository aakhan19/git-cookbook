# Git Cookbook: A Guide to Git

## The Perfect Commit

1. Add the *right* changes!
    - `git diff <staged filename>`
    - `git add -p <filename>`
2. Compose a *good* commit message!
    - `git commit`
        1. Subject = *concise summary of what happened*
            - first line of `git commit` window
        2. Body = *more detailed explanation*
            - What is now different than before?
            - What's the reason for the change?
            - Is there anything to watch out for / anything particularly remarkable?

## Branching Conventions

### A Written Convention: Agree on a Branching Workflow in Your Team

1. Git allows you to create branches - but it doesn't tell you how to use them!
2. You need a written best practice of how work is ideally structured in your team - to avoid mistakes & collisions.
3. It highly depends on your team / team size, on your project, and how you handle releases.
4. It helps to onboard new team members ("this is how we work here").

### Integrating Changes & Structuring Releases

1. Mainline Development ("Always be Integrating")
    - few branches
    - relatively small commits
    - high-quality testing & QA standards
2. State, Release, and Feature Branches
    - Branches Enhance Structures & Workflows
        - different types of branches...
        - ...fulfill different types of jobs
        - main branch
            - develop branch
                - feature branches

### Long-Running Branches
- exist through the complete lifetime of the project
- often, they mirror "stages" in your dev life cycle
- common convention: no direct commits!
- main/develop branches

### Short-Lived "Feature" Branches
- for new features, bug fixes, refactors, experiments
- will be deleted after integration (merge/rebase)

### Branching Strategy: GitHub Flow
- very simple, very lean: only one long-running branch ("main") + feature branches

### Branching Strategy: GitFlow
- more structure, more rules
- long-running: "main" + "develop"
- short-lived: features, releases, hotfixes

## Pull Requests
- Communicating About and Reviewing Code
- Based on branches, not individual commits 
- Contributing Code to Other Repositories
    - creating a "Fork" of the original repository, where you can make changes
    - ...and suggest those changes to be included via a Pull Request!


## Merging Conflicts







