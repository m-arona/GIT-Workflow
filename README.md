# GIT-Workflow
CASE STUDY - GIT WORKFLOW
You work as a Devops Architect in Zendriix Softwares. The company has been struggling to
manage their product releases. The releases should happen on 25th of every month. Suggest a
Git Workflow Architecture for this requirement.
Simulate this workflow, by creating a pseudo code files and branches, and upload the same to
your GitHub Account.
As a part of solution, share the link to your GitHub repository.

Solution:
I would suggest using the GitFlow Workflow with the following branches: main, dev and feature branches.

Here’s the summary of my workflow:
Initial Release (Release 1)
1.)	In master, create the initial code for Product1 (produc1.c)
2.)	Create the dev branch; and under the dev branch, create the feature branches (feature1. feature2)
3.)	Modify the code in the feature branches, 
4.)	Merge features with dev, resolve any conflicts
5.)	Merge dev with master – Release 1

Security patch in between releases:  modify code in dev, commit and merge with master 

Succeeding Releases 
6.)	For new products, create the initial code in dev; add additional branches if needed
7.)	In feature branches, rebase/pull codes as needed
8.)	Modify the code(s) in the feature branches, 
9.)	Merge features with dev, resolve any conflicts
10.)	Merge dev with master – Release x
