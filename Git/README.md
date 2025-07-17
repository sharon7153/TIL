# Git
- git init
: git 저장소로 초기화 (*프로젝트 진행 시 한번만 수행 *)
- git add <파일명>
: git에 추가할 준비 (staging area로 이동)
- git commit -m <메시지>
: staging에 있는 내용을 기록
- git status :  현재 변경 사항 내역 + staging area 표시
    
- git log : 현재까지 변경 내역 확인 
    
- git config --global -l
:  user email, user name 확인
- git commit --amend
    
    : vim 에서 commit message 수정
    
    : 파일 하나를 같이 commit 하지 못했을 경우, git add 그리고 git commit --amend 실행하여 직전 commit에 포함시킴
    
- git commit --amend -m <메시지>
    
    : 메시지 동시에 명령어와 작성
    
- git remote add origin <url>
    
    : remote respiratory 설정 
    
- git push -u origin master
    
    : -u의 의미 ⇒ 처음에 설정하면, 그 이후에 git push 만 써도 가능
    
- gitignore
    
    : Git에서 특정 파일이나 디렉토리를 추적하지 않도록 설정하는 데 사용되는 텍스트 파일
    
    : https://www.toptal.com/developers/gitignore/
    
    → 해당 링크를 통해 gitignore 작성에 필요한 것을 알 수 있음