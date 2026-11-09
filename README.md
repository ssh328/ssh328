## Hi there 👋
 
## 🛠 Tech Stack
 
**Backend**<br>
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
 
**Frontend**<br>
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
 
**Database**<br>
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
 
**Tools**<br>
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

<br>

## 📌 Featured Projects

### 💅 땡잡은 언니 (Thankunnie) · 뷰티샵 빈자리 예약 플랫폼
> 흩어진 뷰티샵의 빈자리와 할인을 한곳에서 비교하고, 예약금 결제부터 방문까지 연결하는 서비스입니다. (U-CAMP 2조 · 6인 풀스택 팀 · 2026.10.19 ~ 11.05)

- **My Role** : 찜, 문자(Solapi) 발송, 알림 이벤트, SSE 서버·heartbeat
- **팀 프로젝트의 핵심 문제** : 같은 빈자리의 동시 예약 제어, 예약·결제 상태 연결, 취소 이후 빈자리 재공개와 알림
- **검증 (팀 기준)** : 백엔드 자동 테스트 1,131개, JaCoCo 라인 커버리지 94.4%
- **Stack** : `Java 21` `Spring Boot` `Spring Security` `JPA` `Oracle` `React` `Docker` `AWS EC2`
- 🔗 [Repository](https://github.com/ironhamlab/thankunnie) · 공개 배포는 발표 후 종료되었습니다.

<br>

### 💳 ResaleStore · 에스크로 기반 중고거래 서비스
> 게시글 기반 중고거래 서비스로, 결제(Toss Payments) → 에스크로 → 판매자 지갑 정산까지 이어지는 안전 거래 흐름을 구현했습니다.
 
- **결제·에스크로** : Toss Payments 서버 검증, 결제 완료 시 게시글 자동 예약중 전환, 배송 중 → 구매 확정 → 수수료 제외 후 판매자 지갑 정산
- **Redis 활용** : 조회수, 최근 본 글, Sorted Set 기반 인기/카테고리별 추천
- **인증·보안** : JWT(HttpOnly 쿠키) + Spring Security, CSRF 토큰, 비밀번호 변경·계정 삭제 시 임시 토큰 검증
- **이미지 업로드** : S3 Presigned URL로 클라이언트가 직접 업로드
- **Stack** : `Java 21` `Spring Boot` `Spring Security` `JPA` `MySQL` `Redis` `AWS S3` `Elastic Beanstalk`
- 🔗 [Repository](https://github.com/ssh328/project) · [API 명세서](https://thinkable-earthquake-735.notion.site/Resale-Store-API-2e7a5166124c800c861dfa772bbac7c0?source=copy_link) · [트러블 슈팅](https://thinkable-earthquake-735.notion.site/2eea5166124c80f88b1bcf93f60225f0?source=copy_link)
 
---

<br>

![GitHub stats](https://github-readme-stats-two-liard-14.vercel.app/api?username=ssh328&show_icons=true&theme=default)
