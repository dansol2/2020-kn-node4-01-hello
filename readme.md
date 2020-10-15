#2020.10.30 노드수업
## 1. Visual Studio 다운로드 및 실행
## 2. node.js 설치
- [노드 사이트](http://nodejs.org)
## 3. git 설치
- [git-scm.com](http://git-scm.com)
## 4. github 가입
## 5. 본인의 컴퓨터에 git 사용자 등록
- cmd 창을 열고
```bash
git config -- global user.name 'dansol2'
git config -- global user.email 'na4rang22@naver.com'
```
## 6. 프로젝트 폴더를 만들고 vscode에서 연 다음, git을 설정한다.
```bash
git init
git remote add origin http://github.com/booldook/2020-kn-node4-01-hello.git
```

## 7. 터미널 창에서 다음과 같이 node프로젝트를 시작한다.
```bash
npm init -y
```
## 8. root에 package.json 파일이 생성되면 프로젝트 생성이 완료됨. 