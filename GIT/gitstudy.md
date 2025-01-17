# CMD 명령어 정리

- 커널 기록 삭제 : clear / ctrl + l
- 습관적으로 ls 입력하는 습관 들이기 (ls-list segment 기억하자)
- 삭제 명령어 : rm (휴지통에 삭제 내역 반영되지 않으니 주의)
  - 디렉토리 삭제 명령어 옵션 : rm -r <dir name>
- 현재 경로 확인 : pwd

** CLI는 항상 경로를 알고 있어야 한다  **
- 절대경로 : Root부터 목적까지 모든 경로
- 상대경로 : 현재 디렉토리 기준 상대적 위치 (서버의 경로 등 보안이 필요한 경우)

# GIT Bash 명령어 정리

- git status : 현재 상태 확인
- git init : git 활성화, 현재 디렉토리를 Working Directory로
- git log : git Commit Log 보기
  - git log --oneline : 한줄로 보기, 해시값 표시

## Commit 및 Push
1. git add : Working Directory에서 Staging Area로 Commit할 파일 올리기
   - git add . : 현재 디렉토리의 모든 파일을 add
   - git restore --staged : 특정 파일 스테이지에서 제외
2. git commit -m "message" : Local Repo에 파일 Commit
3. git push <Remote Repo 별칭> master : Remote Repo에 파일 Push
