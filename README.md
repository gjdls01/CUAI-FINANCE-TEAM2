# CUAI-FINANCE-TEAM2
## 🍋 [금융보안원] 2021 금융데이터 경진대회 🍋
##### (Notion : https://www.notion.so/2021-60e9bc291ee14289a12feccbbe446406)
[금융보안원]2021 금융데이터 경진대회.ipynb
### 주제 : 서울시 소비자의 특성에 따른 요식업종 선호도 파악 및 생활지역권 내의 상권 분석을 통한 창업 가이드 제공
#### 1. 데이터 전처리 및 시각화
##### [KB 국민카드] 지역별 음식점 세부 업종 집계내역 : 코로나 전수 성.연령별 요식업종 선호도 (by 구매건수) 시각화
![newplot (4)](https://user-images.githubusercontent.com/77157003/131252267-c7f70e68-61e4-430e-9ab2-db5f06c2ca59.png)


< 코로나 전후 성별 연령별 구매력 >


![newplot (5)](https://user-images.githubusercontent.com/77157003/131252286-84000fc8-b1cd-49d9-8988-449237a854e6.png)


< 코로나 전후 전체 업종별 선호도 >


![newplot (6)](https://user-images.githubusercontent.com/77157003/131252307-5ebbf340-94b0-4908-8825-61135d43723d.png)


< 특정 업종의 코로나 전후 성별 연령별 선호도>




##### [공공데이터포털] 소상공인시장진흥공단_상가(상권)정보_서울 : 지역생활권별 요식업종 수 시각화
![newplot (3)](https://user-images.githubusercontent.com/77157003/131252250-bbbffc6e-f29b-4df0-a773-7482d2d35a89.png)


< 지역생활권별 요식업종 수 >

##### [서울 열린데이터 광장] 행정동별 서울생활인구(내국인) : 코로나 전후 서울 생활인구 시각화 (및 지역생활권별 영업시간별 예비소비자 예측 - 2번 참고) 
![newplot (2)](https://user-images.githubusercontent.com/77157003/131252219-21a19614-298f-4b8c-bfc2-c64cddc9a580.png)


< 코로나 전 개포 일원 지역생활권 서울 생활인구 >


![newplot (1)](https://user-images.githubusercontent.com/77157003/131252225-563313bd-12dd-4efc-af73-6651a99398e1.png)


< 코로나 후 개포 일원 지역생활권 서울 생활인구 >




#### 2. 행렬 분해를 통한 협업 필터링


시계열분석_전체.ipynb(밑의 설명 참고) 수행결과 생성된 csv 파일 (지역생활권별 생활인구 예측)을 이용


(지역생활권별 성별.연령별 생활인구)*(성별.연령별 요식업종 구매건수)/(지역생활권별 요식업종수) 연산을 수행


(지역생활권별 요식업종의 한 상가당 매출건수)를 도출하여 추천을 진행




#### 3. 지역생활권별 요식업 가이드 제공
(지역생활권)-(영업시간)-(요식업종) 선택 결과별 시각화 제공 및 

(지역생활권-영업시간)별 요식업종 또는 (지역생활권-요식업종)별 영업시간 추천]


![설정](https://user-images.githubusercontent.com/77157003/131253393-f1bd5d91-b08d-42e7-8138-7c22b9058562.PNG)


<버튼선택>


![버튼2](https://user-images.githubusercontent.com/77157003/131253371-a9c1c695-2ae9-4d80-bd10-4e383aac7ed2.PNG)


< (지역생활권-영업시간)별 요식업종 추천 >


![버튼3](https://user-images.githubusercontent.com/77157003/131253365-589262bd-a20c-416f-a962-b3cd5052cd67.PNG)


< (지역생활권-요식업종)별 영업시간 추천 >


시계열분석_전체.ipynb

![예측결과_전체](https://user-images.githubusercontent.com/80053493/131254145-b1f24d0c-2e18-447b-80a0-f2acce719cc2.png)
