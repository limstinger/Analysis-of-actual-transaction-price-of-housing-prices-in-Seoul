# Analysis of actual transaction price of housing prices in Seoul




 ◭ 2022.12  **OSS Term Project**  ◭
 
 <br>
 
 ## **Introduction**
 
 현재 물가가 여러 요인에 인해 끊임없이 상승하여 이 물가 상승을 막아 시장이 얼어붙는 것을 막기 위해 각 나라들은 금리를 인상하였다.
 그러나 이러한 금리 인상으로 인해 가장 직접적으로 영향을 받아 부동산 또한 이에 맞추어 변화가 일어났다.
 부동산은 우리의 생활과 매우 가깝게 연관되어 있어 뉴스에서도 중요하게 다루는 주제 중 하나이다.
 그래서 최근에 서울 부동산 거래가 어디서, 얼마나, 어떻게 변화가 일어났는지 알아보고자 한다.  
 
 **matplotlib**, **seaborn** 등의 패키지를 사용하여 2018년~2022년까지 서울 부동산 거래 데이터와 대출금리 데이터를 **DataFlame**하여 기준을 나누어 데이터를 분석하고 시각화하여 최근에 어떤 변화가 나타났는지 알아보고자 합니다.
 
 ## **Developer**
 
 * 컴퓨터공학과 21100162 임민규

## **Release**

[통계청](https://kosis.kr/search/search.do?query=%EA%B8%88%EB%A6%AC),을 통해 2018~2022년 대출 금리 데이터(csv)를 얻었으며 [서울특별시 홈페이지 공공데이터](https://data.seoul.go.kr/dataList/OA-21275/S/1/datasetView.do),를 통해 2018~2022년 서울 부동산 실거래가 데이터(csv)를 얻었으므로 모든 저작권 규칙은 해당 사용 약관에 따릅니다.

* pandas로 csv 파일 불러와 데이터프레임 형태로 데이터 저장


