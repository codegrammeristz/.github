## Github Workflow

1. Clone first the repository (copy the HTTPS link in the green "Code" button)
   - Use the command: `git clone [paste the https link]` and press enter

2. Before working at any given point, ALWAYS USE `git pull` to get all changes reflected in your copy of the repository 

3. Before working on a certain task, copy the GitHub branch name provided in the Height App

4. Create a new branch with the branch npame you just copied
   - Use the command: `git checkout -b [paste the branch name you copied]` in the cloned folder of the repo in your system

5. Work on your task. It is recommended to work on features little by little with commits in between

6. `git add` - Add all changes to a commit

7. `git commit -m "Message"` - CHECK THE CONVENTIONS FOR THE PROPER MESSAGE FORMAT!!!!!!

8. Repeat Steps 5-7

9. `git push` - Push all commits to remote branch

10. GO TO GITHUB REPOSITORY ONLINE

11. Go to pull requests and click "Create new Pull Request"

12. Choose the branch you are working on, on the right dropdown button. The layout should be `main <- [branch-name]`
    - This means that you are requesting the changes you added to your branch be merged with the stable code

13.  Follow the naming convention of the pull requests 
    
14.  ADD ME AS A REVIEWER IN YOUR PULL REQUEST!!! Pull requests will not be reviewed if they do not follow the naming convention.

15.  Wait for the reviewing process to be completed.

16.  Repeat Steps 3-15