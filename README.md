# SQL 튜닝 학습 프로젝트

MySQL 기반 SQL 튜닝 기법을 학습하기 위한 프로젝트입니다. 
오라클 기준 SQL 튜닝 책의 내용을 MySQL로 변환하여 실습할 수 있습니다.

## 🚀 시작하기

### 1. Docker Compose 실행

```bash
# 컨테이너 시작
docker compose up -d

# 컨테이너 중지
docker compose down

# 볼륨까지 삭제 (데이터 완전 삭제)
docker compose down -v
```

### 2. Adminer 접속

브라우저에서 `http://localhost:8080` 접속

**로그인 정보:**
- 데이터베이스 형식: MySQL / MariaDB
- 서버: mysql
- 사용자이름: user
- 비밀번호: password
- 데이터베이스: db

## 🛠️ 기술 스택

- **데이터베이스**: MySQL 8.0
- **관리 도구**: Adminer
- **컨테이너**: Docker Compose

## 📖 참고 자료

- 친절한 SQL튜닝