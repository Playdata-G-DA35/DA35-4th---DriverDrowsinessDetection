# 딥러닝 활용 졸음운전 실시간 감지 모델 개발

## 1. 주제

딥러닝을 활용한 졸음운전 실시간 감지 

## 2. 프로젝트 목적 및 목표

- 목적 : 졸음운전 사고로 인해 인명피해와 교통 혼잡 문제를 막기 위해 운전 중 졸음 상태를 실시간으로 감지해 사고를 예방
- 목표 : 실시간 졸음 운전 감지 시스템 개발

## 3. 세부 프로젝트 진행 
- 선행 연구 검토 : 졸음운전 감지 모델 개발을 위한 다양한 데이터셋, 모델링 기법 고려
- **주제**
  1. 운전자 얼굴 좌표의 시계열 분석을 통한 상태 파악 
  2. 눈 이미지 데이터의 CNN 활용한 졸음 감지 모델 개발
->  두 모델의 성능 및 활용도 비교 가능
  
|세부주제|데이터|주요 모델링 기법|
|--|------|------|
|1|운전자 얼굴이미지|LSTM 시계열 분석, 다중분류|
|2|감은 눈/뜬 눈 이미지|CNN, 이진분류|

## 4. 팀원과 담당업무 
|세부주제|팀원|담당업무|
|--|------|------|
|1|김세찬|데이터 전처리 및 학습데이터 생성, 모델 학습, 모델 적용 및 테스트, 발표|
|1|하승주|데이터 전처리 및 학습데이터 생성, 모델 학습, 모델 적용 및 테스트, 보고서 작성|
|2|김문선|데이터 수집, 전처리, 모델 설계, 학습, 평가, 감지 시스템 개발|
|2|이성재|데이터 수집, 전처리, 모델 설계, 학습, 평가, 감지 시스템 개발|

## 4. 산출물 
1. 세부 프로젝트 1
  - [모델링 기법 보고서](https://github.com/Playdata-G-DA35/DA35-4th---DriverDrowsinessDetection/blob/main/Reports/project1/1_modeling_report.md)
  - [테스트 설계 보고서](https://github.com/Playdata-G-DA35/DA35-4th---DriverDrowsinessDetection/blob/main/Reports/project1/2_test_report.md)
  - [프로세스 검토 보고서](https://github.com/Playdata-G-DA35/DA35-4th---DriverDrowsinessDetection/blob/main/Reports/project1/3_process_report.md)
2. 세부 프로젝트 2
  - [모델링 기법 보고서](https://github.com/Playdata-G-DA35/DA35-4th---DriverDrowsinessDetection/blob/main/Reports/project2/1_modeling_report.md)
  - [테스트 설계 보고서](https://github.com/Playdata-G-DA35/DA35-4th---DriverDrowsinessDetection/blob/main/Reports/project2/2_test_report.md)
  - [프로세스 검토 보고서](https://github.com/Playdata-G-DA35/DA35-4th---DriverDrowsinessDetection/blob/main/Reports/project2/3_process_report.md)

