제니퍼 JDBC 드라이버
---

제니퍼 디비를 조회하는 API 서버와 통신하여 데이터를 SQL 로 조회할 수 있다.  
표준 ANSI SQL 을 지원하여 대부분의 SQL 함수 이용이 가능하다.

#### 커맨드라인에서 조회하는 방법
```shell
java -jar jennifer-jdbc-{version}.jar -u jdbc:jennifer:{host}:{port}:[db-name]
```
* version - 드라이버 버전
* host - API 서버의 주소 or 아이피
* port - API 서버의 포트
