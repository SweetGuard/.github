# Sweet Home Project

## 프로젝트 개요
Sweet Home은 MFCC, YOLO, Mediapipe, Transformer를 활용해 가정 내 이상 행동(쓰러짐, 범죄 등)을 탐지하는 AI 시스템입니다. 
Android 앱과 FastAPI 서버를 연동하여 음성 및 영상 데이터를 실시간으로 처리합니다.

## 주요 기능
- Android 앱: 음성 데이터 백그라운드 수신 및 실시간 서버 통신.
- YOLO, Mediapipe, Transformer: 영상 데이터 처리 및 이상 행동 탐지.
- MFCC: 음성 데이터 처리
- FastAPI 서버: 음성 및 영상 모델과 연동하여 실시간 알림 전송.

## 실행 방법
1. **Android 앱**:
   - Android Studio에서 `main.kt` 실행.
2. **FastAPI 서버**:
   - Python 환경에서 `app.py` 실행.
3. **Data Processing & Model Training**  
   - 모델 학습 코드는 kaggle 및 colab으로 관리.
   - 모델 학습 과정과 결과는 PPT 및 보고서로 정리.

## 참고 자료
- **모델 코드**
- **시연 영상 및 프로젝트 설명**: [PPT]
