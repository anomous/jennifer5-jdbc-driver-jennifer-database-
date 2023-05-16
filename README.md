Jennifer JDBC Driver
---

Data can be retrieved using SQL by communicating with the API server that searches the Jennifer DB.  
Supports standard ANSI SQL, allowing use of most SQL functions.

#### How to query from the command line
```shell
java -jar jennifer-jdbc-{version}.jar -u jdbc:jennifer:{host}:{port};[dbName=default;dbType=data]
```
* version - driver version
* host - API server address or IP
* port - the port of the API server
* dbName - DB name entered in API server setting (optional) - Default: default
* dbType - DB type entered in API server settings (optional) - Default: data (view or data)
{###################################################################################################}

Korean language:

제니퍼 JDBC 드라이버
---

제니퍼 디비를 조회하는 API 서버와 통신하여 데이터를 SQL 로 조회할 수 있다.  
표준 ANSI SQL 을 지원하여 대부분의 SQL 함수 이용이 가능하다.

#### 커맨드라인에서 조회하는 방법
```shell
java -jar jennifer-jdbc-{version}.jar -u jdbc:jennifer:{host}:{port};[dbName=default;dbType=data]
```
* version - 드라이버 버전
* host - API 서버의 주소 or 아이피
* port - API 서버의 포트
* dbName - API 서버 설정에 입력한 디비의 이름 (optional) - 기본: default
* dbType - API 서버 설정에 입력한 디비의 타입 (optional) - 기본: data (view or data)
{###################################################################################################}
