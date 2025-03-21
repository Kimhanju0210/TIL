# GitHub 연결하기


## GitHub와 Intellij 연결하기

### 1. 파일에서 Git bash
1-1. 새로 만근 파일에 우클릭

1-2. Git Bash 클릭

1-3. "git init" 명령어 입력

1-4. "git remote add origin add origin {repository URL}" 명령어 입력

-----

### 2. 프로젝트 추가
2-1. 파일로 가서 New project 클릭

2-2. 파일 경로를 Git 설정을 해두었던 파일로 지정
-----

### 3. Github로 commit하고 push하기
3-1. 상단에 Git 클릭

3-2. Git clone 선택

3-3. URL에 자신이 쓸 repository로 설정

3-4. 그 후, 수정사항 있을 시, Commit으로 통해 무엇을 추가했거나 수정했는지 입력

3-5. Push를 클릭

----

## GitHub와 VS code 연결하기
### 1. 파일에서 Git bash
1-1. 새로 만든 파일에서 우클릭

1-2. Git bash 클릭

1-3. "git init" 명령어 입력

1-4. "git remote add origin add origin {repository URL}" 명령어 입력


-----

### 2. 프로젝트 추가
2-1. VS code를 열어 소스제어 클릭

2-2. "리포지토리 복제" 클릭

2-3. 자신이 사용할 repository 주소를 입력

2-3. Git 설정을 해둔 파일로 경로 지정

------

### 3. 연결 및 Commit과 Push
3-1. 상단에 설정 클릭

3-2. 터미널 -> 새 터미널 클릭

3-3.  터미널에
```
$ git init
$ git add .
$ git status
$ gif commit -m "git convention + 명칭"
$ git remote add origin 자기주소
$ git push origin master
```
차례대로 입력

3-4. "소스제어" 클릭 후 변경사항에서 "+" 모양 클릭

3-5. 그 후 메시지 란에 Commit 내용 작성

3-6. "✓" 커밋 클릭

3-7. 화면 좌측 하단에 🔁 클릭 후 Push


### Git 명령어

## 1. git reset --soft HEAD~1
- 최근 커밋을 전단계로 돌려보내고 변경 사항은 유지한다.

## 2.  git clone [레포지토리 주소]
- 링크의 레포지토리를 해당 폴더에 클론을 만든다.

## 3. git checkout [브랜치명]
- 특정 브랜치로 이동하게 된다.

## 4. git diff
- 변경된 내용을 확인 가능하도록 만든다.

## 5. git reset --hard HEAD~1
- 최근 커밋을 취소하고 변경 사항도 삭제한다.

## 6. git revert [커밋 해시]
- 특정 커밋을 되돌리는 새로운 커밋 생성한다.

## 7. git fetch origin
- origin에서 최신 변경 사항을 로컬 저장소로 가져온다.

## 8. git stash
- 변경된 사항을 임시저장한다.

## 9. git stash pop
- 임시로 저장된 변경 사항을 다시 적용시킨다.