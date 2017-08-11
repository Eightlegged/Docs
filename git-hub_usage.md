## Git Repository 설정

1. git 다운로드

2.	github 홈페이지에서 Repository 생성

3.	... create a new repository on the command line 밑에 단락에 있는 Command 모두 복사

4.	git에 올리고자 하는 코드가 있는 폴더의 한 단계 상위 폴더로 이동
> ex)
> git에 올리고자 하는 코드가 있는 폴더 (C:\Users\Administrator\Documents\GitHub)
> 위의 경우에는 C:\Users\Administrator\Documents

5.	위의 예의 경우 GitHub 폴더를 선택(들어가지 않음) 한 후 오른쪽 마우스 클릭
6.	Dropdown 메뉴에서 Git Bash Here 선택 후 복사한 Command 붙여넣기
계정 정보를 요구하는 경우에는 GitHub 계정 입력(email/password)

## 이클립스 or STS에서의 Git 설정
1.	Window - Perspective - Open Perspective - Other... - Git 선택
2.	Add an existing local Git repository
> (이미 Github에서 개발중이던 코드를 가져오고 싶을 경우 Clone a Git Repository)
3.	앞에서 Commit 수행했던 폴더를 선택
4.	Perspective를 다시 Spring으로 돌린 후 Import - Maven- Existing Maven Projects
에서 git 설정했던 폴더 선택

## 코드 수정 후 업데이트 하고 싶을 떄
1.	프로젝트에서 오른쪽 마우스 Team - Commit
2.	Unstaged Changes에 있는 항목을 Staged Changes로 옮긴 후 Commit Message 입력
3.	Commit and Push
