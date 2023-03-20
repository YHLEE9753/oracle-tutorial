# Oracle Aggregate Functions
## Introduction to Oracle aggregate functions
- Oracle 집계 함수는 행 그룹에서 계산하고 각 그룹에 대해 단일 값을 반환합니다.
- 일반적으로 group by 와 함께 aggregate functions 를 사용한다.
- group by 는 rows 를 groups 로 나누고, aggregate functions 가 계산하고 각 그룹에서 single result 를 반환한다.
- group by 없이 aggregate functions 를 사용하면, aggregate functions 는 views 나 queried tables 의 모든 rows 에 aggregate functions 를 적용한다.
- having, select, order by , group by 등에 aggregate functions 는 나타날 수 있다.

## DISTINCT vs. ALL
- 몇 aggregate function  은 distinct 와 all 를 accept 한다.
  - DISTINCT 절은 인수의 고유한 값만 고려하도록 집계 함수에 지시합니다.
  - ALL 절은 집계 함수가 중복을 포함하여 모든 값을 계산에 사용하도록 합니다.
- 예) 2,2,2,4 의 distinct average 는 (2+4)/2 3이다
- 예) 2,2,2,4 의 all average 는 (2+2+2+4)/4 = 2.5 이다.

## NULL treatments
- 모든 aggregate functions 는 count(*), grouping(), grouping_id() 를 제외하고 null 값들을 무시한다.
- null 값을 0 으로 대체하고 싶다면 NVL() 기능을 활용하라
  - count(), regr_count() 함수는 null 을 절대  반환하지 않고, 0 을 반환한다.
- 다른 aggregate functions 는 만약 input data set 이 null 을 포함하거나 no rows 를 가질 때 null 를 반환한다.

## Oracle aggregate function list
### AVG
```oracle-sql
-- A) Simple Oracle AVG() example
SELECT
    ROUND(AVG( standard_cost ), 2) avg_std_cost
FROM
    products;
-----------------------------
B) Oracle AGV() with DISTINCT clause
SELECT
    ROUND(
        AVG( DISTINCT list_price ),
        2
    ) avg_list_price
FROM
    products;
-----------------------------

```




