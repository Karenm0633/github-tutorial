# _GitHub Tutorial_

by Karen Morocho

---
## Git vs. GitHub
Git is a control system while Github is the host and provides Git.

---
## Initial Setup
1. If you wish to make a Github account you go to the website www.github.com
2. You can sign in with your HSTAT email, or if want you can be able to use your personal one. Follow the directions they want you put in.
3. Therefore, you would be able to get started 


---
## Repository Setup



---
## Workflow & Commands
1. You want to check if any of your commits are being added into the staging area, you can use ```git status```.
2. If its red its because you didnt use ```git add```, after that you should use ```git commit -m (make a message to remind yourself the step you are going to do)```. 
3. Finally, you can use ```git status```  to check and it should be green. 
4. If you wish to push your project the command will be ```git push```, this will help someone else look at your work through github.


---
## Rolling Back Changes 
If you want to take back something you did in the staging area, then look at the bullets below:
* Undo edit:
  *   Go to the file you want to undo the edit from 
  *   Then ```c9 FILENAME``` (Instert your file name)
  *   But once you go there and you see that you want to undo an edit you go to ```git status```
  *   Once you type that there should be 2 comands follow ```git checkout -- <file>``` insert the file name
* Undo add:
    *   