# git-guide
깃 명령어
## 과정
작업트리 -> 스테이지 -> 저장소
* 작업트리: 파일 수정 및 저장, 우리 눈에 보이는 디렉토리
  
* 스테이지: 버전을 만들 파일을 대기하는 곳, 눈에 안 보임
  
* 저장소: 스테이지에 있던 대기 파일을 커밋하여서 저장, 눈에 안 보임

## 명령어
* git status: 저장소의 상태 확인
  
* git log: 지금까지의 저장소의 히스토리를 확인
  
| Command | Description |
| --- | --- |
| -n | n개의 히스토리만 출력 |
| -p | 각 커밋의 다른 결과를 출력 |
| -p -2 | 최근 2개의 다른 결과를 출력 |
| -all | 모든 히스토리를 출력 |

* git init: 저장소 생성
  
* git add: 작업트리 -> 스테이지
  
* git commmit -m "message": 버전 생성, 커밋을 하면서 메시지를 함께 기록

* git diff: 현재 작업 디렉토리의 마지막 커밋과 차이점을 비교
* git diff <commit#1> <commit#2>: 두 커밋의 차이점을 비교

* git checkout <commit>: 해당 버전으로 파일 되돌리기
  + git log --all: 이후 버전 확인 가능

## Branch
### 생성
* git init: 해당 폴더에 .git 파일 생성

* git remote add origin [github 주소]: github 주소와 연결

* git branch [브랜치명]: 브랜치 생성

* git branch -b [브랜치명]: 브랜치를 생성하고 해당 브랜치로 이동

### 이동
* git checkout [브랜치명]: 해당 브랜치로 이동

* git branch: 현재 브랜치 확인


  
