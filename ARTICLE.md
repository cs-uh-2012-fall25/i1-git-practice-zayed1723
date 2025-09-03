# Interesting Article

I came across this article about [Git branching strategies](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow), and I found it really interesting.  
It explains the different ways developers use branches when working in teams. What stood out to me is how each strategy is useful depending on the project size.  
For example, feature branches make it easier to separate work, while hotfix branches are for quick fixes without messing up the main project.  
I liked it because it connects to what we’re learning and shows how Git is actually used in real projects, not just in theory.  

---

# Part 1: Centralized Workflow

In the centralized workflow, everyone pushes changes straight to the main branch of one shared repo.  
It’s simple and easy to understand, which makes it good for small projects.  
The downside is that if more than one person is editing the same file, you can run into conflicts.  

---

# Part 2: Branch Workflow

The branch workflow is more organized. Instead of working directly on the main branch, each developer creates a new branch for their work.  
This keeps things separate until the feature or fix is done. After that, the branch is merged back into main with a pull request.  
It helps keep the main branch stable and also gives others a chance to check your work before it gets added.  

---

# Part 3: Fork Workflow

The fork workflow is common in open-source projects. You make a fork of the repo under your own GitHub account, then clone it and do your work there.  
When you’re done, you send a pull request to the original repo asking them to include your changes.  
This way, anyone can contribute without needing direct write access, and the original project stays safe while still allowing collaboration.  
