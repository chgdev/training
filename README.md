# How does this work? How can I answer the training questions?
As you've probably guessed, you won't be answering the training questions and then pushing the answers back up to this repository. 

It would also suck to pull this repository down, answer some questions, but never get any updates to questions or topics.

To be able to do both of those things, you'll need to fork this repository, clone your fork to your local machine, push any changes to your fork, and merge any new changes from this repo into your local copy.

If you don't know how, let's take a look at how to do those things. This guide assumes that you are familiar with using git in the command line. If you are not take a look at the resources and training in the Git folder in the repository. If you are familiar with using git in the command line, proceed below:

## Create a Fork of This Repository
A fork of a repository is like a copy that is added to your local GitHub account. To create a fork of this repository, click the "Fork" button on the top right of the page. 

## Clone the Forked Repository Onto Your Local Machine
Now that you have a copy of this repo in your own GitHub account, clone your fork onto your machine. You'll know that you're cloning the right repository because your fork will have <YourUsername>/training as its title. Click on the green button on the right side of the page that says "Clone or download". 

You will see a modal that pops up giving you the option to clone your forked repository using HTTPS or SSH. If, you have SSH setup, feel free to use it to clone your forked repository. Either way you choose, use the clipboard icon to copy the link to your forked repository.

Next, think about where you'd like to clone your forked repository. If you've already cloned the original chgdev/training repository, you will need to clone your fork into another folder with a different name. Navigate to the location you want to clone your fork into using an open command prompt using the following:

`cd MY/TRAINING/PROJECT/REPO/DIRECTORY`

If you are using SSH to clone your repository, enter the command:
`git clone git@github.com:<YourUsernameGoesHere>/training.git <YourFolderNameGoesHere>`.

If you are using HTTPS, enter the command:
`git clone https://github.com/<YourUsernameGoesHere>/training.git <YourFolderNameGoesHere>`.

You should now have your forked repository cloned onto your local machine.

## Answering Questions and Pushing the Answers to Your Repo
From here on out, interact with your cloned forked repository in the same way you would with any other repository. Make changes your changes in the IDE of your choice, save, commit, and then push those changes to your local repository. You may answer the questions right on the README.md files of the topics you are working on, or create new folders and pages to add your answers and example problems to. You might want to copy the README.md that you are working on and paste it into a new filed called ANSWERS.md. Then you can commit and push your ANSWERS.md files to your repository. Maybe you want to supply a link to a CodePen, repl, or Code Sandbox as the answer to a question. It's up to you!

## Getting Changes
Eventually, you'll want to get updated questions and topics from the original chgdev/training repo and merge those into the forked copy of the repo on your local machine. To do that, use the following steps:

### Navigate to your local forked repo
Change the current working directory to that of your forked local project on your machine.

Using your command line, enter the following:
`cd MY/TRAINING/PROJECT/REPO/DIRECTORY`

### Add a remote to the original chgdev/training repository called "upstream"
Copy the clone link for the chgdev/traning repository. You can find this link using the green "Clone or download" button on the right side of the page of the original chgdev/training repository on GitHub. You may use the HTTPS or SSH link.

Next, open your command line tool of choice, and enter the following: 
`git remote add upstream <THE_CHGDEV/TRAINING_SSH_OR_HTTPS_LINK_YOU_COPIED>`

### Fetch the changes from the original chgdev/training repo
In your command line tool, enter the following:
`git fetch upstream`

### Checkout the master branch of your local forked repository
In your command line tool, enter the following:
`git checkout master`

### Merge the changes from the master branch of the original repository, chgdev/training, into the master branch of your local repository
In your command line tool, enter the following:
`git merge upstream/master`


## If you get stuck, take a look at the following resources:
- https://reflectoring.io/github-fork-and-pull/
- https://help.github.com/en/github/getting-started-with-github/fork-a-repo
- https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork
- https://blog.scottlowe.org/2015/01/27/using-fork-branch-git-workflow/
- https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow