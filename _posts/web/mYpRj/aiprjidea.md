# 부스트캠프 ai tech 프로젝트 분석
## 주제
### NLP
- 하루의 마침표: 일기 텍스트에서 감정 추출 후 그걸 기반으로 컨텐츠를 추천하여 하나의 피드를 만듦.
  - cloud Server: google cloud platform, mongoDB
  - Local Server
    - FE: streamlit, html, css
    - BE: FastAPI
    - Model: KcElectra
- 강의 음성 데이터 요약 및 키워드 추출: STT(Speech-to-Text)
  - STT모델: espnet-asr
  - FE: streamlit, typeguard, espnet, transformers, pydub
  - BE: pytube, moviepy, kobart, konlpy, sentence_transformers, fastapi, uvicorn pydub

### RecSys
### CV


## 사용하는 기술
### 허깅페이스
  - 트랜스포머/데이터셋 등의 머신러닝 레퍼런스를 제공하는 인공지능 플랫폼
    - 트랜스포머 라이브러리: 트랜스포머 모델을 만들때, 코드를 작성할 필요없이 라이브러리를 가져오기만 하면 됨
    - 허깅페이스 허브: git 기반 플랫폼(호스팅,버전관리,소규모웹앱,데이터셋 등)
    - 데이터셋: 빅데이터 프로세싱 라이브러리
    - 인터페이스 API, 오토트레인, 데일리페이퍼, 스페이스
  - 오픈 소스 커뮤니티: 배포->리뷰->수정
### STT 모델 - ESPNet
- 기초 지식: HMM(은닉 마르코프 모형)


# 프로젝트 구상
- 생성 ai기반 블로깅 서비스
- nlp활용 미디어 비평 서비스
- cv기반 패션 분석 서비스
- 간단한 게임, 채팅, 다이어리, 일정, 컨텐트, 노션페이지 -> 소셜, couple
- 플래너, 투두, 캘린더, 채팅, 게시판, 노션UI를 활용한 차트UI -> 소셜, selfmotiv