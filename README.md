# personal_project



## 1️⃣ 온라인 커머스몰('다잇다') 매출 분석 및 cross-selling 기반 구매 촉진 방안 [>바로가기](https://github.com/eunyeongkimm/personal_project/blob/04675a34fe46e7e0ef2e3db8f47ba2f725fe1643/commerce/%EC%98%A8%EB%9D%BC%EC%9D%B8_%EC%BB%A4%EB%A8%B8%EC%8A%A4%EB%AA%B0(%EB%8B%A4%EC%9E%87%EB%8B%A4)%EC%9D%98_%EB%A7%A4%EC%B6%9C_%EB%B6%84%EC%84%9D_%EB%B0%8F_cross_selling%EC%9D%84_%ED%86%B5%ED%95%9C_%EA%B5%AC%EB%A7%A4_%EC%A6%9D%EB%8C%80_%EB%B0%A9%EC%95%88.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eunyeongkimm/personal_project/blob/04675a34fe46e7e0ef2e3db8f47ba2f725fe1643/commerce/%EC%98%A8%EB%9D%BC%EC%9D%B8_%EC%BB%A4%EB%A8%B8%EC%8A%A4%EB%AA%B0(%EB%8B%A4%EC%9E%87%EB%8B%A4)%EC%9D%98_%EB%A7%A4%EC%B6%9C_%EB%B6%84%EC%84%9D_%EB%B0%8F_cross_selling%EC%9D%84_%ED%86%B5%ED%95%9C_%EA%B5%AC%EB%A7%A4_%EC%A6%9D%EB%8C%80_%EB%B0%A9%EC%95%88.ipynb)


* 문제 정의 
```
· 온라인 커머스몰('다잇다')의 최근 회원가입 고객 수 감소 및 매출액의 지속적인 정체 현상
· 이로 인해, 구매를 촉진할 전략적 접근 필요
```

* 프로젝트 내용
```
[EDA]
· 채널/주문월/상품카테고리별 매출액 분석
· 연령/회원가입연월별 회원수 분석
· 할인금액 - 매출액 상관관계 분석
· 상품 카테고리별 단가 분석
· 상품 카테고리별 재구매율 분석


[association rule 기반 cross-selling 전략]
· apriori 알고리즘 사용
· 상품/카테고리 기준 연관분석
· 저단가/중단가/고단가 카테고리 상품의 연관분석
· 연관 관계 및 아이템 간 향상도(lift) 시각화  
```


* 결론
```
· 상품권, 패션잡화, 키즈/유아동, 생활가전, 주방가전, 뷰티 카테고리의 경우 매출액과 할인금액의 상관계수가 0.8 이상으로,
  매출액 증진을 위해 해당 카테고리의 적극적 할인 정책 필요
· 재구매율이 높은 반려용품, 일반식품, 키즈/유아동 상품군의 경우, 재구매 고객에게 포인트, 쿠폰 등을 제공하여 로열티를 높이는 정책 필요
· 재구매율이 저단가>중단가>고단가 순으로 나타났으므로, cross-selling 전략은 저단가 제품군에 대해 우선적으로 실시해야함
· 가전(대형가전, 생활가전, 주방가전) 카테고리 상품의 중복 구매 확률이 가장 높게 나타났으므로, 가전 카테고리의 묶음 판매 및 중복 구매 시 할인 정책 필요
```
<br>
<hr><br>

## 2️⃣ Fastcampus 2022년 매출/강의 데이터 분석 [>바로가기](https://github.com/eunyeongkimm/personal_project/blob/6d0a2ff720ff2081faa6c4d6bef049ce98cf1076/commerce/Fastcampus_%EB%A7%A4%EC%B6%9C_%EB%B6%84%EC%84%9D_%EB%B0%8F_%EA%B3%A0%EA%B0%9D_%EC%84%B8%EA%B7%B8%EB%A8%BC%ED%8A%B8_%EB%8F%84%EC%B6%9C.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eunyeongkimm/personal_project/blob/6d0a2ff720ff2081faa6c4d6bef049ce98cf1076/commerce/Fastcampus_%EB%A7%A4%EC%B6%9C_%EB%B6%84%EC%84%9D_%EB%B0%8F_%EA%B3%A0%EA%B0%9D_%EC%84%B8%EA%B7%B8%EB%A8%BC%ED%8A%B8_%EB%8F%84%EC%B6%9C.ipynb)


* 문제 정의 
```
· 마케팅 전략 수립을 위한 고객 segmentation 필요
```

* 프로젝트 내용
```
[EDA]
· 강의별 첫번째/마지막 신청 유저 및 날짜(SQL- FIRST_VALUE, LAST_VALUE, PARTITION BY 이용)
· 월별 매출액 합계 및 전달 대비 증가율(SQL - LEAD, LAG)
· 매출액 경향성 분석(월별 트렌드, 주말 vs 주중 등)
· 회원가입 경향성 분석
· 강의별 상위 출현 키워드/환불 횟수

[RFM 분석 기반 고객 segmentation]
· RFM Scoring 및 9가지 고객군으로 분류
```

[> Tableau - 대시보드 바로가기](https://public.tableau.com/app/profile/eunyeong.kim/viz/fastcampuscustomersegmentation-rfm/1)

![Tableau - 대시보드](https://github.com/eunyeongkimm/personal_project/assets/101814174/d280972c-11cd-4ab4-9a89-1ada6d66dfbe)


* 결론
```
· 작성 예정
```
<br>
<hr><br>


## 3️⃣ 온라인 커머스몰 구매 패턴 분석 및 RFM 분석 기반 고가치 고객 맞춤 전략 도출 [>바로가기](https://github.com/eunyeongkimm/personal_project/blob/441f0721c40672537e07c9a1ab86f1c0a875dfed/commerce/%EC%98%A8%EB%9D%BC%EC%9D%B8_%EC%BB%A4%EB%A8%B8%EC%8A%A4%EB%AA%B0_%EA%B5%AC%EB%A7%A4_%ED%8C%A8%ED%84%B4_%EB%B6%84%EC%84%9D_%EB%B0%8F_RFM_%EB%B6%84%EC%84%9D_%EA%B8%B0%EB%B0%98_%EA%B3%A0%EA%B0%80%EC%B9%98%EA%B3%A0%EA%B0%9D_%EB%8F%84%EC%B6%9C.ipynb)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eunyeongkimm/personal_project/blob/441f0721c40672537e07c9a1ab86f1c0a875dfed/commerce/%EC%98%A8%EB%9D%BC%EC%9D%B8_%EC%BB%A4%EB%A8%B8%EC%8A%A4%EB%AA%B0_%EA%B5%AC%EB%A7%A4_%ED%8C%A8%ED%84%B4_%EB%B6%84%EC%84%9D_%EB%B0%8F_RFM_%EB%B6%84%EC%84%9D_%EA%B8%B0%EB%B0%98_%EA%B3%A0%EA%B0%80%EC%B9%98%EA%B3%A0%EA%B0%9D_%EB%8F%84%EC%B6%9C.ipynb)

* 문제 정의 
```
· 경쟁사 대비 브랜드 충성도가 낮은 것으로 나타나, 장기적으로 안정적인 수익 창출 모색해야 함
· RFM분석을 통한 고가치 고객을 정의하고, 로열티를 이끌어낼 수 있는 맞춤형 전략 필요
```

* 프로젝트 내용
```
[EDA]
· 성별/연령구간별 고객 수 분석
· 구매 경과 일수 및 구매 주기 분석
· 고객 특성 별 구매 경과 일수 및 구매 주기 차이 확인(t-test, ANOVA)
· 재구매 유도 캠페인 반응 고객 수 분석
· 요일별 구매 패턴 분석
· 카테고리별 월평균 매출액/매출 성과(변동계수) 분석


[RFM분석 기반 고가치고객 도출 및 맞춤형 전략 도출]
· 고가치 고객 정의
· 고가치 고객의 인구통계학적 특성 분석
· 고가치 고객 선호 제품/카테고리 분석 및 맞춤형 전략
```


* 결론
```
· 고가치 고객의 2.0, 5.0 지역 분포 비중이 약 33%이므로, 이 지역에 오프라인몰 추가 투자 계획 검토 필요
· 고가치 고객은 34세 이상 39세 미만 연령대 분포 비중이 약 45%이며, 고가치 고객 그룹과 아닌 그룹의
   구매 횟수당 매출액의 차이가 가장 큰 카테고리는 리빙용품 및 주방용품(Home And Kitchen)이고,
   특히 2~3월에 해당 카테고리의 매출액이 높으므로, 웨딩/입주 관련 프로모션 검토 필요
```


<br><br><br>


