# apache-tomcat

> Apache + Tomcat 환경에서 로드밸런싱을 이용하는 경우 세션 클러스터링을 하는 예제입니다.

------

## :running: ​테스트

1. Apache24 서비스 등록
2. tomcat9(:8080), tomcat9_2(:8090) 서비스 등록
3. Apache 실행, tomcat9, tomcat9_2 실행
4. localhost:8080, localhost8090 접속 후 세션 아이디 확인 => 세션 아이디가 다르게 조회
5. localhost 접속, 접속시마다 세션 아이디가 동일한 것을 확인

:page_facing_up: 포스팅 : [https://shxrecord.tistory.com/255](https://shxrecord.tistory.com/255)