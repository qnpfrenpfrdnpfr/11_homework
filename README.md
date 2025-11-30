# 📨 FastAPI Community Backend  
FastAPI · SQLAlchemy · JWT Authentication · SQLite

이 프로젝트는 FastAPI를 기반으로 제작한 **커뮤니티 백엔드 서비스**입니다.  
회원가입, 로그인, 게시글 CRUD, 회원정보 수정 등의 기능을 제공하며  
JWT 인증과 SQLAlchemy ORM을 사용해 안정적인 서버 구조를 구현했습니다.

---

## 📌 Features (주요 기능)

### 👤 User (회원 기능)
- 회원가입
- 로그인 (JWT)
- 내 정보 조회
- 내 정보 수정

### 📝 Post (게시글 기능)
- 게시글 목록 조회
- 게시글 상세 조회
- 게시글 작성
- 게시글 수정

---

## 🛠 Tech Stack

| 기술 | 설명 |
|------|------|
| **FastAPI** | 웹 서버 프레임워크 |
| **SQLAlchemy ORM** | 데이터베이스 ORM |
| **SQLite** | 로컬 DB |
| **Passlib (bcrypt)** | 비밀번호 암호화 |
| **JWT (PyJWT)** | 로그인 인증/인가 |
| **Pydantic** | 데이터 검증 및 스키마 |

---

## 📁 Project Structure


---

## 🚀 How to Run (실행 방법)

### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
