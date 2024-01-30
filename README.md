# training_github_pages
Graduate training - git, VS Code, terminal and basic web page building with Github Pages

## Learning Objectives

- Learn how to use git and Github
- Learn how to use VS Code
- Learn how to use the terminal
- Learn how to build a basic web page with Github Pages

## Prerequisites

- Create a [Github account](https://github.com/)
- Xcode command line tools - `xcode-select --install`
- Install [homebrew](https://brew.sh/) using `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
- Install [VS Code](https://code.visualstudio.com/) via homebrew using `brew install --cask visual-studio-code`

# Tutorial

## Forking the repository
- Fork this repository to your own Github account
- Clone your forked repository to your local machine using `git clone`
  - Think about where you want to clone the repository to on your local machine and consider using the `.` operator
- Open the repository in VS Code using `code .`
- Open the terminal in VS Code using (on Windows) `Ctrl + Shift + ` or (on Mac) `Cmd + Shift + `

## Creating a new branch

You now have a copy of this repository on your local machine. You can now create a new branch to work on.

- Create a new branch using `git branch <branch_name>`
- Checkout the new branch using `git checkout <branch_name>`
- Push the new branch to your forked repository using `git push --set-upstream origin <branch_name>`
- In your VS Code terminal, you should now see that you are on your new branch
  - Also check the bottom left of the VS Code window to see that you are on your new branch `<branch_name>`

## Making changes

You will make changes on the new branch you have created. You will then commit and push these changes to your forked repository.

Making changes on a new branch is good practice as it means you can work on multiple features at the same time without affecting the `main` branch.

- Open the `README.md` file in VS Code
  - Alternatively, open the `README.md` file in preview mode in VS Code for a more readable view
- Update the areas in the `index.html` file that are marked with `TODO` comments
- Make edits to `style.css` to change the styling of the page marked with `TODO` comments
- Make changes to other styles in `style.css` to change the styling of the page (optional)
- Once you've made changes, stage the changes using `git add .`
- Commit the changes using `git commit -m "<commit_message>"`
  - Edit the <commit_message> to be a short description of the changes you have made
  - Best practice is to use the present tense in your commit message
- Push the changes to your forked repository using `git push origin <branch_name>`

Your changes should be on the github repository you forked on your account on the new branch you created.

## Creating a pull request

You will now create a pull request to merge your changes from your new branch into the `main` branch. This is standard practice when working on a project with multiple people.

- Go to your forked repository on Github
- Click on the `Pull requests` tab
- Click on the green `New pull request` button
- Select the `main` branch as the base branch
- Select your new branch as the compare branch

Here you will see the changes you have made on your new branch compared to the `main` branch. You can review the changes you have made and add comments if you wish.

- Add a title and description for your pull request
- Click on the green `Create pull request` button
- Wait for the pull request action to complete
