# MCR기반 광고 매체 추천 가이드 

<h2>Project Introduction</h2><br>
<h3>Why? - 왜 했는지?</h3>

우리가 휴대폰 구매과정을 생각해 봤을 때 대부분이 광고를 통해 그 제품을 알게되고 관심을 갖고 구매까지 나아가게 된다. (근거 데이터 : 휴대폰 구매시 광고의 영향력). 제품 구매 시 광고의 영향력이 높다.<br>

그런데 소비자들은 접한 매체와 그 매체에 대한 관심도, 구매 시 반영하는 매체가 늘 일정하게 한 매체만 선호하는 것은 아니다.<br>

그러므로 우리는 구매과정 속에서 광고 카테고리별로 자주 접촉하는 매체, 그 광고 매체에 대한 관심도(얼마나 관심있게 보냐)와 구매 시 영향을 미치는 매체를 연속변수화하여 3차원으로 그래프화하고 성별, 연령별, 이용시간 등을 고려하여 기업에게 광고 매체 선정 가이드를 제시한다.<br> 

<h3>How? - 어떤 방법으로 했는지</h2><br>

MDS 다차원 척도법 (소비자의 휴대폰 광고 매체별 접촉률, 소비자의 휴대폰 광고 매체별 관심도, 소비자의 휴대폰 광고 매체별 구매영향력)<br>

상관관계 분석 (접촉률, 관심도, 구매영향력 ) <br>

시간대별 매체 이용자 수 분석 <br>

(성별/연령대별) 과 접촉 매체와의 관계 분석 (카이제곱 독립성 검정)<br>

(성별/연령대별) 과 관심도 <br>

(성별/연령대별) 과 구매영향도 <br>

<h2>File Description</h2><br>

MDS_3차원.R - 소비자의 휴대폰 광고 매체별 접촉률, 소비자의 휴대폰 광고 매체별 관심도, 소비자의 휴대폰 광고 매체별 구매영향력, 세 가지 요소를 3차원 그래프로 만드는 코드<br>

데이터_분석_코드.R - 상관관계 분석 (접촉률, 관심도, 구매영향력), 시간대별 매체 이용자 수 분석,(성별/연령대별) 과 접촉 매체, 관심도, 구매영향도와의 관계 분석 (카이제곱 독립성 검정) 등등의 통계 분석 코드<br>