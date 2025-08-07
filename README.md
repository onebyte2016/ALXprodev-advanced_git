# ALXprodev-advanced_git
0. Setting up gitflow
mandatory
Objective: Understand and initialize a GitFlow workflow

Instructions:

Install git-flow if not already installed. Steps here

Create an empty repository ALXprodev-advanced_git

Clone your repository to have it available locally.

Create a branch develop

Push the develop branch to the remote repository

Initialize Git Flow within the repository using default settings i.e git-flow init [-d]

Create an empty README.md file

Commit your file to staging and Push


## 1. Creating a feature branch
mandatory
Objective: Learn how to work with feature branches in GitFlow.

Instructions:

Create a new feature branch feature/implement-login from the develop branch

In the feature/implement-login create a new directory called login-page, inside it create a README.md file with the message: Login Feature Coming soon

Commit your changes and push to github

Use commit message feat: scaffolding login page

Repo:

GitHub repository: ALXprodev-advanced_git
Directory: login-page
File: README.md



## 2. Creating a Release Branch
mandatory
Objective: Understand the release process in GitFlow.

Instructions:

Create a new feature branch feature/implement-signup from the develop branch and create a directory called signup-page with a README.md file with the message feature coming soon

Commit the changes and push to github

Merge the 2 branches to the develop branch. Fix conflicts if any

Create a new release branch release/1.0.0

Make changes to signup/README.md file by adding the following text:” data requirements: email, firstName, lastName, profilePic]” inside the release branch

Commit and push changes to github then merge the release branch to the main branch and the develop branch

Tag the release with v1.0.0 and push the tags to the remote repository

Repo:

GitHub repository: ALXprodev-advanced_git
Directory: login-page, signup-page
File: `login-page/README.md, signup-page/README.md`