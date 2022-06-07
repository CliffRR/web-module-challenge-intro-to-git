## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
2. What is the difference between Git and GitHub?
3. Why do we create a branch?
4. What is the purpose of a Pull Request?
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
7. What is a merge conflict?
8. How do you resolve a merge conflict?

Answers:
1. Open Source Distributed Version Control System

2. The difference is that github is a web-based Git repository hosting service. It has all the same features as git and a couple of its own features.

3. You create a branch to in order to maintain stability. You basically make a copy of the code and then make the changes needed on the copy. Finally you merge the changes afterwards to the original branch.

4. Pull requests tells others the changes you have made to a branch in a repository.

5. 'git checkout'

6. 'git fetch' pulls in all commmits from your remote but does not make any changes to your local files. 'git pull' immediately pulls in all the most up to date changes from the remote repository and upate the local repository. 'git merge' is used to combine two branches into one. This is what you would after all the changes are complete.

7. It is when Git cannot resolve the difference in code between two commits. In example would be when people make different changes to the same line to the same file.

8. The only way to resolve it is to open the code and make the edits needed.