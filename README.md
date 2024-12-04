## PUPPYDIARY
(접속 링크)
<br /><br />

### 📖 프로젝트 소개
반려견과 보호자를 위한 웹 애플리케이션으로 <br />
반려견을 케어하는 데 다양한 도움을 제공합니다.
<br /><br />

### ⚙ 개발 환경
- Node.js : 20.18.0
- npm : 10.8.2
- 주요 라이브러리 : Express, dotenv
- 데이터베이스 : MySql
- IDE : VS Code
- 배포환경 :
<br /><br />

### 📌 주요 기능
#### 오늘의 날씨정보 및 날씨에 따른 산책에 대한 어드바이스 제공
사용자에게 위치동의 여부를 묻고<br />
동의할 시 사용자의 위치를, 거부할 시 서울을 기준으로<br />
다양한 서비스를 제공합니다.

 #### 날짜별 일지기록
'기록추가'버튼을 눌러 날짜를 선택하거나<br />
이전, 다음 버튼을 통해 원하는 날짜를 선택하여<br />
해당하는 날짜에 강아지에 대한 기록을 추가/조회/수정/삭제할 수 있습니다.
<br /><br />

### 🕹 시작 가이드
node.js가 설치된 환경이어야 합니다.

```
// 프로젝트 복제
$ git clone https://github.com/UJH506/puppydiary.git

// 의존성 설치 (경로 - 해당 프로젝트)
$ npm install

// .evn 파일 생성 (경로 - 해당 프로젝트 루트)
DATABASE_HOST='localhost'
DATABASE_PORT='3306'
DATABASE_USER='이름을 작성하세요'
DATABASE_PASSWORD='비밀번호를 작성하세요'
DATABASE_NAME='puppydb'

// 실행
$ npm start
```