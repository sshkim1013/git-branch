# git branch 명령어 정리

- 브랜치 확인
  - git branch 

- 브랜치 생성
  - git branch {브랜치명}

- 브랜치 전환
  - git checkout {브랜치명}
    - `checkout -b` : 생성하면서 전환
  - git switch {브랜치명}
    - `switch -c` : 생성하면서 전환

- 브랜치 삭제
  - git branch -d {브랜치명}

- 커밋 히스토리 확인
  - git log --oneline --graph
  - `--oneline` : 간소화해서 출력
  - `--graph` : 그래프 형태로 출력

- 병합
  - git merge {타겟 브랜치}
    - 현재 내가 있는 브랜치에 타켓 브랜치를 가져와서 병합

- test