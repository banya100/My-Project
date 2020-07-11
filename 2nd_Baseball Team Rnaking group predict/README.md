# 프로젝트 소개
- 직업훈련교육 두번째 프로젝트
- 데이터 수집 및 모델링
  
## 프로젝트 일정
- 기간 : 2020.5.12 ~ 5.15
- 발표 : 2020.5.18
- 인원 : 인원4(데이터수집,시각화,보고서작성 및 발표)

## 데이터 정의서
- 데이터 수집 : 
- 서울시 지하철 호선별 역별 유무임 승하차 인원정보 화일
  - 2015년 1월 ~ 2020년 4월 자료
- 서울시 역코드로 지하철역 위치 조회 화일
  - 929개 전철역코드와 위도경도 정보

## 파일구성
```
Docs : 경진대회 보고서(PPT)
Data : 수집데이터 2종
Source : 시각화
```
- Docs : 경진대회 보고서(지하철_무임승차_현황분석.ppt)
- Data : subway.csv, 서울시 역코드로 지하철역 위치조회.csv
- Source : 전처리, 시각화, 지도시각화

## 주요이슈(History)
- 05.12 : 데이터 다운로드([서울시 열린데이터 광장](https://data.seoul.go.kr/)) 및 데이터 현황 탐색
- 05.13 : 데이터 전처리(중복행 제거, 9호선 개발단계별 역사명 상이한것 수정)
          역사별 위도 및 경도 데이터 병합
- 05.14 ~ 05.15 : 다양항 방식의 시각화 라이브러리 활용한 시각화 진행
- 05.16 : 보고용 PPT작성
- 05.18 : 보고서 발표

## 개발환경 Spec
- Programming Language : Python 3.7.1
- Package : pandas, matplotlib, seaborn, folium, plotly

## 주요 참고자료 (논문)

## 연락처
- HP : 010-8185-0984
- Email : banya197400201@gmail.com