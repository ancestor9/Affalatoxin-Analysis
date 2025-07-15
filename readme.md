### 1. 식품위해예측 시스템 구축에 활용할 수 있도록 우선순위 위해요소별*의예측모델 등 개발 필요
* (1순위)아플라톡신, 오크라톡신 A, (2순위)푸모니신, (3순위)리스테리아 모노사이토제네스,
데옥시니발레놀, 병원성 대장균, 비브리오 패혈증균, (4순위)삭시토신

#### 1.1. Feature 구성
  #### - 예측모델 개발 대상 위해요소: 아플라톡신
  #### - 제안서 24페이지 ~ 27페이지 기존문헌(literature Review)를 통해 Feature 재구성 필요
                   - 기존문헌에서 데이터를 재현하여 아폴라톡신에 대한 위해 인자 도출
#### 1.2. Target 구성
  #### - 식약처의 LIMS 데이터에서 해당 식품종류(농산물)을 분석대상으로 set

#### 1.3. Feature & Targer 선행연구결과 (제안서 53페이지)
<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/0e977248-8150-4fbd-83a5-10298e2cfe32" />

### 2. 데이터 수집 및 분석
#### 2.1. 기후(온도, 습도, 강수량, 토양 정보 등) 정보 Webcrawling : Timesereis data
#### 2.2. 식약처 수거검사 데이터(Positive, Negative로 아플라톡신 이진분류) : Cross-sectional data
#### 2.3. Cross-sectional 데이터를 기준으로 Timesereis + 

