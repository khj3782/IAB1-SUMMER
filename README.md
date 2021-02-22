# IAB 실무응용1 코딩 기술서
IoT, 인공지능, 빅데이터(IAB)의 실무응용1 개인 프로젝트 (2020년 하계)<br>
> 연구자: 지구환경과학부/연합전공 인공지능반도체공학 김현진<br>
> 연구 주제: 무엇이 음원 차트 순위를 결정하는가<br>
> 연구 기간: 2020.06.22. Mon.~2020.07.25. Sat.<br>
> 링크: [서울대학교 글로벌공학교육센터 GECE](http://gece.snu.ac.kr/gecexe/index.php?mid=gece_lms&category=51919&document_srl=52852)

## 무엇이 음원 차트 순위를 결정하는가
- 연구 목표: 차트 하위권에 머무는 음원과 상위권으로 역주행하는 음원의 차이를 만드는 요소 확인
- 연구 대상: 2019년, 차트에 5주 이상 머물렀던 국내 음원

## 개요
1. 데이터 수집 및 전처리
2. k-means clustering을 통해 상위권/하위권/역주행 음원 분류
3. sentiment analysis를 이용해 노래 가사의 긍정/부정 판단
4. 히트맵을 그려 수집한 feature간 관계 확인
5. Random Forest와 Decision Tree

참고한 페이지
> https://wikidocs.net/44249
> https://www.ranks.nl/stopwords/korean
