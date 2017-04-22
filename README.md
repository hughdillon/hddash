# hddash

This project is supposed to help you learn Git, and how to use it with the code that we create.

1. CREATE A BRANCH. It's similar to an SVN branch, but it's not quite the same. It's so much easier to merge changes if you create a branch, but you won't realize that till step 6.
2. To create a branch, all you have to do is click Branch on GitHub and then start typing. Name it like this:
    hd-dev-feature
        This says: My initials = my branch, dev = development branch, feature = what it's working on.
3. Set GitHub to your branch, then clone the repo to your local hard drive.
    - Get the link from GitHub under clone this branch.
    - Open your command prompt to the folder location you want the branch.
    - Type: git clone https://github-repo-url-here yournewfoldername to place the github repo in the folder yournewfoldername.
    This gets the files down to your hard drive and tells your stuff that it's a git repo.
4. Change a file using a text editor. Understand the steps to commit code back to the repo.
    - If a file is unsaved in the text editor, it's not even on your disk yet. Push save in your text editor to save to disk.
    - Your local repo (the thing you cloned earlier) is now different from the files on your disk. You have two options:
        - You can use your local repo to reset your hard drive to the correct state. This blows away any changes you made to your files.
        - You can commit to your local repo, storing versioning information to save the state of your hard disk to your repo.
    - Let's say you chose commit, to save to your local repo.
        - Now, your local repo contains the change, but you didn't push it to the hosted repo, or GitHub.com. i.e. Your changes are still local-only.
        - Push the local repo to the branch that you cloned it from. Git will take care of that, you just have to run push.
    - If you pushed, your repo is now on your branch in GitHub.
5. Let's say you've got all of your changes in GitHub on your branch. You need to create a Pull Request to ask the owner of the master branch to bring 
    your changes into the master branch. The master branch owner will delete your branch when it is merged into the master from the PR.