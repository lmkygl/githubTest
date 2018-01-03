
# git 실행 및 연결 
#### Visual Studio Code > ctrl+shift+C (cmd창 열림)

>  명령어 순서 
* git init
* git add "파일명"
* git commit -m "커밋할 메세지"
* git remote add origin 레포지토리 url 
* git push -u origin master
* git 연동 이메일과 비밀번호를 쳐서 push해준다.

새로운 프로젝트를 시작할때마다 github에 레포지토리를 새로 생성해주는게 깔끔하게 정리됨

# npm 시작하기
처음에 npm 모듈을 설치한 부분이 없기때문에, package.json 파일이 없음 생성하기 위해서 cmd창에 
* npm init
* npm install jquery(설치할모듈) --save

[npm install jquery 도 되지만 package.json 파일에 저장되지 않기 때문에 --save를 함께 붙여줘야된다.]

> .gitignore 파일 생성
node_modules 필요 하지 않은 모듈도 같이 생성되어 있다 필요한 부분만 사용하기 위해서 .gitignore 생성하여 /node_modules 넣어줌
깃이 이 파일을 읽고 안에 있는 내용들의 소스들을 무시함. ( 불필요한 내용에대한 시간절감 )
[/node_modules 절대경로]