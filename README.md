# 머신러닝 기법을 이용한 논 담수심 추정 시험 연구
## Pounding Depth Prediction Using Machine Learning : A Preliminary Study

DATA SET 가공
  1. NULL을 포함한 행 삭제
  2. 1시간 단위
  3. ΔPD < 0 구간만 추출

DATA SET 구분
  1. 날짜
  2. 용・배수로 수위
  3. 기상데이터
  4. 날짜 + 용・배수로 수위
  5. 용・배수로 수위 + 기상데이터
  6. 날짜 + 기상데이터
  7. 날짜 + 용・배수로 수위 + 기상데이터
  
  ###### *날짜 = DoY(Day of Year)와 데이터 시작 값을 0을 기준으로 했을 때의 값 (1hour = 약 0.04)
