## 데이터베이스 생성
```
$ createdb --encoding=UTF8 서울연구원
```
또는
```sql
# CREATE DATABASE 서울연구원 ENCODING='UTF8';
```

## 데이터 복원
```
$ psql 서울연구원 < 서울연구원.dump
```

## 덤프파일 다운로드
1. 서울연구원.dump 를 클릭
1. 오른쪽 상단에 Raw 클릭
1. 브라우저의 다른 이름으로 저장(Save As나 Save Page As)이나 Ctrl+s
