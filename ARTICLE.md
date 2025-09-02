# Part 1: Centralized Workflow

The centralized workflow is the most basic way of using Git. Everyone pushes directly to the same main branch in a single repository. This makes setup simple, but it also increases the chances of conflicts if several people edit the same files at the same time. It works best for very small projects or teams.


# Part 2: Branch Workflow

The branch workflow is more advanced and widely used in real projects. Instead of pushing directly to the main branch, developers create a separate branch for each feature or bug fix. Work happens in isolation on the branch, and when the changes are complete, a pull request is opened to merge it back into the main branch. This keeps the main branch stable and makes it easier to review and test changes before integration.
