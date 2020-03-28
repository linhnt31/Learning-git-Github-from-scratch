### Git flow and senario
**1. Senario**
> If you are working in one project that has many features
> We do not commits and push to ***master*** but create a **new branch**. Then, we review *commit* and ***merge*** them together.

![](https://gitbookdown.site/img/git_branch_merge.png)
___
2. **Commands**
* ***git branch***: creates a new branch
![](https://github.com/viendanbac/Learning-git-Github-from-scratch/blob/master/Images/branch.png)
* ***git checkout***: switchs branchs
![](https://github.com/viendanbac/Learning-git-Github-from-scratch/blob/master/Images/check-out.png)
> To make it faster, we can combine 2 commands **branch** and **checkout** by: ***git checkout -b name_branch***
![](https://github.com/viendanbac/Learning-git-Github-from-scratch/blob/master/Images/pull-request.png)
* ***git merge***: merges branchs together.
![](https://github.com/viendanbac/Learning-git-Github-from-scratch/blob/master/Images/merge.png)
> But in real project, we will not merge code changes straightway. To:
> 1. Review before merge.
> 2. Make **commits** more concise.
> ***Solution***: **pull request**
