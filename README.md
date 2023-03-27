# Oracle-Tutorial
- 실습 환경은 docker 이다
- 설치 Oracle docker image 는 gvenzl/oracle-xe:latest 이다.(230106 - OraDBHome21cXE)
- mac m1, m2는 Colima 사용 시 실습 가능하다
- Oracle Tutorial 는 12c 기준이다
## Oracle Tutorial
https://www.oracletutorial.com/


## Table
### 1. Start
[1.Oracle 설치](https://github.com/YHLEE9753/oracle-tutorial/blob/main/1.%20Start/1.Oracle%20%EC%84%A4%EC%B9%98.md)<br>
[2.Docker Oracle sqlplus 접속](https://github.com/YHLEE9753/oracle-tutorial/blob/main/1.%20Start/2.Docker%20Oracle%20sqlplus%20%EC%A0%91%EC%86%8D.md)<br>
[3.Oracle 유저 생성 및 Sample Data 주입(mac)](https://github.com/YHLEE9753/oracle-tutorial/blob/main/1.%20Start/3.Oracle%20%EC%9C%A0%EC%A0%80%20%EC%83%9D%EC%84%B1%20%EB%B0%8F%20Sample%20Data%20%EC%A3%BC%EC%9E%85(mac).md)<br>
[3.Oracle 유저 생성 및 Sample Data 주입(windows)](https://github.com/YHLEE9753/oracle-tutorial/blob/main/1.%20Start/3.Oracle%20%EC%9C%A0%EC%A0%80%20%EC%83%9D%EC%84%B1%20%EB%B0%8F%20Sample%20Data%20%EC%A3%BC%EC%9E%85(windows).md)<br>
[3-1.CDB 와 PDB](https://github.com/YHLEE9753/oracle-tutorial/blob/main/1.%20Start/3-1.CDB%20%EC%99%80%20PDB.md)<br>

### 2. Oracle Basics
1. Querying data<br>
   [- SELECT](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/1.%20Quering%20data/1.select.md) 
2. Sorting data<br>
   [- ORDER BY](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/2.%20Sorting%20data/1.Order%20by.md)<br>
3. Filtering data<br>
   [- DISTINCT](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/3.%20Filtering%20data/1.DISTINCT.md)<br>
   [- WHERE](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/3.%20Filtering%20data/2.WHERE.md)<br>
   [- AND, OR](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/3.%20Filtering%20data/3.AND%2COR.md)<br>
   [- FETCH](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/3.%20Filtering%20data/4.FETCH.md)<br>
   [- IN](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/3.%20Filtering%20data/5.IN.md)<br>
   [- BETWEEN](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/3.%20Filtering%20data/6.BETWEEN.md)<br>
   [- LIKE](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/3.%20Filtering%20data/7.LIKE.md)<br>
   [- IS NULL](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/3.%20Filtering%20data/8.IS%20NULL.md)<br>
4. Joining tables<br>
   [- A visual explanaton of Oracle joins](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/4.%20Joining%20tables/1.%20A%20visual%20explanaton%20of%20Oracle%20joins.md)<br>
   [- INNER JOIN](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/4.%20Joining%20tables/2.INNER%20JOIN.md)<br>
   [- LEFT JOIN](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/4.%20Joining%20tables/3.LEFT%20JOIN.md)<br>
   [- RIGHT JOIN](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/4.%20Joining%20tables/4.RIGHT%20JOIN.md)<br>
   [- FULL OUTER JOIN](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/4.%20Joining%20tables/5.FULL%20OUTER%20JOIN.md)<br>
   [- CROSS JOIN](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/4.%20Joining%20tables/6.CROSS%20JOIN.md)<br>
   [- SELF JOIN](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/4.%20Joining%20tables/7.SELF%20JOIN.md)<br>
5. Grouping data<br>
   [- GROUP BY](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/5.%20Grouping%20data/1.GROUP%20BY.md)<br>
   [- HAVING](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/5.%20Grouping%20data/2.HAVING.md)<br>
6. Subquery<br>
   [- Subquery](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/6.%20Subquery/1.Subquery.md)<br>
   [- Correlated Subquery](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/6.%20Subquery/2.Correlated%20Subquery.md)<br>
   [- EXISTS and NOT EXISTS](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/6.%20Subquery/3.EXISTS%20and%20NOT%20EXISTS.md)<br>
   [- ANY, SOME](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/6.%20Subquery/4.ANY%2C%20SOME.md)<br>
   [- ALL](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/6.%20Subquery/5.ALL.md)<br>
7. Set Operators<br>
   [- UNION](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/7.%20Set%20Operators/1.UNION.md)<br>
   [- INTERSECT](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/7.%20Set%20Operators/2.INTERSECT.md)<br>
   [- MINUS](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/7.%20Set%20Operators/3.MINUS.md)<br>
8. More on Groupings<br>
   [- Grouping sets](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/8.%20More%20on%20Groupings/1.Grouping%20sets.md)<br>
   [- CUBE](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/8.%20More%20on%20Groupings/2.CUBE.md)<br>
   [- ROLLUP](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/8.%20More%20on%20Groupings/3.ROLLUP.md)<br>
   [- PIVOT](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/8.%20More%20on%20Groupings/4.PIVOT.md)<br>
   [- UNPIVOT](https://github.com/YHLEE9753/oracle-tutorial/blob/main/2.%20Oracle%20Basics/8.%20More%20on%20Groupings/5.UNPIVOT.md)<br>
9. Modifying data<br>
10. Data definition<br>
11. Oracle data types<br>
12. Constraints<br>
13. Temporary Tables<br>

### 3. Oracle View

### 4. Oracle Index
[1. Create a new index](https://github.com/YHLEE9753/oracle-tutorial/blob/main/4.%20Oracle%20Index/1.%20Create%20a%20new%20index.md)<br>
[2. Removing an index](https://github.com/YHLEE9753/oracle-tutorial/blob/main/4.%20Oracle%20Index/2.%20Removing%20an%20index.md)<br>
[3. Unique index](https://github.com/YHLEE9753/oracle-tutorial/blob/main/4.%20Oracle%20Index/3.%20Unique%20index.md)<br>
[3_1. Unique constraint vs Unique index](https://github.com/YHLEE9753/oracle-tutorial/blob/main/4.%20Oracle%20Index/3_1.%20Unique%20constraint%20vs%20Unique%20index.md)<br>
[4. Function-based index](https://github.com/YHLEE9753/oracle-tutorial/blob/main/4.%20Oracle%20Index/4.%20Function-based%20index.md)<br>
[5. Bitmap index](https://github.com/YHLEE9753/oracle-tutorial/blob/main/4.%20Oracle%20Index/5.%20Bitmap%20index.md)<br>

### 5. PL/SQL Tutorial
1. Getting statrted with PL/SQL<br>
   [- What is PL/SQL](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/1.%20Getting%20started%20with%20PL-SQL/1.%20What%20is%20PL-SQL.md)<br>
   [- Anonymous Block](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/1.%20Getting%20started%20with%20PL-SQL/2.%20PL-SQL%20Anonymous%20Block.md)<br>
   [- Data Types](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/1.%20Getting%20started%20with%20PL-SQL/3.%20Data%20Types.md)<br>
   [- Variables](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/1.%20Getting%20started%20with%20PL-SQL/4.%20PL-SQL%20Variable.md)<br>
   [- Comments](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/1.%20Getting%20started%20with%20PL-SQL/5.%20Comment.md)<br>
   [- Constants](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/1.%20Getting%20started%20with%20PL-SQL/6.%20PL-SQL%20Constants.md)<br>
2. Conditional control<br>
   [- IF statements](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/2.%20Conditional%20control/1.%20IF%20Statements.md)<br>
   [- CASE statements](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/2.%20Conditional%20control/2.%20CASE%20statements.md)<br>
   [- GOTO](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/2.%20Conditional%20control/3.%20GOTO.md)<br>
   [- NULL statement](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/2.%20Conditional%20control/4.%20NULL%20statement.md)<br>
3. Iterative processing with loops<br>
   [- Basic LOOP statement](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/3.%20Iterative%20processing%20with%20loops/1.%20Basic%20LOOP%20statement.md)<br>
   [- Numeric FOR LOOP statement](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/3.%20Iterative%20processing%20with%20loops/2.%20Numeric%20FOR%20LOOP.md)<br>
   [- WHILE loop](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/3.%20Iterative%20processing%20with%20loops/3.%20WHILE%20loop.md)<br>
   [- CONTINUE](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/3.%20Iterative%20processing%20with%20loops/4.%20CONTINUE.md)<br>
4. Select Into<br>
   [- SELECT INTO](https://github.com/YHLEE9753/oracle-tutorial/tree/main/5.%20PL-SQL%20Tutorial/4.%20Select%20Into)<br>
5. Exception handlers<br>
   [- Exception](5.%20PL-SQL%20Tutorial%2F5.%20Exception%20handlers%2F1.%20Exception.md)<br>
   [- Raise exceptions](5.%20PL-SQL%20Tutorial%2F5.%20Exception%20handlers%2F2.%20Raise%20exceptions.md)<br>
   [- Using raise_application_error](5.%20PL-SQL%20Tutorial%2F5.%20Exception%20handlers%2F3.%20Using%20raise_application_error.md)<br>
   [- Exception propagation](5.%20PL-SQL%20Tutorial%2F5.%20Exception%20handlers%2F4.%20Exception%20propagation.md)<br>
   [- Handling other unhandled exceptions](5.%20PL-SQL%20Tutorial%2F5.%20Exception%20handlers%2F5.%20Handling%20other%20unhandled%20exceptions.md)<br>
6. Records<br>
   [- Record](5.%20PL-SQL%20Tutorial%2F6.%20Records%2F1.%20Record.md)<br>
7. Cursors<br>
   [- Cursor](5.%20PL-SQL%20Tutorial%2F7.%20Cursors%2F1.%20Cursor.md)<br>
   [- Cursor FOR LOOP](5.%20PL-SQL%20Tutorial%2F7.%20Cursors%2F2.%20Cursor%20FOR%20LOOP.md)<br>
   [- Cursor with parameters](5.%20PL-SQL%20Tutorial%2F7.%20Cursors%2F3.%20Cursor%20with%20parameters.md)<br>
   [- Cursor Variable with REF CURSOR](5.%20PL-SQL%20Tutorial%2F7.%20Cursors%2F4.%20Cursor%20Variable%20with%20REF%20CURSOR.md)<br>
   [- Updatable cursor](5.%20PL-SQL%20Tutorial%2F7.%20Cursors%2F5.%20Updatable%20cursor.md)<br>
8. Stored procedures and Functions<br>
   [- Procedure](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/8.%20Stored%20procedures%20and%20Functions/1.%20Procedure.md)<br>
   [- Implicit statement results](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/8.%20Stored%20procedures%20and%20Functions/2.%20Implicit%20statement%20results.md)<br>
   [- Function](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/8.%20Stored%20procedures%20and%20Functions/3.%20Function.md)<br>
   [- Cursor variables](https://github.com/YHLEE9753/oracle-tutorial/blob/main/5.%20PL-SQL%20Tutorial/8.%20Stored%20procedures%20and%20Functions/4.%20Cursor%20variables.md)<br>
9. Packages<br>
10. Triggers<br>
11. PL/SQL Collections<br>
### 6. Oracle Aggregate Functions
[- Oracle Aggregate Functions](6.%20Oracle%20Aggregate%20Functions%2FOracle%20Aggregate%20Functions.md)

### 7. Oracle Analytic Functions
[- Oracle Analytic Functions](7.%20Oracle%20Analytic%20Functions%2FOracle%20Analytic%20Functions.md)

### 8. Oracle Date Functions
[- Oracle Date Functions](8.%20Oracle%20Date%20Functions%2FOracle%20Date%20Functions.md)

### 9. Oracle String Functions
[- Oracle String Functions](9.%20Oracle%20String%20Functions%2FOracle%20String%20Functions.md)

### 10. Oracle Database Administration
[- Oracle Database Administration](10.%20Oracle%20Database%20Administration%2FOracle%20Database%20Administration.md)

### Advance
[1. Connect By, Prioir](Advance%2F1.%20Connect%20By%2C%20Prioir.md)<br>
[2. Dual](Advance%2F2.%20dual.md)<br>
[3. JSON_TABLE](Advance%2F3.%20JSON_TABLE.md)<br>
[4. Merge](Advance%2F4.%20Merge.md)<br>
[5. With](Advance%2F5.%20with.md)<br>
[6. Partition by](Advance%2F6.%20partition%20by.md)<br>
[7. Oracle Job Batch](Advance%2F7.%20Oracle%20Job%20Batch.md)<br>
[8. over](Advance%2F8.%20over.md)<br>
[9. coalesce](Advance%2F9.%20coalesce.md)<br>

### Other
[1. 유용한 쿼리](Other%2F1.%20%C0%AF%BF%EB%C7%D1%20%C4%F5%B8%AE.md)<br>
[2. 테이블 생성 스크립트 추출](Other%2F2.%20%C5%D7%C0%CC%BA%ED%20%BB%FD%BC%BA%20%BD%BA%C5%A9%B8%B3%C6%AE%20%C3%DF%C3%E2.md)<br>

