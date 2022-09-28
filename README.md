### Mac 내장 Apache로 웹서버 운영하기✅
+ 맥 터미널에서 '아파치' 버전 확인 => `apachectl -v`
+ 아파치를 실행 => `sudo apachectl start`
   + 🛑 `sudo` 권한이라서 `password`를 묻는 단계가 있다. => 접속한 맥 계정 비밀번호를 입력하니 확인완료‼️
+ 브라우저에서 `localhost`로 접속 => `url`치는 곳에 `localhost`라고 치면 `It works!` 라는 페이지가 뜨면 성공‼️
+ index.html 파일 찾기 => `cd /Library/WebServer/Documents` 안에 있다.
  + 그래서 `Documents` 폴더 안에 해당 프로젝트 파일을 넣어두면 서버로 열 수 있다.😉
