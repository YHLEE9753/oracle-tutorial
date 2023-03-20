# Oracle Job Batch
- 주기적으로 수행되어지는 JOB 을 JOB QUEUE 를 사용해서 스케줄링 할 수 있다.
- (DB 내에 생성된 프로시저 함스들에 대해 DB 내의 스케줄러에게 지정한 시간에 자동으로 작업이 진행 될 수 있도록 하는 기능)
- JOB 을 스케줄링 하기 위해서 ORACLE 의 DBMS_JOB 패기지를 이용하며 JOB QUEUE PROCESS 가 JOB QUEUE  안의 JOB 을 수행한다.
- JOB으로 등록될 수 있는 것은 PL/SQL 프로시저 또는 패키지이다.
- DBMS_JOG 에 등록된 JOB 은 오라클이 관리한다
- ORACLE 에서 DBMS_JOB 패키지를 이ㅛㅇ해서 주기적으로 작업을 실행하는 방법이다.
- 특정시간에 특정 기능을 수행하게 하는 명령어라고 볼 수 있다.

## Simple explanation
- job_queue_process = 1:SNP 프로세스 개수를 지정
- job_queue-interval = 60:SNP 프로세스가 Sleep 상태에서 깨어나는 간격을 초로 지;정
- submit : 새로운 작업을 job queue 에 등록
- remove : job queue 에 등록된 job 을 제거
- change : job queue 에 등록된 job 을 변경
- next_date : job queue 에 등록된 job 의 작동시간을 변경
- interval : job queue 에 등록된 job 의 수행주기를 변경
- what : 수행할 procedure or package 변경
- run : 등록되어 있는 특정 job 을 수동으로 수행

## 1) Job 관리하기
```oracle-sql
DBMS_JOB.submit(
job out binary_integer, --실행시킬 job 번호
what in varchr2, -- 실제 작업을 수행하는 PL/SQL 또는 SQL 또는 Procedure 등
next_date in date default sysdate, -- job 이 수행될 다음일자
interval in varchar2 default 'null' -- job 이 수행될 다음 시간
no_parse in boolean default false) --

```
### 주요 파라미터 의미
- job : job 번호로 다른 프로시저에서 호출될 수 있음
- what : 수행할 pl/sql or procedure or package 이름을 지정, 직접 수행하기를 원하는 sql문 적어도 됨
- next_date : 다음에 수행될 시간을 지정
- interval : 수행되는 주기를 지정, 초단위까지 지정가능
- no_parse : parse 여부를 지정, 기본값은 false 로 parse를 수행

### 주기 예제
- sysdate + 7 : 7일에 한번
- sysdate + 1 : 하루에 한번
- sysdate + 1/24 : 한 시간에 한번
- sysdate + 1/1440 : 1분에 한번(24*60)
- sysdate + 1/86400 : 1ch (24*60*60)

## example
## JOB_TEST01 테이블 생성 1분마다 1번씩 데이터 INSERT
