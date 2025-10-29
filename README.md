# 👋 Hello, I'm JaeHwan!

저는 **가독성이 높고 효율적으로 동작하는 코드**를 작성하는 것을 중시하는 신입 백엔드 개발자 정재환입니다.
단순히 기능을 구현하는 것을 넘어, **반복적인 쿼리 호출이나 불필요한 API 요청**과 같은 성능 병목 지점을 인지하고 이를 **코드 레벨에서부터 최적화**하는 과정에 큰 흥미를 가지고 있습니다.

## 🛠️ Tech Stack

<!-- 사용하시는 기술 스택에 맞춰 아이콘을 수정/추가/삭제하세요. -->
<!-- https://github.com/Ileriayo/markdown-badges 에서 더 많은 아이콘을 찾을 수 있습니다. -->

**Backend**
<p>
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white">
  <img src="https://img.shields.io/badge/JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/QueryDSL-007396?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzMiIgaGVpZ2h0PSIzMiIgdmlld0JveD0iMCAwIDMyIj48ZyBmaWxsPSIjNjRCNUE2Ij48cGF0aCBkPSJNMjkuMzUgNS43N0wyMy42IDEuMDJDOC41MTMuNDg6IDEuOTY3IDcuNTggMS45NjcgMTYuMDAzYzAgOC44MjcgNi41NDYgMTUuNDg3IDIxLjYzMyAxNC45NTNsNS43NS00Ljc1N0MyMS42MiAyNS40OCAxNS41MzMgMTkuOTEgMTUuNTMzIDEyLjkzMUMxNS41MzMgNi43MiAyMS44NDUgMS44MSAyOS4zNSA1Ljc3NSIvPjxwYXRoIGQ9Ik0zMC4wMzMgMTYuMDAzYzAgOC44MjctNi41NDYgMTUuNDg3LTIxLjYzMyAxNC45NTNsNS43NS00Ljc1N0MyMS42MiAyNS40OCAxNS41MzMgMTkuOTEgMTUuNTMzIDEyLjkzMWMwLTYuMjggNi43MTItMTEuMTI3IDE0LjIxNy03LjE1NkwzMC4wMzMgMTZ6Ii8+PC9nPjwvc3ZnPg==">
</p>

**Database & Cache**
<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
  <img src="https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white">
</p>

**DevOps & Tools**
<p>
  <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/SpringDoc-85EA2D?style=for-the-badge&logo=swagger&logoColor=black">
</p>

## 🚀 Key Experience

저는 다음과 같은 경험을 통해 **팀의 생산성과 서비스의 안정성**을 높이는 데 기여했습니다.

1.  **코드 품질 개선:** PR 리뷰를 통해 `@Setter` 어노테이션 대신 **Builder 패턴과 DDD 기반의 도메인 메서드**를 사용하도록 제안하여 객체의 안정성과 코드 품질을 높였습니다.
2.  **협업 및 표준화:** `SpringDoc` API 문서화, **`공통 에러 응답`** 설계, `Flyway` DB 마이그레이션 등을 주도하여 팀의 협업 표준을 마련했습니다.
3.  **공통 모듈 개발:** 여러 도메인에서 반복적으로 사용되는 **파일 업로드 기능을 공통 모듈로 구현**하여 중복 코드를 제거하고 유지보수성을 향상시켰습니다. `FileService`와 `FileManager`를 설계하여 파일의 물리적 저장, 메타데이터 관리, URL 제공 및 소프트 삭제 기능을 중앙에서 관리하도록 구현했습니다.
4.  **성능 및 생산성:** **`Specification` 동적 쿼리 추상화**로 재사용성을 높였으며, `GitHub Actions` (CI/CD) 및 `Nginx` (환경 분리)를 구축하여 개발 생산성을 향상시켰습니다.

## 📌 Featured Project

### [Fantry (팬트리) - K-POP 팬덤을 위한 경매 기반 중고 굿즈 거래 플랫폼]

> **K-POP 팬덤을 위한 실시간 포토카드 경매 및 거래 서비스를 개발하며 백엔드, DevOps, 프론트엔드 성능 개선까지 다양한 역할을 수행했습니다.**
>
> -   **주요 역할:** 백엔드 개발, DevOps, 공통 모듈 설계
> -   **핵심 경험 (Backend & Application):**
>     -   **고객센터 (CS) 모듈 전체 설계 및 개발:** 1:1 문의, FAQ, 공지사항 기능의 전체적인 구조를 설계하고 개발했습니다. 사용자 및 관리자 API 엔드포인트를 구현하고, `JpaSpecificationExecutor`를 활용하여 동적인 검색 기능을 제공했습니다.
>     -   **정산 시스템 개발:** 판매자 정산 로직을 개발하고, 스케줄러를 이용해 정산 프로세스를 자동화했습니다. 또한, 관리자가 정산 내역을 효율적으로 관리할 수 있도록 대시보드 및 검색 기능을 구현했습니다.
>     -   **공통 파일 업로드 모듈 개발:** 여러 도메인에서 공통으로 사용할 수 있는 파일 업로드 모듈을 설계하고 개발하여 코드의 재사용성과 유지보수성을 높였습니다.
>     -   어드민 스마트 에디터의 **XSS 공격 방지**를 위한 HTML 새니타이저 도입 및 적용
> -   **핵심 경험 (DevOps & Team):**
>     -   **API 문서화 주도:** `SpringDoc`(Swagger)을 도입하여 API 명세를 체계적으로 문서화하고, 프론트엔드 개발자와의 협업 효율을 크게 향상시켰습니다.
>     -   **DB 마이그레이션 자동화:** `Flyway`를 도입하여 팀원 간의 DB 스키마 불일치 문제를 해결하고, 데이터베이스 변경 이력을 안전하게 관리했습니다.
>     -   GitHub Actions 기반 CI/CD 파이프라인 구축 (개발/운영 분리)
>     -   Nginx 리버스 프록시 구성 (WebSocket 라우팅 포함)
>     -   k6를 이용한 실사용자 시나리오 기반 부하 테스트
>
> **👉 자세한 내용은 아래의 포트폴리오에서 확인해주세요!

## 🔗 Links

-  [![Notion Portfolio](https://img.shields.io/badge/Notion%20Portfolio-000000?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.so/2924349fa07b810ab65ee41cb8d2d723?source=copy_link)
-   **Email:** rekindle402@gmail.com

## 📊 GitHub Stats

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=rekindle402&show_icons=true&theme=gotham)
