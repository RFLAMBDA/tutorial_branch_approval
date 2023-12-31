# tutorial_branch_approval

## Task 1: Make your own branch
For this task, you will learn to make your own branch!

To check what branches you have 

    git branch -v

You should see that you are on **main** branch with highlights on it

![image](./imgs/main_branch_init.png)

To create your own branch with your \[NAME\] and enter it

    git checkout -b [NAME]

Using following command again to double check if your branch is now changed to the new branch

    git branch -v

You should see something like this (example [NAME]: darlene)

![image](./imgs/new_branch_init.png)

## Task 2: Make the change on code

Now you are ready to make some changes on your code

First, make the designated change on your code following the instruction in *code.c*

![image](./imgs/code_piece.png)

Second, upload the code piece to your own branch following the add, commit and push sequence that we learnt before

    git add *
    git commit -am "updated by [NAME]"
    git push --set-upstream origin [NAME]

Finally, you should see this following text printed out on your terminal

![image](./imgs/code_upload_after_push.png)


## Task 3: Merge branch

Now your branch is all updated, you are ready to make a final update to main branch!

First, go back to your main branch by using the following command

    git checkout main

Then, make sure you are actually back by using

    git branch -v

![image](./imgs/main_branch_after.png)

Note: Try to do a simple *git pull* action now to make sure that your local main branch is still updated. If your local main branch is no longer the updated version, your following action will **FAIL** or getting very complicated!!!!

Now your are ready to merge!! You will perform a *pull* action on the main branch to your [NAME] branch

    git pull origin [NAME]

If there is no conflicts that needs to be resolved, you are good to go! Go ahead and make the commit and upload by add, commit and push!

    git add *
    git commit -am "merged by [NAME]"
    git push

You should now see the following print outs. It means you are ready to get someone to approve!

![image](./imgs/push_need_approval.png)

Ask your assigned person to approve your code! (The arrow means that you need to find the targeted person to ask for approval)

![image](./imgs/approval_list.png)

**The visualized tutorial is at the end of the page under "Pull Code from Github Repository page.pdf"**

We can also trace your approval history and comments to make sure all the tasks are done properly


## Task 4: Approve others

Don't forget to approve other people's code as well! Just click the button and write your comments. Your will need to approve **AT LEAST ONE** person in this team.

