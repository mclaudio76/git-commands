# Git Commands (and recipes)
A list of useful git commands

### 1. Publish an existing spring project on GitHub
- First, create on GitHub a new repository for the project.
- After doing that,  in the root folder of the project type
   ``` git init ```
- Copy in the root folder of the project the README and LICENSE files (if you want to)
- Add a proper .gitgnore file
- Execute : ```git remote add origin <remote-url> ```
- Execute : ```git commit -m 'First Commit' ```
- To push the content of the local project to the remote repo, issue:
  ``` git push --set-upstream origin master ```


