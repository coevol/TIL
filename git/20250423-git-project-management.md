[Co-work with git, github]

Issue template

기능, 질문, 버그리포트에 대한 다른 양식 지정하기

## Description

한 줄로 추가할 기능 설명

디테일하게 다시 설명(사진 영상 등 자유롭게 추가 가능)

## Tasks

- [ ] Item 1
      
- [ ] Item 2
      
- [ ] Item 3
      
## References

- [Link text](Link addr)


Issue Labels

https://medium.com/@dave_lunny/sane-github-labels-c5d2e6004b63

• Issue의 상태와 종류, 긴급도 등을 표시하기 위함

• Jira 등의 도구를 사용한다면 Label이 필요하지 않을 수도 있음

• Type: Bug, Enhancement, Maintenance, Question

• Priority: Urgent, High, Medium, Low

• Status: Available, In Progress, Pending, On Hold, Review Needed, Abandonded, Completed, Accepted, Blocked, Revision Needed


Milestone

• 작성된 Issue가 프로젝트의 어떤 주기에서 해결되어야 하는지를 표기

• Milestone 작성을 통해 해당 Sprint의 달성률과 남은 Issue 파악이 쉬워짐


--------------------------------------------------


[projects Version management]

• github에서 repo issue 기반의 task management

• Scrum board와 table의 방식 존재

• 팀의 Admin만 관리 가능(관리자가 관리하는 것이 맞음!!)

• commit, pull request 등을 통해 자동으로 움직이도록 관리할 수 있음



--------------------------------------------------

[wiki record]

• repository에서 README.md 에서 더 자세히 설명할 부분이 있을 경우 작성

• 따로 사이트를 만들지 않더라도 해당 프로젝트에 대한 FAQ, Docs 처리 가능

• 프로젝트 중 문서화가 필요한 모든 것들을 담아놓는 공간

• https://github.com/TeamCooks/TwoSpoon/wiki

• Daily Scrum

• Sprint Retrospection(Liked, Learned, Lacked)

• Code Convention

• Technical Issues


--------------------------------------------------

[pull request]

PR template

일관성 있는 요청을 위한 필수요소


‘.github/PULL_REQUEST_TEMPLATE.md’

## Summary

한 줄로 해당 작업사항에 대한 설명

디테일하게 다시 설명(사진 영상 등 자유롭게 추가 가능)

## Proposed Changes

- 작업사항(close #{issue_num})
  
- 작업사항(fixed #{issue_num})
  
- 작업사항(resolves #{issue_num})
  
## To Reviewers

- Code review시 참고할 사항

--------------------------------------------------


[github flow with fork]

팀장의 remote repo

	> Fork to 팀원의 remote repo  >  Clone to 팀원의 local repo
 
	> Fork to 팀원의 remote repo  >  Clone to 팀원의 local repo
 
	> Fork to 팀원의 remote repo  >  Clone to 팀원의 local repo
 
		. . .
  
	> Fork to 팀원의 remote repo  >  Clone to 팀원의 local repo



Create a new repo

새 Organization에서 새 repo 만들기


clone

clone 하여 작업한 뒤 대상 파일 push 하기


Create an issue

팀원은 새로 만든 repo에서 issue 만들면서 작업사항 정리하기


fork and clone

팀장의 작업 시작 지시에 맞춰 fork 하고 clone 하기


clone and work

각자의 컴퓨터에 fork한 나의 repo를 clone 하기


set upstream

다른 사람의 작업사항을 쉽게 받기 위한 upstream 설정하기


Assignees and Labels

팀원이 작업하는 동안 팀장은 issue, projects 세팅하기


작업중 . .


push to forked repo

작업사항을 나의 repo에 push


Open Pull Request

팀 repo에 작업사항을 전달하기 위한 PR 열기


Comparing . .


PR 내용 작성한 뒤 Create

https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword


Code Review

팀장은 생성된 PR에 대해 code review를 실시


추가 작업사항 처리하기

팀원은 code review 결과 추가 작업사항을 열려있는 branch에서 작업하기


And Then, Push to forked repo

추가 작업사항을 나의 PR이 열려있는 branch로 push


추가 작업사항 반영 확인

나에게 push하면 자동으로 연결됨 ㅇㅇ


재검토

팀장은 추가 작업사항에 대해 재검토 후 Approve 로 최종 승인


Now Ready to merge

merge는 팀장만 수행


결과물 확인

Don’t Panic

팀원이 local에 팀 repo의 최신사항을 반영하지 않았을 때 발생

일단 PR을 생성하고,

conflict 발생 확인 후,

local에서 처리해 update 하기

내 PR의 최신사항 update 완료


--------------------------------------------------

[Final Project]

• 팀을 이뤄 프로젝트를 수행

• Organization을 만들고 수행할 것

• 필수과제 fizzbuzz + 선택과제 : 과제별 개별 repo에서 진행

1. 100 Prisoners Problem(https://rosettacode.org/wiki/100_prisoners#Python)
   
- 100000회 시행시 성공 확률 출력
  
2. Pig Dice Game(https://www.mathsweek.ie/2023/games/pig.html)
  
- 그래픽 없이 문자로 게임 진행상황을 출력하는 CLI 방식으로 구현
  
3. Monty Hall Problem Simulation(https://rosettacode.org/wiki/
  
Monty_Hall_problem#Python)

- 100000회 시행 시 문을 바꾸었을 때, 유지했을 때의 각 성공 횟수 출력

