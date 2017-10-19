## 데이터베이스 생성
```
$ createdb -U postgres --encoding=UTF8 si
```

### 윈도우즈
```
> cd [postgresql이 설치된 디렉토리]\bin
> createdb.exe -U postgres --encoding=UTF8 si
```
또는
```sql
# CREATE DATABASE si ENCODING='UTF8';
```

## 데이터 복원
### 덤프파일 다운로드
1. si.dump 를 클릭
1. 오른쪽 상단에 Raw 클릭
1. 브라우저의 다른 이름으로 저장(Save As나 Save Page As)이나 Ctrl+s

```
$ psql -U postgres si < si.dump
```

### 윈도우즈
```
> cd [postgresql이 설치된 디렉토리]\bin
> psql.exe -U postgres si < [덤프파일의 path]
```
