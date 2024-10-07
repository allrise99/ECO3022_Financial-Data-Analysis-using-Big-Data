# ECO3022_Financial-Data-Analysis-using-Big-Data

[Description]
- CAPM, Fama French 모델을 주가 데이터를 이용해 검증
- scipy 라이브러리 사용

1. Exercise
주차별 과제 및 중간고사 시험에 제출한 소스 코드 

2. Midterm
중간고사 코딩 테스트 소스 코드

[중간고사 문제 설명]
midterm_data.csv는 2000.1부터 2020.12까지 여러 금융자산들의 일별 가격변화율(daily return)을 기록한 데이터며, 자산의 목록은 다음과 같습니다.

Spain 10Y: 스페인 국채 10년물
KOSPI: KOSPI 주가지수
SPY: S&P500 주가지수
crudeOilFutures: 원유 선물
naturalGasFutures: 천연가스 선물
goldFutures: 금 선물
copperFutures: 구리 선물

(1) business_cycle_label.csv를 이용해 midterm_data.csv로 다음의 세 가지 pandas dataframe들을 생성하시오 (5점)
df_up: 경기 확장기에만 해당하는 데이터
df_down: 경기 후퇴기에만 해당하는 데이터
df: 전체 데이터

(2) (1)에서 생성한 각 dataframe에 대해, 무위험자산을 배제하고 자산의 가중치들을 무작위로 부여한 random portfolio를 5,000개 생성해 이를 ( μ,σ ) 공간에 표시하시오. (10점)

(3) 모든 dataframe에 대해 무위험자산을 포함한 efficient frontier를 도출한 다음 이를 하나의 ( μ,σ ) 공간에 표시하고, 서로의 annualized Sharpe Ratio를 비교하시오. (10점)

(4) (3)번의 결과를 고려할 때, 경기 순환을 고려한 포트폴리오 운용이 실효성이 있는가? 그 근거는 무엇인가? (10점)

(5) 경기 순환의 국면별 tangency portfolio를 고려할 때, 경기가 확장/후퇴 할때 어떤 자산을 보유하고 있는게 좋은가? (5점)
