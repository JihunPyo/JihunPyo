<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1D4ED8,100:0F766E&height=210&section=header&text=Jihun%20Pyo&fontSize=50&fontColor=ffffff&animation=fadeIn&desc=AI%20Engineer%20%7C%20LLM%20%26%20RAG%20%7C%20Computer%20Vision&descAlignY=72&descSize=18)

### Research ideas into reliable AI systems

LLM/RAG 효율화 연구부터 Computer Vision 모델, 사용자에게 전달되는 AI 서비스까지 구현하는 AI Engineer 표지훈입니다.

[![GitHub](https://img.shields.io/badge/GitHub-JihunPyo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/JihunPyo)
[![Email](https://img.shields.io/badge/Email-pyojihun80%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:pyojihun80@gmail.com)
![Profile Views](https://komarev.com/ghpvc/?username=JihunPyo&style=flat-square&color=1D4ED8)

</div>

## About Me

- 경희대학교 소프트웨어융합학과 데이터사이언스 트랙에 재학 중이며, GPA는 **4.06/4.5**이다.
- 경희대학교 KDST 학부연구생으로 **hidden state 기반 동적 RAG 시점 결정**을 연구하고 있다.
- 모델 실험에 머무르지 않고 데이터 처리, API, 프론트엔드와 배포까지 연결해 **동작하는 AI 시스템**을 만드는 데 집중한다.
- 2026 ICPR Low Resolution License Plate Recognition Competition 학부생 팀을 이끌고 있다.
- 경희대학교 데이터분석·AI 중앙동아리 **KHUDA 10기 회장**으로 70명 규모의 학회를 운영하고 있다.

## Featured AI Projects

### 1. [RAMO](https://github.com/JihunPyo/ramo) — LLM 대화 흐름 시각화 및 AI 활용 리포트

> Team Leader · Full-stack Developer · Presenter | 2026.06 - Present

- 꼬리질문으로 복잡해지는 LLM 대화를 브랜치로 분리하고, 대화 간 관계를 그래프로 시각화하는 서비스를 개발했다.
- 대화 컨텍스트를 브랜치 단위로 관리하고 사용자별 AI 활용 리포트를 생성하는 흐름을 설계했다.
- 예시 시나리오 기반 시뮬레이션에서 기존 방식 대비 **최대 17.1%의 토큰 절감 가능성**을 확인했다.
- React·Vite 프론트엔드와 FastAPI·PostgreSQL 백엔드를 연동하고 Vercel·Railway에 배포했다.
- **2026 Kyunghee Valley Program 대상**, **KHUDA 제1회 정기학술제 최우수상**을 수상했다.

[Service](https://ramo-pi.vercel.app) · [Frontend](https://github.com/JihunPyo/ramo) · [Backend](https://github.com/uiuuymin/ramo) · [API Docs](https://chatbotbranchproject-production.up.railway.app/docs)

### 2. [Handwriting2Ink](https://github.com/JihunPyo/Handwriting2Ink) — 손글씨 이미지의 편집 가능한 획 복원

> Team Leader · Core Algorithm Developer · Presenter | 2025.03 - 2025.06

- 손글씨 이미지를 Goodnotes에서 다시 편집할 수 있는 ink stroke 좌표열로 변환하는 규칙 기반 알고리즘을 개발했다.
- PaddleOCR로 레이아웃을 분리하고, Zhang-Suen thinning과 8-neighbor graph를 이용해 skeleton 기반 stroke를 추출했다.
- FastAPI 비동기 job orchestration, macOS GUI worker, SwiftUI iPad 클라이언트를 연결해 end-to-end 서비스를 구현했다.
- 연구 결과를 KCC 2026 학부생 논문으로 발표해 **한국정보과학회 우수상**을 수상했다.

[Repository](https://github.com/JihunPyo/Handwriting2Ink) · [Demo](https://youtube.com/shorts/Ik74j1NbrQU) · [Paper](https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE12929802&width=1920)

### 3. [Disabled Parking Guard](https://github.com/JihunPyo/Disabled-Parking-Guard) — 비정상 보행 분류 기반 주차구역 부정이용 탐지

> Data Preprocessing · Model Architecture · Presenter | 2025.12

- YOLO 객체 탐지, BoT-SORT 추적, MediaPipe 3D pose estimation과 LSTM 분류를 하나의 영상 추론 파이프라인으로 구성했다.
- 관절 선택, translation 제거, scale normalization과 sequence length 정규화를 적용해 pose sequence를 모델 입력으로 변환했다.
- 프로젝트 평가 데이터에서 정상·비정상 보행 분류 **약 97% 정확도**를 달성했다.
- 얼굴이나 번호판 대신 보행 패턴을 사용하는 비식별적 판단 보조 방식을 제안했다.

### 4. [ICPR 2026 LRLPR Competition](https://github.com/JihunPyo/2026ICPR-LRLPR-Competition) — 저해상도 번호판 인식

> Undergraduate Team Lead | 2026 - Present

- multi-frame 저해상도 번호판 인식 성능 향상을 위한 복원·인식 방법론을 실험하고 있다.
- 실험 조건과 결과를 재현 가능한 형태로 관리하며 팀의 모델 개발 방향을 조율하고 있다.

## Additional ML Work

- **실시간 날씨 기반 비행기 연착 확률 예측**: 시계열 데이터 분석, boosting tree 모델과 실시간 날씨 API를 결합했다.

## Tech Stack

### AI / Machine Learning

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![PaddleOCR](https://img.shields.io/badge/PaddleOCR-0062B0?style=flat-square)
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat-square)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square)

### Data / Scientific Computing

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)

### Engineering

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

### Workflow

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Conda](https://img.shields.io/badge/Conda-44A833?style=flat-square&logo=anaconda&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-111111?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)

## Awards

| Date | Award |
|---|---|
| 2026.08 | **대상(1위)** — Kyunghee Valley Program 창업 경진대회 Demo Day |
| 2026.08 | **우수상** — KCC 2026 학부생 논문 부문, 한국정보과학회 |
| 2026.07 | **최우수상(1위)** — KHUDA 제1회 정기학술제 |
| 2025.12 | **최우수상(1위)** — KHUDA 9th 심화프로젝트 컨퍼런스 |

## Current Focus

- hidden state를 활용한 동적 RAG retrieval timing과 LLM inference 효율화
- AI 모델을 API·UI·배포 환경까지 연결하는 ML/AI system engineering
- OCR, document AI와 multi-frame low-resolution vision

<div align="center">

AI 연구와 실제 사용자에게 전달되는 제품 사이의 간극을 줄이는 엔지니어를 지향한다.

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:0F766E,50:1D4ED8,100:0F172A&height=120&section=footer)

</div>
