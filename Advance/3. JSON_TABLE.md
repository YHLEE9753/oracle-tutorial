# JSON_TABLE
- 12c 부터 사용가능
- json 데이터를 관계열 열과 행으로 매핑할 수 있고, 함수를 통해 리턴된 결과를 SQL 를 사용하여 가상의 관계형 테이블로 조회할 수 있게 만든다.
- 즉 JSON 데이터를 가지고 관계형 VIEW를 생성한다.

## syntax
```oracle-sql
JSON_TABLE
  ( expr [ FORMAT JSON ] [ , JSON_basic_path_expression ]
    [ JSON_table_on_error_clause ] [ JSON_table_on_empty_clause ] 
    JSON_columns_clause )
```
- `expr` : 쿼리하려는 JSON 문서입니다.
- `JSON_basic_path_expression` : SQL/JSON 경로 표현식입니다.( $ : 1줄. [$] : 여러줄 - SQL/JSON Path Expression 참고)
- `JSON_query_on_error_clause` : 특정 오류가 발생할 때 반환되는 값을 지정합니다.
- `JSON_query_on_empty_clause` : 일치하는 항목이 없을 경우 반환되는 값을 지정합니다.
- `JSON_columns_clause` : 함수에 의해 반환된 가상 관계형 테이블의 열을 정의합니다.
- JSON_TABLE() function 은 SELECT 절의 FROM 절에서만 사용가능하다.


## example
### simple example rhkwp
```oracle-sql
SELECT *
FROM JSON_TABLE('{a:1, b:2, c:3}', '$' COLUMNS(a, b, c));

--------------------
   A    B    C 
____ ____ ____ 
1    2    3    
```

```oracle-sql
SELECT *
FROM JSON_TABLE(
    '[{a:1, b:2, c:3}, {a:4, b:5, c:6}, {a:7, b:8, c:9}]', 
    '$[*]' 
    COLUMNS(a, b, c)
    );
    
--------------------
   A    B    C 
____ ____ ____ 
1    2    3    
4    5    6    
7    8    9  
```
### Less Columns
```oracle-sql
ELECT *
FROM JSON_TABLE(
    '[{a:1, b:2, c:3}, {a:4, b:5, c:6}, {a:7, b:8, c:9}]', 
    '$[*]' 
    COLUMNS(a, b)
    );
    
Result:

   A    B 
____ ____ 
1    2    
4    5    
7    8    
```



