# 서울대학교 빅데이터연구원 4차산업혁명 아카데미 비즈니스 애널리틱스 과정
-----------
## - 교육 내용 소개 [[자세히 보기]](https://github.com/lee-kyubong/data-analytics/blob/master/course_syllabus/BA1.jpg)
## - 대표 분석 수행물
### 캡스톤 프로젝트 (기업 현장에서 데이터 분석 수행)
[* KB생명보험:  FC 채널 고능률화를 위한 설계사 맞춤형 관리방안 제시 [비지니스 인사이트 도출, 클러스터링]](https://github.com/lee-kyubong/data-analytics/blob/master/KBL/KBL_summarizedreport.pdf) [[자세히 보기]](https://github.com/lee-kyubong/data-analytics/blob/master/KBL/KBL_summarizedreport.pdf)
- 주요 판매채널(FC, GA, TA) 관리자 인터뷰를 통한 보험 도메인 지식 습득 / '고능률 설계사'를 정의내릴 지표 선정
- 분석 테이블 구축을 위해 정산관리용 데이터로부터 변수 생성 작업
- 회귀분석을 통한 유의변수(지표)를 추려내고, 이를 기반으로 클러스터링 수행 (R 활용)
- 분석 결과를 현업 실무자들과 공유 / 군집별 특성에 맞게 원수사 차원의 관리 방안 제시 
> 로그 수준의 데이터를 가공하여 분석/모델링까지 도출한 프로젝트
> 프로젝트 수행을 위한 빠른 도메인 지식 습득
> 활용된 이론 바탕을 비전문가들에게 설명하는 자세 훈련

### Data Mining
[* 공동 및 개인 발의 현황을 통한 국회의원 서브그룹 클러스터링 [비지도학습, 군집분석]](https://github.com/lee-kyubong/data-analytics/blob/master/Clustering_Politician-Party/Clustering(Political%20sub-parties).ipynb) [[자세히 보기]](https://github.com/lee-kyubong/data-analytics/blob/master/Clustering_Politician-Party/Clustering(Political%20sub-parties).ipynb)
- 주어진 발의 현황 데이터(개인 발의 여부, 공동 발의 여부 및 공동 발의자 명단, 각 의원(익명)의 소속 정당)를 의원 간 '거리 데이터'로 변환하는 전처리 작업
- k-means, hierarchical clustering 알고리즘(비지도학습)을 활용해 군집화
- 군집 결과를 2016년 정계 상황과 비교해 parameter 조절 및 고도화
> 군집화를 위한 비지도학습의 이론 기반 이해
> 실제 도메인 상황을 분석 결과 해석에 활용

### EDA Visualization
[* 국내 PB & NB 과자 상품 텍스트 마이닝 (NAVER API 응용) [편상관계수, 빈도분석, 마케팅]](https://github.com/lee-kyubong/data-analytics/blob/b45d9714df803aed7431dbca8767ca1b153c461e/EDA_SnackMarket/Korean_Snack_Market_Analysis.pdf) [자세히 보기](https://github.com/lee-kyubong/data-analytics/blob/b45d9714df803aed7431dbca8767ca1b153c461e/EDA_SnackMarket/Korean_Snack_Market_Analysis.pdf)
- 네이버 Open API를 활용해 블로그 서비스 내 게시물 크롤링
- R 패키지(tm, KoNLP)를 활용해 텍스트 데이터 전처리
- Graphical Lasso 알고리즘을 통해 해당 과자 내 주요 키워드 간 상관관계 파악
> 분석결과를 통해 '전통적 과자'와 'PB 과자'에 대한 대중들의 인식 파악 / 강점은 계승하고 단점은 극복할 마케팅 방안 제시

### DB Marketing
[* RFM exercise [머신러닝 기법별 성능비교, 변수 선택]](https://github.com/lee-kyubong/data-analytics/blob/master/RFM_exercise/report.pdf) [[자세히 보기]](https://github.com/lee-kyubong/data-analytics/blob/master/RFM_exercise/report.pdf)
- Recency, Frequency, Monetary 변수가 포함된 고객 구매 데이터를 활용 분석 / 쿠폰 발행 시 구매 유도 가능성 예측
> 대표 알고리즘 간 성능 비교와 모델 채택 과정 연습 경험

---------

