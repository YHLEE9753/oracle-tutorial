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
   [- UNION]()<br>
   [- INTERSECT]()<br>
   [- MINUS]()<br>
8. More on Groupings<br>
   [- Grouping sets]()<br>
   [- CUBE]()<br>
   [- ROLLUP]()<br>
   [- PIVOT]()<br>
   [- UNPIVOT]()<br>
9. Modifying data<br>
   [- ]()<br>
10. Data definition<br>
    [- ]()<br>
11. Oracle data types<br>
    [- ]()<br>
12. Constraints<br>
    [- ]()<br>
13. Temporary Tables<br>
    [- ]()<br>