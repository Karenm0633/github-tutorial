# _Github Tutorial_

by Karen Morocho

---
## Git vs. GitHub
Git is a control system and keeps pictures of the code and helps you share or collaborate with other people, while Github is the host and provides Git.

---
## Initial Setup
1. If you wish to make a Github account you go to this website (www.github.com).
2. You can sign in with your HSTAT email, or if want you can be able to use your personal one. Follow the directions they want you to put in.
3. Therefore, you would be able to get started and make projects!

    
     **SSH KEY**
    *  Once you made your account go to (www.c9.io), login into your acoount. **Do not go to workspace yet**, you should see a settings icon, click on it
    * After you click on it, press on SSH Keys, copy the code that says 
        *  (Connect to your private git repository)
    *  Go to www.github.com and click on the settings icon 
        * Click on SSH and GPG keys
        * Then click on new SSH keys 
        * Once your there, it should appear (SSH Keys/add new)
        * Make a title that will help you remember like C9 or cloud 9
        * Paste the code you copied previously into the part that says (Key).
    * Go back to cloud9 
        *  Open c9 workspace 
        *  Type ssh -T git@github.com


---
## Repository Setup
1. When you start your repository go to your file and  do ```git init```, this will help you initialize your repository, then it will help you begin.
2. Once you initilized your repository you would want to use ```git add``` , so it can add the file to the staging area.
    * use ```git add . ```  or 
    * use ```git add filename.md```
3. After that, you can commit your file which would be ```git commit -m (the  meassage and how it was modified)```.

      **New Repo on Github**
     * Go to your www.github.com, on the top right corner there should be a plus sign (click on it).
     * Write the filename, **MAKE SURE THE FILENAMES ARE THE SAME**.
     * Click on _create repostitory_.
     * Once your there you should click on SSH towards the top.
     * now copy the last 2 lines that starts with ( or push ) ** Make sure you copy each line seperately**.
     * Paste it in your c9 file.
     
## Workflow & Commands
1. You want to check if any of your commits are being added into the staging area, you can use ```git status```.
2. If it's red it's because you didn't use ```git add```, once you do, you should use ```git commit -m (make a message to remind yourself the step you are going to do)```. 
3. Finally, you can use ```git status```  to check and it should be green. 
4. If you wish to push your project, the command will be ```git push```, this will help someone else look at your work through github.


---
## Rolling Back Changes 
If you want to take back something you did in the staging area, then look at the bullets below:
* **Undo edit:**
  *   Go to the file you want to undo the edit from.
  *   Then ```c9 FILENAME``` (Insert your file name).
  *   But once you go there and you see that you want to undo an edit, type in ```git status```.
  *   Once you type that, there should be 2 commands follow ```git checkout -- <file>``` (insert the file name that you wish to undo the edit).
* **Undo add:**
    *   If you added your command by accident, go to git status.
    *   Once your there you should use ```git reset HEAD <file>..``` (this appears on top when you use git status).
* **Undo Commit:**


  * You can use ``git reset --soft HEAD~1``.
  * If you want to uncommit an add you use ``git reset HEAD~1``.
  * If you want to uncommit an edit you use ```git reset HEAD~1```( this will take you back to the last commit).
  