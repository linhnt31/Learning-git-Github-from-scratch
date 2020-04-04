### Origin
___
##### 1. Local Version Control System (VCS)
-First, developers have built ***local VCS*** that contains a ***simple database*** to stores all changes.
![](https://viblo.asia/uploads/611c2af8-2b1b-4070-a7a1-0675b3ef80e1.png)
> But, this model can't still resolve how to connect/exchange codes of developers together.
##### 2. Centralized Version Control System (CVCS)
![](https://miro.medium.com/max/1400/1*GgaGcwh5L246YcU5NVDA5A.png)
-This model comprises ***a server*** that stores entire projects. Programmers can work (commit, pull, update,...) on that server.
-Example: SVN, Perforce.
> But, in the case the server goes down - we could not make a backup ---> we may lose all data.
> Or, if we could not connect to network ---> we also can not use our repo on server.
##### 3, Distributed Version Control System.
![](https://miro.medium.com/max/1400/1*CEyiDu_mQ5u9NI0Fr2pSdA.png)
-In this model, every developer ***clones*** a copy of repo and has ***full history*** of the project on their hardware.
Example: Git, Mercurial,...
___
### Git
___
![](https://git-scm.com/images/about/index1@2x.png)
##### 1. Staging area
-This is ***an intermediate area*** where commits can be formatted and reviewed ***before completing the commit.***
-Each file in git are managed based-on 3 conditions: ***modified***, ***staged***, ***commit***
___
### References
[git-about](https://git-scm.com/about)

[Vietnamese tutorial](https://viblo.asia/p/git-hoc-nghiem-tuc-mot-lan-phan-1-OeVKBo6JZkW)

[Centralized and Distributed VCS](https://medium.com/faun/centralized-vs-distributed-version-control-systems-a135091299f0)
