# personal_project

## 1️⃣ 온라인 커머스몰('다잇다') 매출 분석 및 cross-selling을 통한 구매 촉진 방안 [>바로가기](https://github.com/eunyeongkimm/personal_project/blob/04675a34fe46e7e0ef2e3db8f47ba2f725fe1643/commerce/%EC%98%A8%EB%9D%BC%EC%9D%B8_%EC%BB%A4%EB%A8%B8%EC%8A%A4%EB%AA%B0(%EB%8B%A4%EC%9E%87%EB%8B%A4)%EC%9D%98_%EB%A7%A4%EC%B6%9C_%EB%B6%84%EC%84%9D_%EB%B0%8F_cross_selling%EC%9D%84_%ED%86%B5%ED%95%9C_%EA%B5%AC%EB%A7%A4_%EC%A6%9D%EB%8C%80_%EB%B0%A9%EC%95%88.ipynb)

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


<br><br><br>

<img width="398" alt="스크린샷 2024-04-14 오후 7 57 33" src="https://github.com/eunyeongkimm/personal_project/assets/101814174/ef0e33df-78d7-40da-b030-804ae519fa00">

