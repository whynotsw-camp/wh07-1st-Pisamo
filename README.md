# wh07-1st-Pisamo
LG U+ Why Not SW Camp 7기 피사모  프로젝트 1 레포지토리 입니다.

# ⚡ 팀원 소개

<table>
  <tr>
    <th>김지희</th>
    <th>배형진</th>
    <th>김다은</th>
    <th>이은영</th>
  </tr>
  <tr>
    <td><img src="https://github.com/" width="100"/></td>
    <td><img src="https://github.com/" width="100"/></td>
    <td><img src="https://github.com/" width="100"/></td>
    <td><img src="https://github.com/" width="100"/></td>
  </tr>
  <tr>
    <td>팀장</td>
    <td>발표자</td>
    <td>리서처</td>
    <td>기록자</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/jihuikim45">
        <img src="https://img.shields.io/badge/GitHub-Link-black?logo=github&style=flat"/>
      </a>
    </td>
    <td>
      <a href="https://github.com/bhjin97">
        <img src="https://img.shields.io/badge/GitHub-Link-black?logo=github&style=flat"/>
      </a>
    </td>
    <td>
      <a href="https://github.com/damdam1219">
        <img src="https://img.shields.io/badge/GitHub-Link-black?logo=github&style=flat"/>
      </a>
    </td>
    <td>
      <a href="https://github.com/2rlo0">
        <img src="https://img.shields.io/badge/GitHub-Link-black?logo=github&style=flat"/>
      </a>
    </td>
  </tr>
</table>

-------------------------------------------------------------

# 프로젝트 기획서
</summary>

## 1. 프로젝트 개요
- 프로젝트 주제 : **감정기반 AI 심리상담 서비스**
- 문제정의 : **많은 현대인들이 우울증을 겪고 있지만 사회적 인식과 심리치료에 부담감으로 실제로 치료로 이어지는 비율은 적음**
- 목표 : **챗봇을 통해 상담에 대한 접근성을 높이고, 누구나 손쉽게 감정 표현과 정서적 위로를 받을 수 있는 환경을 마련함과 동시에 실질적인 도움을 제공**

---------------------------------------------------------------------------------------------


### 프로젝트 기획서 다이어그램
</summary>
  --------------------------

# 작업 분할 구조 (WBS)

## 1. 단계별 작업 구성
### 1. 기획
1.1. 문제 정의  
1.2. 데이터 요구사항 정의  

### 2. 데이터 수집 및 준비
2.1. 데이터 소스 조사  
2.2. 데이터 수집 및 저장  
2.3. 데이터 전처리  

### 3. 데이터 분석 및 모델링
3.1. 데이터 탐색 및 시각화  
3.2. 모델 선택 및 학습  
3.3. 성능 평가  

### 4. 결과 도출 및 보고
4.1. 결과 요약  
4.2. 보고서 작성  
4.3. 최종 발표

  ------------------------------

# 요구사항 정의서

## 1. 기능 요구사항
- [ ] 데이터 수집 기능: [수집 대상 및 방식]
- [ ] 데이터 전처리 기능: [결측치 처리, 이상치 제거 등]
- [ ] 분석 기능: [사용할 알고리즘 또는 분석 기법]
- [ ] 시각화 기능: [대시보드, 차트, 그래프]

## 2. 비기능 요구사항
- [ ] 시스템 안정성: 데이터 처리 시 오류 발생 최소화
- [ ] 성능: 데이터 처리 및 분석 시간 최소화
- [ ] 확장성: 새로운 데이터 추가 및 확장 가능

----------------------------

# 프로젝트 설계서

## 1. 시스템 아키텍처
- **구성 요소**:
  - 데이터 수집 모듈
  - 데이터 전처리 모듈
  - 데이터 분석 및 시각화 모듈

## 2. 데이터 설계
- **데이터 흐름**: 원천 데이터 → 전처리 → 분석 → 결과
- **주요 데이터 속성**:
  - 속성 이름: [예: user_id, timestamp, value]
  - 데이터 유형: [정량, 정성]

## 3. 기술 스택
- **데이터 수집**: Python, Selenium, API 활용
- **분석**: Pandas, NumPy, Scikit-learn
- **시각화**: Matplotlib, Seaborn, Plotly

## 4. 예상 문제 및 해결 방안
- **문제**: 데이터 불균형  
  **해결 방안**: SMOTE 기법 활용

  
  <br>
   
## 📜문서

<details><summary>프로젝트 계획서
</summary>
