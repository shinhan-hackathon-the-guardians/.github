# 신한: 더 패밀리 가디언 (가족 금융 안심 서비스)
![image](https://github.com/user-attachments/assets/e579e894-22cf-4615-b8b5-6e7d30577f48)

## 📌 목차

1. [프로젝트 개요](https://www.notion.so/readme-md-daf154cafb1744408a5a4138becb48c9?pvs=21)
2. [팀 소개](https://www.notion.so/readme-md-daf154cafb1744408a5a4138becb48c9?pvs=21)
3. [주요 기능](https://www.notion.so/readme-md-daf154cafb1744408a5a4138becb48c9?pvs=21)
4. [기술 스택](https://www.notion.so/readme-md-daf154cafb1744408a5a4138becb48c9?pvs=21)
5. [아키텍처](https://www.notion.so/readme-md-daf154cafb1744408a5a4138becb48c9?pvs=21)
6. [시연 사진](https://www.notion.so/readme-md-daf154cafb1744408a5a4138becb48c9?pvs=21)
7. [설치 및 실행 방법](https://www.notion.so/readme-md-daf154cafb1744408a5a4138becb48c9?pvs=21)
8. [API 사용](https://www.notion.so/readme-md-daf154cafb1744408a5a4138becb48c9?pvs=21)
9. [프로젝트 비전 및 향후 계획](https://www.notion.so/readme-md-daf154cafb1744408a5a4138becb48c9?pvs=21)

## 프로젝트 개요

  "신한: 더 패밀리 가디언"은 가족을 각종 금융 위협으로부터 보호하기 위한, 보다 따뜻한 금융을 지향하는 가족 안심 서비스입니다. 보이스피싱, 스미싱, 무분별한 과소비 등 증가하는 금융 위협에 대응하여, 가족 구성원의 경제적 독립성을 보장하면서도 효과적으로 금융 안전을 지키는 솔루션을 제공합니다.

## 팀 소개

**팀명: 더 가디언즈**

👑 **안현욱**(팀장): BE - 결제 감지, 그룹 시스템
👨‍💻 **이한주**: BE - 학습 시스템,  AI 챗봇
👨‍💻 **이준용**: BE - 인증/인가,  알림 시스템
🎨 **현경찬**: FE - 알림, 챗봇, 메인 페이지
🎨 **조윤정**: FE - 그룹, 설정, 시험 페이지

## 주요 기능

1. 🏠 **패밀리 그룹 구성**: 가디언과 서포터 역할을 통한 가족 금융 관리
2. 🛑 **송금 차단**: 보이스피싱 방지를 위한 현금 인출 및 계좌 이체 제한
3. 💳 **결제 한도 설정**: 하루/주간/월간 사용량 및 단건 결제 금액 제한
4. 👀 **모니터링 및 알림**: 한도를 초과한 인출 및 이체, 결제 시 알림
5. 📚 **금융 학습 시스템**: AI 챗봇을 활용한 금융 교육 및 가디언 자격 취득 지원
6. ⚡ **실시간 결제 감지**: 등록된 계좌의 잔액 변동 실시간 모니터링

## 기술 스택

- **Frontend**: React, Tailwind CSS
- **Backend**: Java, Spring Boot, JPA, Spring Security
- **Database**: MySQL, Redis
- **Notification**: Firebase Cloud Messaging

## 아키텍처
![image](https://github.com/user-attachments/assets/d1cd61df-fd93-49bc-9918-b8f0fa96ee4c)


## 시연 사진
<div align="center">
<img src="https://github.com/user-attachments/assets/622f254f-dc90-4c0b-8d76-10ef9a2ba37f" width="200" alt="스플래시 화면">
<img src="https://github.com/user-attachments/assets/58511b06-8820-4f5c-a3f3-bd835e4ff92f" width="200" alt="화면 3">
<img src="https://github.com/user-attachments/assets/b929480a-3535-49dd-adcb-0ac5d69b90de" width="200" alt="화면 4">
<img src="https://github.com/user-attachments/assets/85cd8744-00bd-4054-a1f9-ba71d300e709" width="200" alt="그룹원 추가 화면">
<img src="https://github.com/user-attachments/assets/a87f4c49-9df0-477c-973a-dbf6bd4f5e84" width="200" alt="화면 6">
<img src="https://github.com/user-attachments/assets/16b05da3-026b-4bd1-bbe0-4023e1e1b37b" width="200" alt="화면 7">
<img src="https://github.com/user-attachments/assets/cabea35e-8514-4077-a117-21b8686b056a" width="200" alt="화면 8">
<img src="https://github.com/user-attachments/assets/b71c768a-49cc-4fcf-8faa-85fc1586426d" width="200" alt="화면 9">
</div>


## 설치 및 실행 방법

1. 저장소 클론
    
    ```
    git clone <https://github.com/your-repo/신한-더-패밀리-가디언.git>
    cd 신한-더-패밀리-가디언
    
    ```
    
2. 백엔드 설정 및 실행
    
    ```
    cd backend
    ./gradlew build
    ./gradlew bootRun
    
    ```
    
3. 프론트엔드 설정 및 실행
    
    ```
    cd frontend
    npm install
    npm start
    
    ```
    

## API 사용

본 프로젝트는 다음과 같은 신한은행 API를 활용합니다:

1. **사용자 로그인**
    - 계정 생성
    - 계정 조회
2. **수시입출금**
    - 계좌 생성
    - 계좌 조회
    - 계좌 잔액 조회
    - 계좌 출금
    - 계좌 입금
    - 계좌 이체
    - 계좌 이체 한도 변경
    - 계좌 거래 내역 조회
    - 계좌 거래 내역 조회(단건)
3. **인증**
    - 1원 송금
    - 1원 송금 검증

## 프로젝트 비전 및 향후 계획

"신한: 더 패밀리 가디언"은 단순한 금융 서비스를 넘어, 가족의 금융 안전과 교육을 위한 종합 플랫폼으로 발전하고자 합니다. 우리의 비전과 계획은 다음과 같습니다:

1. **AI 기반 금융 위협 탐지 고도화**: 머신러닝 모델을 지속적으로 개선하여 더욱 정확한 금융 사기 탐지 시스템 구축
2. **금융 교육 콘텐츠 확장**: 연령별, 상황별 맞춤형 금융 교육 콘텐츠 개발 및 제공
3. **가족 금융 계획 도구 개발**: 가족 구성원 전체의 재무 상태를 통합 관리하고 장기적인 재무 계획을 수립할 수 있는 도구 추가
4. **다국어 지원**: 글로벌 시장 진출을 위한 다국어 서비스 지원
5. **오픈 뱅킹 연동**: 다양한 금융 기관과의 연계를 통해 서비스 범위 확대

우리는 이러한 계획을 통해 "신한: 더 패밀리 가디언"을 가족 금융의 새로운 패러다임을 제시하는 혁신적인 서비스로 발전시켜 나갈 것입니다.
