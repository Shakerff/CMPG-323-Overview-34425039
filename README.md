# CMPG-323-Overview-34425039
* For Project 1 (Agile & Scrum),  a repository named CMPG 323 Overview will be created. This repository will be used to track and monitor the progress of other projects
* For Project 2 (API Development), a repository named CMPG 323 Project 2 will be created
* For Project 3 (Standards & Patterns), a repository named (CMPG 323 Project 3) will be created
* For Project 4 (Testing & RPA), a repository named (CMPG 323 Project 4) will be created
* For Project 5 (Reporting & Monitoring), a repository named (CMPG 323 Project 5) will be created

![image](https://user-images.githubusercontent.com/91734031/185284256-59617106-ee9e-47ad-af3b-f451665f3978.png)

# Branching Strategies
I will make use of GitFlow strategy for each project because it offers a detailed structure with a few clearly defined branches. 
This strategy will allow me to use each type of branch for parallel processing and provide quality assurance for all the projects.

![20180412-git-flow](https://user-images.githubusercontent.com/91734031/185289019-a240ffb3-9802-4b65-b713-dae948b60e9f.png)

* Master Branch - I will deploy my code in the master branch, which I will eventually merge with all other code branches into.

* Development Branch - Before eventually merging the development branch with the master, I will first integrate all of the features and modifications into the development branch. Consider it to be a master branch that is virtually "pre-production." This branch will give rise to the feature and release branches.

* Feature Branch - I will create new features on feature branches, one branch for each feature. With the help of these branches, it is simple to track versioning at a more granular level and to have different teams or engineers working on distinct features simultaneously.

* Release Branch - This branch will only be used for release-related tasks including QA, bug fixes, and documentation. I will merge with the master branch when the release is prepared, and then deploy from there.

* Hotfix Branch - I will utilise hotfix branches to only patch production code. To swiftly resolve issues and test the patches without immediately affecting production code (until it's ready to merge), I will isolate problematic code from the master branch.

# gitignore
* In order to instruct Git which files and directories to ignore when I make a commit, I will create a.gitignore file in the root directory of each repository. I will also Commit the .gitignore file to each repository to make the ignore rules available to anyone that clone the repository.
