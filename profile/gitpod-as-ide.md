## Using Gitpod as IDE

Since not all of us can access `npm` and other commands that require higher hardware requirements that the project requires, you can use [Gitpod][1] as your IDE

### Steps to work with Gitpod

1. Sign in via your GitHub account [here][1] 

2. Download the Chrome extension [here][2]

3. If you go to a repository page, you have now the `Gitpod` button beside the `Code` button on the header of the repository

4. Before you click the Gitpod button, copy the GitHub branch name provided in the Height App

5. Create a new branch with the branch name you just copied using the branch menu on Github

6. Work on your task. It is recommended to work on features little by little with commits in between

7. `git add` - Add all changes to a commit. 

8. `git commit -m "Message"` - CHECK THE CONVENTIONS FOR THE PROPER MESSAGE FORMAT [HERE](conventions.md)
   - Alternatively, you can use the Source Control extenstion (will have a number every time you change files after a commit) for both adding and committing

9.  Repeat Steps 6-8 

10. `git push` - Push all commits to remote branch

11. To push changes, you can create a pull request via the GitHub interface OR within Gitpod itself. Just login via GitHub on the workspace

12. Create a Pull request and fill in the information.

13. Choose the branch you are working on, on the right dropdown button. The layout should be `main <- [branch-name]`
    - This means that you are requesting the changes you added to your branch be merged with the stable code

14.  Follow the naming convention of the pull requests. CHECK FOR THE PROPER FORMAT OF PULL REQUESTS [HERE](conventions.md)
    
15.  ADD ME AS A REVIEWER IN YOUR PULL REQUEST!!! Pull requests will not be reviewed if they do not follow the naming convention.

16.  Wait for the reviewing process to be completed.

17.  Repeat Steps 4-16


[1]: https://www.gitpod.io
[2]: https://chrome.google.com/webstore/detail/gitpod-online-ide/dodmmooeoklaejobgleioelladacbeki
