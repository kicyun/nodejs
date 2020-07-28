# nodejs
node.js boilerplate
# 참고 사이트
## 기반
https://github.com/pjt3591oo/node-express-boilerplate
## node를 보다 견고하게
https://softwareontheroad.com/ideal-nodejs-project-structure/
## passport 를 이용한 로그인
https://cheese10yun.github.io/passport-thirdpart-loginl/
## watson 을 이용한 로깅
https://basketdeveloper.tistory.com/42?category=789573


### 1. express 프로젝트 시작

`express-genderator`설치

```
$ npm install -g express-generator
```

express-generator이외의 서버를 실행 시키기 위한 패키지를 받아보자.
- nodemon : 서버 내부의 코드가 바뀌면 서버를 자동으로 재시작 해주는 패키지
- forever : 서버를 백그라운드로 띄어주는 패키지

```
$ npm install -g nodemon
$ npm install -g forever
```

`express` 프로젝트 생성

```
$ express {project_name}
```

project_name이라는 디렉토리가 생성이 된다.

