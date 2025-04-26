# CS50P Workshop: Git and GitHub
Workshop for students taking CS50P at [Aryaloka](https://www.aryalokaeducation.com/courses/cs50x-python/) (CS50x Python at Aryaloka): basic Git usage on CLI and in VSCode and GitHub as preparation for the final project.

<p align="center">
<img src="img/intro.png" width="40%">
</p>

## Steps
**First step**: click the "Fork" button in the top right corner of the repo, to create your own version of this repo. Then you can use the below check-list to complete the tasks.

*Then in your own fork:* Check off the tasks below as you complete them by putting an `x` in the square brackets like `- [x]`:
- [ ] Create a new codespaces with VSCode for your repo
  * Click on the green **"<> Code"** dropdown button > select "Codespaces" tab > click the "Create codespace on main" button.

- [ ] Watch one of these lectures:
  * [CS50 Seminars 2023 - How To Use Git and GitHub](https://www.youtube.com/watch?v=cspx7YSvp5Q)
  * [CS50 An Introduction to Git and GitHub by Brian Yu](https://www.youtube.com/watch?v=MJUJ4wbFm_A)

- [ ] Practice Git commands: VSCode Source Control GUI
  - [ ] Change one file
    1. In your VSCode, switch to the Source Control view in the left sidebar (Ctrl+Shift+G)
    1. In your VSCode, edit the `README.md` file e.g. add a new line or check off a completed task.
       * Observe that the `README.md` file is marked as "changed" in the Source Control view.
    1. Click the **"+"** button next to the file to add this file to the staging area.
    1. Write a Message in the input field at the top e.g. "Updated README with completed tasks". Then press the "✔ Commit" button.
       * Observe that your new commit is now visible in the commit tree in the lower part of the Source Control sidebar.
    1. Press the "Sync Changes" button to push (upload) the changes to Github.com
    1. Go to your repository on Github.com `https://github.com/<your-github-username>/workshop-git-and-github`
       * Observe that your changes to your files are visible on GitHub.
       * Now press the **"Commits"** link below the green "<> Code"
         * Observe that your new commit is listed.
         * Click on the commit in the list to see the commit diff, the incremental changes did commit did.

  - [ ] Change several files
    1. Create a few new files with the `$ code <filename>` command.
    1. Repeat the steps from the previous task to create new commits, and observe how the staging area is changing, and new commits appear in the commit tree timeline.

- [ ] Practice Git commands: command-line (CLI) commands
  - [ ] First CLI commit
    1. In your VSCode, edit the `README.md` file e.g. add a new line or check off a completed task.
    2. Create a two new file like `$ code prog1.py prog2.py` and write something in them
    3. Observe changes files with `$ git status` and with `$ git diff`.
    4. Decide that you want to commit only the changes to the `README.md` file and the `prog1.py` file. Do so by adding it to the staging area with `$git add README.md prog1.py`.
    5. Commit the staged changes with `$ git commit -m "Update README and add prog1"`.
    6. Observe the updated commit history with `$ git log` or with included diff `$ git log -p`. Press the `q` to quit the log view.
    7. Push (upload) the new commits to the remote (GitHub) with `$git push origin`.
    8. Go to your repository on Github.com `https://github.com/<your-github-username>/workshop-git-and-github`
         * Observe that your changes to your files are visible on GitHub.
         * Now press the **"Commits"** link below the green "<> Code"
           * Observe that your new commit is listed.
           * Click on the commit in the list to see the commit diff, the incremental changes did commit did.

  - [ ] Second CLI commit
    1. Remember that you did not commit the new file `prog2.py` yet. Repeat the commands above to create a new commit that add this new file.           



# More CS50P Aryaloka Resources
* [erikw/cs50p-workshop-github-profile](https://github.com/erikw/cs50p-workshop-github-profile)
* [erikw/cs50p-workshop-git-and-github](https://github.com/erikw/cs50p-workshop-git-and-github)
* [erikw/cs50p-workshop-vscode](https://github.com/erikw/cs50p-workshop-vscode)
* [erikw/cs50p-lectures](https://github.com/erikw/cs50p-lectures)
