# Investment_propensity_model
Investment propensity model using Stock Trading Data and Clustering Models

# 개요
* 주식 거래 내역을 이용한 투자자 성향 분류
* 마이데이터 산업 활성화로 인해 투자자 개인화 서비스에 대한 필요성 증가
* 기존 증권사의 투자자 성향 분류를 위한 설문은 의도적으로 조작 가능
* 주식 거래 내역을 통해 보다 정확하게 투자자 성향을 파악하고 맞춤형 투자 피드백 제공 가능

# 원리
* 모든 코스피 종목에 대한 가격 변동성, 거래량 회전율 계산 
* Standard Scaling을 통한 표준화
* 표준화된 2가지 Feature 기준으로 클러스터링
* 극단적으로 변동성, 거래량 회전율이 높은 군집은 위험 투자 성향이라고 판단, 반대의 경우 안전 투자 성향
* 포트폴리오의 경우 종목 비중과 보유기간을 고려하여 계산
