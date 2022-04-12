##create new branch from master branch
git checkout -b <new_branch_of_a_branch>
git push origin <new_branch_of_a_branch>
##commit message to a push
git commit -m "msg"
##go to the <master_branch>
git checkout to <master_branch>
##to merge changes of the <new_branch> to the<master_branch>
git merge <new_branch_of_a_branch>

