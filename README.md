# TechPing-AI
이화캡스톤프로젝트 주식 도우미 챗봇 '스토기'의 Prompt-Tuning 레포
![화면 캡처 2024-11-21 223752](https://github.com/user-attachments/assets/bdeda09c-1ddf-48a0-a1e6-8b27906a9f19)

---
## 챗봇 스토기의 기능
### 1. 주식 입문자들을 Pin Point한 주식 용어 관련 쉬운 설명 제공
- '한국투자증권' 등 공식적으로 인증된 정보에서 Web Crawling을 통해 산재되어있는 주식 용어의 정확한 설명 제공
- Tools: `Selenium` : 동적 웹 사이트 크롤링 / `BeautifulSoup` : 정적 웹 사이트 크롤링

### 2. 주요 ticker에 대한 주식 데이터 수집
- Yahoo Finance API 이용
- 최신 2년 주식 데이터 제공
- 1일 주기로 업데이트: (시가, 고가, 저가, 종가, 거래량) 데이터 제공
- 데이터 시각화: 튜토리얼 기본 시각화 기능 제공
![image](https://github.com/user-attachments/assets/66851ebd-9f16-4415-9778-9f46890cc08f)

### 3. 사용자 마이 투자 리포트 분석
- 한 달 단위로 사용자의 '마이 투자 리포트' 분석 자료 제공
- 총 투자금 - 실 수익률 지표 기반 시각화 차트 제공
![image](https://github.com/user-attachments/assets/74617dc4-eaa9-44ff-8777-00efefaaacce)
