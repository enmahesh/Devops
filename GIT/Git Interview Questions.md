
1. What is Version Control Systemss?

2. Why we need any Version Control System (VCS)

3. What is the difference between SVN and Git?

4. Which VCS you prefer? SVN Or Git? Why?

5. What are the advantages of Git over SVN?

6. Why we call Git as Distributed VCS?

7. Can you explain Git's End-to-End work flow?

8. How do you clone the code using git?

9. What is the difference between Commit & Push?

10. What is the difference between Push and Pull?

11. Can you explain Git architecture?

12. What is the difference between Centralized and Distributed VCS.

13. Have you ever created Remote repositories in Git? How?

14. What happens if I delete .git folder?

15. How do you configure username, email and editor first time in Git?

16. Where Git stores configuration details?

17. What is the advantage of STAGE in Git?

18. Git log options related questions

    --author

    --grep

    --oneline

    --since/until

    -n2

19. What is SHA-1? How Git uses this?

20. I have a file modified in my Working directory. How do you show the content diff?

21. How do you show the content diff of a file which is staged?

22. How do you delete and rename a file in Git?

23. What is your branching strategy? Can you explain your release process/Strategy?

24. What branching model you suggest for parallel development?

25. Developer fixes a bug. How do you take the change to production?

25. Explain different branching models that you have worked-on.

26. Did you work on merging the code in Git?

27. How do you merge the code in Git?

28. What is merge? What is conflict?

29. When do we get conflict?

30. What is fast-forward merge in Git?

31. What is the difference between Merge and Rebase?

32. How do you resolve the conflit in Git?

34. What kind of conflicts you have seen?

35. Who resolves the conflicts?

6. What is the difference between branch and tag? When do you create a branch and tag?

37. How do you create a branch and switch to that using single command?

38. What is HEAD pointer in Git? Where Git store HEAD info.

39. Can we store binary files in Git?

40. Can skip the staging? How? what are the caveats?

41. How do you list files/folders modified as part of a commit?

42. How do you ignore: ex:

    all files ending with .class

    all files having alphanumeric

    all log files but not build.log

43. How do you add ignore list for all users?

44. What are the different files you ignore in your project?

45. How to remove a committed change? Or can we remove?

        $ git reset --hard HEAD~1

        $ git reset --soft HEAD~1

46. How do you lock the branch?

47. How do you clone the code from a particular SHA?

48. How do you restore a deleted file? Or previous changes of

    a file?

49. How do you list the diff. of a file between two different

    branches.

        $ git diff dev_1.2.4...master -- LoginUser.java

50. How do you list the changes which are going to be fetched?

    method:1        

        $ git fetch    

        $ git log origin/master ^master

    method:2

        $ git fetch && git diff master origin/master --name-only

  

51. What is Git Stash?

52. How do you add a new remote to git? Or How do you attach your local repo with remote?

53. What is git ls-tree?

    git ls-tree <sha> --> Lists files committed as part of

    a commit.

54. How do you clone the repository with a single/particular branch?

    $ git clone -b dev_1.2.4 --single-branch https://github.com/nageshvkn/flipkart899.git

  

55. How to compare two branches?

$ git diff master..dev_1234 [compare local branches]

$ git diff origin/master..origin/dev_1234 [compare remote branches]

  

Qns:

1. How do you revert the code which is already committed in the repository?

2. User A has deleted the file in local repository. User B modified the same file and pushed to remote. Now, when user A push'es the file what will happen?

3. How do you make local repository as remote?

4. How do you push a new branch to remote repository?

5. How do you clone a single branch?

6. How do you search a commit based on time?

7. How do you clone a single folder / file? Or is it possible in Git? How do you list the changes which are fetched?

    $ git diff origin/master

8. How do you list the changes before pull/fetch?

    $ git checkout master                                                  

    $ git fetch                                        

    $ git diff origin/master

    $ git remote rm origin

    $ git remote add origin https://github.com/nageshvkn/jinglegurus.git

  

9. Push a particular commit to remote repository

    $ git push origin <hash>: master