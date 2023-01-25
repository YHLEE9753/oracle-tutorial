# Oracle-Tutorial

## mac m1 oracle 설치
https://shanepark.tistory.com/400

Colima 실행
```
colima start --memory 4 --arch x86_64
```

Colima 정지
```
colima stop
```
볼륨 미설정
```
docker run --name oracle -e ORACLE_PASSWORD=1234 -p 1521:1521 -d gvenzl/oracle-xe
```
볼륨 설정
```
docker run --name oracle -d -p 1521:1521 -e ORACLE_PASSWORD=1234 -v oracledb:/opt/oracle/oradata gvenzl/oracle-xe
```
Docker 로그 확인
```
docker logs -f oracle
```
Docker connection test<br>
Host: localhost<br>
Post: 1521<br>
SID: XE<br>
Driver: Thin<br>
Authentication: User&Password<br>
User: system<br>
Password: 1234<br>

## mac m1 sql developer
https://shanepark.tistory.com/87

## Oracle Tutorial
https://www.oracletutorial.com/