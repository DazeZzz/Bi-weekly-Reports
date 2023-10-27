# Bi-Weekly Reports
This is a place where I keep the bi-weekly reports of my lab team.\
This repository has **six** branches, corresponding to the **six** members of may lab team. Each member's branch is named after the `Chinese pinyin` of his name, and everyone's report is stored on their own branch.

### To my teammates
You need to put your report on the branch associated with your name every two weeks. You can write your report locally and use `Git` to push it to your own branch. The form is not specified, but `Markdown` is recommended because it's really convenient and easy to read and write, and `Github` supports it well.\
For push your report from locally, you should add this remote repository to your local `Git` repository by running the following command:
```
git remote add origin https://github.com/DazeZzz/Bi-weekly-Reports.git
```

If you want to push your report, you should run:
```
git push origin *local_branch_name*:*remote_branch_name*
```
In the command above, `*local_branch_name*` is your local `Git` branch name(usually `master`), and `*remote_branch_name*` is the branch name associated with you in this repository. You should replace them in actual use. **Please carefully check that the spelling of `*remote_branch_name*` is correct, because if you enter an incorrect branch name, a new branch will be created in this repository, which will cause branch confusion!**\
In order to minimize the danger of entering the wrong branch name, I **strongly** suggest that you set your branch here as the upstream branch of your local branch. But first you need to create a local branch with the same name as the remote branch. You can run:
```
//Create a local branch with the same name as the remote branch.
git branch *remote_branch_name*

//Switch to the new branch.
git switch *remote_branch_name*

//Set the upstream branch for the new branch.
git branch --set-upstream-to=*remote_branch_name*
```
After setting the upstream branch, you can push your report without entering the remote branch name, just simply like this:
```
git push
```
That's all about how to push your report ,and if you have any questions or suggestions, feel free to contact me.

### Dos and Don'ts
* You **should** put your report in your **own** branch.
* You **shouldn't** make any changes on other people's branches other than reading.

### Todo
- [ ] Submit your report
