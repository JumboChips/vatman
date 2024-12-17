# VATMAN
> 부가세 신고를 더 편리하게.

---

## 1. 프로젝트 소개
- 이 프로젝트를 통해 매 분기 부가세 신고를 편리하게 한다.
- 부가세 신고를 위한 준비 서류의 작업을 돕는다.
- 분기별 부가세 예상 세액을 예측하고, 산정한다.
- 매입 매출을 정리한다.
- 재고 자금 흐름을 모니터링한다.

---

## 2. 기술 스택
- 이 프로젝트에 사용된 기술 스택 및 도구를 나열합니다.
    - **Backend**: Spring Boot, JPA, MySQL(Postgre SQL), SpringBoot Security
    - **Frontend**: Vue.js / Nuxt.js
    - **CI/CD**: GitHub Actions, Docker
    - **Deployment**: AWS EC2, RDS

---

## 3. 폴더 구조
📁 프로젝트명/ 
            ├── 📂 backend/ # 백엔드 코드 (Spring Boot) 
            ├── 📂 frontend/ # 프론트엔드 코드 (Vue.js/Nuxt.js) 
            ├── 📂 docs/ # 프로젝트 문서 및 기획안 
            ├── 📄 README.md # 프로젝트 설명 파일 
            └── 📄 .gitignore # Git에서 제외할 파일 목록

---

## 4. 설치 및 실행 방법

### Backend 실행
```bash
# 프로젝트 클론
git clone https://github.com/JumboChips/vatman_backend.git

# backend 디렉토리로 이동
cd backend  

# Gradle로 빌드
./gradlew build  

# 서버 실행
java -jar build/libs/app.jar

```
---

# 2. 커밋 규칙

### Commit 규칙 예시

- **feat**: 새로운 기능 추가
- **fix**: 버그 수정
- **docs**: 문서 수정
- **refactor**: 코드 리팩토링