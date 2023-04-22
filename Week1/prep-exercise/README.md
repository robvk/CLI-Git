# Animals repository

In this prep exercise you'll be working with GIT and GitHub. Follow the steps to learn how to create a remote repository and work with it from your local machine:

1. Create a repository on GitHub, called `animals`
1. Clone the repository to your local machine
1. On your computer inside that repository, create 3 Markdown files with 3 different animals. Each file should have:
   - A title with the name of the animal
   - An image of the animal
   - A short description of the animal (you can copy/paste it from wikipedia)
1. Make a README.md file that lists the 3 animals and has a link to them
1. Add and commit the files to the local repository. Make sure the commit message is meaningful (ex. "created files")
1. Push your commit to the remote repository, verify that it has worked on GitHub
1. Go back to your local repository and create a branch called `new-feature`

> Tip: in software, a "feature" is a technical term that points to any functionality that a user can derive benefit from. For example, Facebook has many features: the ability to make a profile, like a post, place comments, etc.

1. Inside the new branch, add another animal file with the same structure as in the previous section.
1. Update the README with the name and link to the new animal
1. Add and commit the file to the local repository. Again, make sure the commit message is meaningful
1. Push your commit to the remote repository, verify that it has worked on GitHub
1. On GitHub, find out how to merge branch `new-feature` into `main`
1. Merge the branches
1. Switch back to branch `main`
1. Pull the changes from your remote repository to your local repository, verify that everything worked

## Things to think about

- Why do you think we develop features in a branch rather than straight away pushed to `main`? Is there a situation that pushing to the `main` branch directly is better?
- What would happen if you create two different branches that edit the same file and then merge them after each other?
- Why do you think is the commit message important?

## IMPORTANT NOTE FOR TEACHERS

In the session, do something similar again, but then add forking and pull requests. Something along the lines of:

- Create a repository in the teacher's GitHub with a single README.md file
- Have everyone fork the repository
- In the forks, have the students create 1 animal README and add a link to it in the README.md file
- Have the students create a PR to the repo with their changes
- Merge everything together (hopefully there is a merge conflict, if not create one)
