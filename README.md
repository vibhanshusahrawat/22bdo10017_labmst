# 22bdo10017_labmst
4. The task
You again live in your own branch, this time we will be doing a bit of juggling with branches, to show how lightweight branches are in git. Hint: git switch will make you switch from one branch to another.

1.	Use git branch to see the two branches that are relevant for this exercise
ans- git branch
2.	What branch are you on?
ans- git branch
3.	Use git branch mybranch to create a new branch called mybranch
ans- git branch / git checkout -b mybranch
4.	Use git branch again to see the new branch created.
ans- git branch
5.	Use git switch mybranch to switch to your new branch.
ans- git switch mybranch / git checkout <branch_name>
6.	How does the output from git status change when you switch between the master and the new branch that you have created?
ans-
7.	How does the workspace change when you change between the two branches?
ans-
8.	Make sure you are on your mybranch branch before you continue.
ans-
9.	Create a file called file1.txt with your name.
ans- echo"vibhanshu">mst1.txt
10.	Add the file and commit with this change.
ans- git add mst1.tst
     git commit -m"added mst1.txt with vibhanshu"
11.	Use git log --oneline --graph to see your branch pointing to the new commit.
ans- git log --oneline --graph
12.	Switch back to the branch called master.
ans- git switch master
13.	Use git log --oneline --graph and notice how the commit you made on the mybranch branch is missing on the master branch.
ans-
14.	Make a new file called file2.txt and commit that file.
  echo"content">mst1.txt

	![WhatsApp Image 2024-03-13 at 11 00 39_cc427794](https://github.com/vibhanshusahrawat/22bdo10017_labmst/assets/136055226/450949db-6e84-4ba5-b64a-392b6985acd2)


15.	Use git log --oneline --graph --all to see your branch pointing to the new commit, and that the two branches now have different commits on them.

16.	Switch to your branch mybranch.
ans- git switch mybranch

17.	What happened to your working directory? Can you see your file2.txt?
ans-
18.	Use git diff mybranch master to see the difference between the two branches.
ans- git diff mybranch master
![WhatsApp Image 2024-03-13 at 11 00 39_9e07cc76](https://github.com/vibhanshusahrawat/22bdo10017_labmst/assets/136055226/83a7c2dd-488f-45f1-b92b-2cefc5ad0456)


![WhatsApp Image 2024-03-13 at 11 00 39_9e07cc76](https://github.com/vibhanshusahrawat/22bdo10017_labmst/assets/136055226/b9ea2323-5b3c-420b-97e5-e73556c25d9d)



