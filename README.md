# GapAcceptanceModel_YOLOv8 (영상 데이터를 활용한 교차로에서의 이륜차 Gap Acceptance 행태 비교 연구)

개요 :
본 프로젝트는 T자 교차로에서 우회전 또는 직진하는 이륜차와 사륜차의 조합에 따라 간격 수락 모형을 구축합니다. 이를 바탕으로, 각 차종별 조합을 분석 및 비교하여 I2V 서비스에 반영해 교차로 안전성을 향상 시키는 연구를 진행합니다. 

주요 기능(영상처리) 
- 객체 탐지: Ultralytics YOLOv8 기반
- 객체 추적: DeepSORT + MARS feature extractor
- 속도 계산: 프레임별 좌표 기반 이동 거리 산출
- 데이터 저장:CSV 파일로 객체 ID별 주행 방향/속도/차간간격/대기시간 등 기록
  
실행 코드 
- 'Day&Nightv8_motorModel.ipynb' : 이륜차 객체 인식률을 높이기 위해, 기존 YOLOv8모델에 전이학습 진행하는 과정.
- 'YOLO_Deeosort_v2_FINAL.ipynb' : 전이학습한 모델로 객체 인식 및 관측 변수 추출.
- 'Description.ipynb' : 간단한 기술통계 시각화

결과 HTML(html 폴더 내부) 
- 'Day+Nightv8_motorModel.html'
- 'YOLO_Deepsort_v2_FINAL.html'
- 'Description.html'

시연 GIF 
- 'yolov8.gif' : 촬영 장소의 낮/밤 영상 데이에 모델을 적용 시킨 영상
  
> 본 저장소는 포트폴리오 열람용입니다. 원 데이터는 용량/라이선스 사유로 비공개이며,
> 결과 재현 대신 코드·출력(COLAB /HTML/GIF)을 제공합니다.
