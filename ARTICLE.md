## Interesting Article  
I found this article about [Git branching strategies](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) very useful.  
It explains how different branching models work in real-world projects, which connects well with what we are practicing in this assignment.  
I like how it shows when to use feature branches vs. hotfix branches, making it practical for team collaboration.  


# Part 1: Centralized Workflow

The centralized workflow is the simplest way to use Git. Everyone pushes directly to the same main branch in one central repository. It is easy to set up, but it can lead to conflicts when multiple people edit the same file at the same time. It works best for small projects.

---

# Part 2: Branch Workflow

The branch workflow is a more reliable approach for teamwork. Each developer creates a branch to work on a feature or fix. Work happens in isolation, and once the task is complete, a pull request is opened to merge the branch back into the main branch. This helps keep the main branch stable and allows teammates to review changes before integration.

---

# Part 3: Fork Workflow

The fork workflow is often used in open-source projects. Developers make a fork (copy) of the main repository under their own account, make changes there, and then submit a pull request to the original repository. This way, contributors do not need direct write access to the main project, which keeps it secure while allowing collaboration across many people.
