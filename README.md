# _GitHub Tutorial_

by Karen Morocho

---
## Git vs. GitHub
Git is a control system while Github is the host and provides Git.

---
## Initial Setup
1. If you wish to make a Github account you go to this website (www.github.com)
2. You can sign in with your HSTAT email, or if want you can be able to use your personal one. Follow the directions they want you put in.
3. Therefore, you would be able to get started 
    
     **SSH KEY**
    *  If you 


---
## Repository Setup
1. When you start your repository go to your file and  do ```git init```, this will help you initialze the your repository, it will help you begin
2. Once you initilized your repository you would want to use ```git add``` , so it can be add the file to the staging area
3. After that, you can commit your file which would be ```git commit -m (the  meassage and how it was modified)```
4. 

---
## Workflow & Commands
1. You want to check if any of your commits are being added into the staging area, you can use ```git status```.
2. If its red it's because you didn't use ```git add```, after that you should use ```git commit -m (make a message to remind yourself the step you are going to do)```. 
3. Finally, you can use ```git status```  to check and it should be green. 
4. If you wish to push your project the command will be ```git push```, this will help someone else look at your work through github.


---
## Rolling Back Changes 
If you want to take back something you did in the staging area, then look at the bullets below:
* **Undo edit:**
  *   Go to the file you want to undo the edit from 
  *   Then ```c9 FILENAME``` (Instert your file name)
  *   But once you go there and you see that you want to undo an edit you go to ```git status```
  *   Once you type that there should be 2 comands follow ```git checkout -- <file>``` (insert the file name that you wish to undo the edit)
* **Undo add:**
    *   If you added your command by accident, go to git status 
    *   Once your there you should use ```git reset HEAD <file>..``` (this appears on top when you use git status)
* **Undo Commit:**
  * This one's alittle too complicated
  * You can use ``git reset --soft HEAD~1``
  * If you want to uncommit an add you use ``git reset HEAD~1``
  * If you want to uncommit 