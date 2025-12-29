# YuJin's Portfolio  
안녕하세요! 양유진입니다. 제 포트폴리오를 소개합니다.
<br>

## 💻 Projects 

> ### 🧪 QA Automation– "F1 - AI 핼피봇 서비스 QA 및 테스트 자동화"
> - **개요**  
>   - AI 챗봇을 제공학는 웹 서비스에 대해 Selenium + Pytest 기반 자동화 테스트를 설계, 구현한 QA 프로젝트입니다.
>   - 단순 기능 확인을 넘어, 테스트를 자동화하고 Jenkins CI/CD 파이프라인을 통해 테스트 자동 실행 환경을 구축했습니다.
> - **문서 자료**
>   - [테스트계획서, 테스트케이스, 테스트결과보고서, Jenkins보고서, 시연영상] 
>   - [산출물](https://drive.google.com/drive/folders/1uY2gyt-DAuWVxbD7FLldfAGoSrK9UwWi?usp=sharing)
>   
> - **주요 작업**
>   > - 자동화 테스트 설계 및 구현
>   >  > - Selenium + Pytest 기반 POM 구조 적용
>   >  > - PPT / Quiz / 심층조사 생성 플로우에 대한 E2E 테스트 자동화
>   >  > - 입력값 검증 및 UI 상태 검증
>   > - 테스트 안정성 개선
>   >  > - 실패가 예상되는 케이스에 대해 xfail/xpass 적용
>   >  > - JS click 적용으로 ElementClickInterceptedException 해결
>   > - CI/CD 파이프라인 구축
>   >  > - Jenkins Pipeline을 통해 push 시 자동 테스트 실행
>   >  > - 테스트 성공/실패를 즉시 확인 가능한 환경 구성
>   
> - **기술스택**
>   - Test Automation: Python, Selenium, Pytest
>   - CI/CD: Jenkins
>   - Tools: GitLab, Jira, Zephyr, VSCode, Notion, Excel 
>     
> - **레포지토리 링크**  
>   [🔗 View Repo](https://github.com/yujin1875/F1_project)

> ### 🌐 WEB Development – "Goseumdochi 학원 강의 포털 & 커뮤니티"
> - **개요**  
>   - 고등학생을 대상으로 학원 강의, 커뮤니티, 맞춤형 학습 경로 추천을 제공하는 통합 온라인 교육 플랫폼입니다.
>   - 학생과 학원 운영자, 관리자가 사용할 수 있는 기능을 구현하여 실제 웹 서비스 환경에서 동작하는 시스템을 완성했습니다.
> - **문서 자료**
>   - [프로젝트보고서](https://drive.google.com/file/d/1q4aJ57_6ZKAV0ITXAFgmyMR-nrAs1iff/view?usp=sharing)
>   
> - **주요 작업**
>   > - 회원 관리 및 인증 기능
>   >  > - 회원가입, 로그인, 아이디/비밀번호 찾기, 임시 비밀번호 이메일 발송, 마이페이지, 프로필 사진 등록/수정  
>   > - 학생 기능 구현
>   >  > - 수업 자료 조회, 과제 확인 및 제출, 교과 정보 확인, 과목 공지사항 확인, 과제/시험 응시 및 제출
>   > - 선생님 기능 구현
>   >  > - 수업 자료 업로드, 시험/과제 문제 출제, 채점, 평가 및 점수 관리
>   > - 파일 관리
>   >  > - GCP GCS를 활용한 이미지 파일, PDF 등 학습 자료 관리  
>   
> - **기술스택**
>   - Backend: Java, Spring Boot
>   - Frontend: React, HTML, CSS, JavaScript 
>   - DataBase: MySQL
>   - Tools: GitHub, IntelliJ IDEA, GCP, figma, erd cloud, StarUML
>     
> - **레포지토리 링크**  
>   [🔗 View Repo](https://github.com/yujin1875/Goseumdochi-official)

> ### 🌐 WEB Development – "Dressing 옷 코디 추천 시스템"
> 
> - **개요**  
>   - 사용자가 옷을 등록하고 카테고리별로 관리하며, ai 코디 추천 기능을 제공하는 웹 애플리케이션을 개발한 프로젝트입니다.  
>   - 회원과 관리자가 사용할 수 있는 다양한 기능을 구현하며 실제 웹 서비스 환경에서 동작하는 시스템을 완성했습니다.  
>   
> - **문서자료**  
>   - [SRS & system testing](https://github.com/yujin1875/SE-Dressing/blob/main/Documents/%5BSE%5D%20%EA%B3%BC%EC%A0%9C1%20-%20SRS.pdf)
>   - [SDS(다이어그램 및 프로토타입)](https://github.com/yujin1875/SE-Dressing/blob/main/Documents/2.%20%5BSE%5D%20SDS.pdf)
>
> - **주요작업**  
>   > - 옷장 관리 기능
>   >  > - 사용자가 옷 이미지를 업로드하고, 업로드된 이미지를 DB에 저장 후 메인 페이지에서 확인 가능
>   >  > - 등록된 옷 이미지를 삭제할 수 있는 기능 제공
>   >  > - 세션(HttpSession)을 통해 로그인한 사용자의 ID를 기반으로 개인화된 옷 관리 기능 지원
>   > - 날씨 외부 API 연동
>   >  > - 외부 WeatherAPI로부터 대구의 실시간 기온과 날씨 상태를 추출
>   >  > - 추출된 날씨 데이터는 추후 코디 추천 기능과 연계
>   
> - **기술스택**
>   - Backend: Java, Spring Boot
>   - Frontend: React, HTML, CSS, JavaScript 
>   - DataBase: MySQL
>   - Tools: GitHub, IntelliJ IDEA, GCP, StarUML
> 
> - **레포지토리 링크**  
>   [🔗 View Repo](https://github.com/yujin1875/SE-Dressing)

> ### 📱 WEB Analysis & Design - "우리 동네 맛집은 어디?"
>
> - **개요**  
>   - 어플 개발에 앞서 요구사항 분석과 설계 활동을 수행하고 문서화한 프로젝트입니다.  
>   - 실제 구현 전 단계에서 체계적인 설계 경험을 쌓았습니다.
>
> - **문서자료**  
>   - [SDS(다이어그램 및 프로토타입)](https://github.com/yujin1875/SW_project1/tree/main/Final%20Report)
>
> - **주요활동**  
>   - 어플 개발 전 체계적인 설계 과정을 경험하고 문서화  
>   - 요구사항과 설계 구조를 명확히 정의하여 개발 준비
>
> - **레포지토리 링크**  
>   [🔗 View Repo](https://github.com/yujin1875/SW_project1)

> ### 👥 Collaborative Fork & Feature Development
>
> - **개요**  
>   100명이 넘는 학생들과 함께 진행한 협력 프로젝트입니다.  
>   기존 오픈소스 또는 공용 레포지토리를 Fork하여 각자 기능을 추가하고 개선하며 협업하는 방식으로 진행되었습니다.
>
> - **주요 활동**  
>   - 레포지토리 Fork 및 개인 브랜치 생성  
>   - 새로운 기능 구현 및 기존 기능 개선  
>   - Pull Request를 통한 코드 리뷰 및 병합 과정 참여  
>   - Git을 활용한 버전 관리와 협업 경험 습득  
>   - 팀원 간 이슈 트래킹 및 커뮤니케이션
>
> - **참여 레포지토리 및 작업 내용**  
>   - [OSS_Paint_2024-1](https://github.com/yujin1875/OSS_Paint_2024-1) – 그림판 관련 기능 구현
>   > - Todo list 템플릿 구현  
>   > - 마름모, 밤하늘, 벽돌, 벌집, 체커보드 등 반복 패턴 기능 + 색상 조절  
>   > - 그라데이션 브러시, 연필 브러시 기능 추가  
>   > - 텍스트 굵기, 기울임꼴, 밑줄, 글꼴 선택 및 크기 조절, 색상 변경 기능  
>   > - 자동 캡처 저장 및 백그라운드 이미지 설정  
>   > - 컨버스 달력/악보 템플릿 추가
>   - [OSS_Account_2024-1](https://github.com/yujin1875/OSS_Account_2024-1) – 가계부 관리 기능 구현
>   > - 지출 추세 그래프 생성 기능 추가  
>   > - 카테고리별 항목 필터링 기능 추가

> - **성과**  
>   - 대규모 협업 환경에서 Git과 Fork 기반 협업 프로세스를 경험  
>   - 기능 개발 뿐만 아니라 코드 리뷰와 통합 과정까지 참여하며 실무형 협업 역량 향상
>     
> - **기술스택**
>   - Language : python
>   - Tools: GitHub, Sourcetree

## 📜 Certifications
> - ADSP (데이터분석준전문가, 2023)  
> - SQLD (SQL 개발자, 2024)  
> - ISTQB Certified Tester Foundation (2025)
> - 정보처리기사 (2025)
