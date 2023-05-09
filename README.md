# git project 업로드 하기 

## README.md 파일 만들기
* sublime text 도구를 사용 할 수 있고 
* git bash shell 에서 : `touch README.md` 라는 명령으로 생성
* git에 project 를 `push(Upload)` 했을때 안내 메시지 등을 보여주는 파일
* mark down 문법을 사용하여 간단한 문서를 작성 하기 

## local folder 를 local Repository 생성하기
* bash shell `git init` 명령으로 생성하기 
* `.git ` 폴더를 생성하는 명령이다 

## `.git ` 폴더
* project 폴더에 작성된 여러 파일들을 압축하여 원격 Repository 에 push 하기 위해 준비 된 폴더 
* git 에  push 할때 사용하는 여러 정보들을 보관 하는 폴더 

## 원격 Repository  생성하기 
* `https://github.com` 로그인후 생성하기 
* `git remote add origin https://github.com/KANGYUEUN/New-project.git` 복사 
*  bash shell 에서 `shift + insert` 입력해서 붙여 넣기 

## `.gitignore` 생성하기
* `.gitignore` 파일은 원격 github 에 업로드 되지 않아야할 파일 정보등록 하기 



* 로컬폴더 파일을 압축하여 .git 폴더에 저장하기 