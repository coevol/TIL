[GIT BRANCH Commands]

임시 저장소 보관

$ git stash or $ git stash save “{message}”


임시 저장했던 작업을 복구(index: stash number)

$ git stash pop or $ git stash pop {index} or $ git stash apply


임시 저장했던 작업 리스트 확인

$ git stash list 


{index}번째 작업 삭제

$ git stash drop {index}


git clone UPSTREAM_URL

git fetch upstream main

git merge FETCH_HEAD


Rename

$ mv a.md to b.md


Undo

$ git restore {filename} or .(whole changes)


Unstaging

$ git reset HEAD {filename}


Edit commit message

$ git commit --amend


Edit commit message

$ git rebase -i <commit>

$ git rebase --continue (rebase 취소: git rebase --abort)


Reset commit

$ git reset --hard HEAD~{nums of commit}

$ git push -f origin <branch>

- {nums of commit}개의 커밋을 삭제 후 remote <branch>에 강제 push
  
- 협업 시에는 나의 local과 clone한 remote repo에서 지워졌다고 해도 다른 곳에 남아있던 이력으로 인해 살아나거나, 충돌이 발생함


Revert commit

$ git revert --no-commit HEAD~{nums of commit}..

$ git commit

$ git push origin <branch>

- {nums of commit}개의 커밋을 되돌린 후 remote <branch>에 push
  
- 잘못하기 직전 시점으로 되돌리고 해당 되돌림의 이력을 팀원들에게 전달하여 어떤 문제가 있었고, 어떻게 수행되는지에 대해 뚜렷한 설명 가능
  
- commit을 따로 하지 않을 땐 ‘—no-edit’
  
- merge commit을 되돌릴 땐 ‘-m’
  
(ex) $ git revert -m {1 or 2} {merge commit id})



