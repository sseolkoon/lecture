## 데이터베이스 생성
```
$ createdb --encoding=UTF8 서울연구원
```
또는
```sql
postgres=# CREATE DATABASE 서울연구원 ENCODING='UTF8';
```

## 데이터 복원
```
$ psql 서울연구원 < 서울연구원.dump
```
