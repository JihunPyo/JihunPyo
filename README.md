![header](./assets/header.svg)

### Research ideas into reliable AI systems

> LLM/RAG 효율화 연구부터 Computer Vision 모델, 사용자에게 전달되는 AI 서비스까지 구현하는 AI Engineer 표지훈입니다.

<a href="https://github.com/JihunPyo" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=JihunPyo&style=flat-square&color=2563EB" alt="profile views"/>

---

## Tech Stack

### Strong

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

### Exploring

![Computer Vision](https://img.shields.io/badge/Computer%20Vision-0F766E?style=flat-square)
![OCR](https://img.shields.io/badge/OCR-2563EB?style=flat-square)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-F59E0B?style=flat-square)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-DC2626?style=flat-square)
![LLM](https://img.shields.io/badge/LLM-1D4ED8?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-0F766E?style=flat-square)
![ML Systems](https://img.shields.io/badge/ML%20Systems-7C3AED?style=flat-square)

### Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Conda](https://img.shields.io/badge/Conda-44A833?style=flat-square&logo=anaconda&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-111111?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)

---

## Areas of Interest

| Area | Keywords | Focus |
|---|---|---|
| LLM & RAG | Dynamic Retrieval, Hidden State, Context Management | LLM 내부 상태를 활용한 retrieval timing과 추론 효율화 연구 |
| Computer Vision | Object Detection, Tracking, Pose Estimation | 영상 기반 문제를 탐지, 추적, 추론 파이프라인으로 해결 |
| OCR & Document AI | PaddleOCR, Skeletonization, Stroke Extraction | 문서 이미지의 구조와 획 정보를 분석하고 재구성 |
| Machine Learning | Classification, Inference Pipeline, Experiment Logging | 모델 실험을 재현 가능한 코드와 기록으로 관리 |
| AI System Engineering | FastAPI, React, Deployment | 모델을 API·UI·배포 환경까지 연결해 실제 서비스로 구현 |
| Algorithm | BOJ, C++, Problem Solving | 문제 해결력을 높이기 위한 알고리즘 풀이 누적 |

---

## Featured Projects

| Year | Project | Topic | Description | Link |
|---|---|---|---|---|
| 2026 | RAMO | LLM, Context Management, Full Stack | LLM 대화를 브랜치로 분리하고 관계를 그래프로 시각화해 컨텍스트를 관리하는 AI 채팅 서비스 | [GitHub](https://github.com/JihunPyo/ramo) · [Service](https://ramo-pi.vercel.app) |
| 2026 | Handwriting2Ink | OCR, Document Image Processing | 손글씨 이미지에서 획 경로를 복원해 Goodnotes에서 편집 가능한 ink stroke로 변환하는 서비스 | [GitHub](https://github.com/JihunPyo/Handwriting2Ink) |
| 2025 | DisabledParkingGuard | Computer Vision, Gait Analysis | CCTV 영상에서 하차 보행자의 보행 특성을 분석해 장애인 전용 주차구역 부정 이용 가능성을 추정하는 프로토타입 | [GitHub](https://github.com/JihunPyo/Disabled-Parking-Guard) |

---

## Project Notes

### RAMO

- LLM 대화의 꼬리질문을 브랜치로 분리하고 대화 관계를 그래프로 시각화합니다.
- 브랜치 단위 컨텍스트 관리와 사용자별 AI 활용 리포트 생성 흐름을 설계했습니다.
- 예시 시나리오 기반 시뮬레이션에서 기존 방식 대비 최대 17.1%의 토큰 절감 가능성을 확인했습니다.
- React·Vite 프론트엔드와 FastAPI·PostgreSQL 백엔드를 연동해 실제 서비스로 배포했습니다.

### Handwriting2Ink

- Zhang-Suen skeletonization과 stroke extraction을 이용해 문서 이미지의 중심선을 분석합니다.
- PaddleOCR 기반 text/shape crop 분리를 통해 OCR layout pilot을 실험합니다.
- crop별 stroke를 원본 좌표계에 재배치하는 방식으로 손글씨 재구성 가능성을 검증합니다.

### DisabledParkingGuard

- ROI 지정, YOLO 기반 객체 탐지, BoT-SORT 기반 추적, MediaPipe Pose 기반 3D pose 추출 흐름을 포함합니다.
- LSTM 기반 보행 분류 inference를 통해 행동 정보 기반 판단 가능성을 실험합니다.
- 얼굴, 신원, 번호판보다 보행 패턴 중심의 비식별적 판단 기준을 다룹니다.

---

## Learning Log

| Track | Current Focus |
|---|---|
| LLM & RAG | Hidden state 기반 dynamic retrieval timing과 context 효율화 |
| Computer Vision | Detection, Tracking, Pose Estimation pipeline 구성 |
| OCR | 문서 이미지 전처리, OCR crop, skeleton 기반 stroke 분석 |
| ML Engineering | 실험 코드 구조화, 모델 추론 파이프라인과 AI 서비스 구현 |
| Algorithm | C++ 기반 문제풀이와 구현 역량 강화 |

---

## Awards

| Date | Award |
|---|---|
| 2026.08 | **대상(1위)** — Kyunghee Valley Program 창업 경진대회 Demo Day |
| 2026.08 | **우수상** — KCC 2026 학부생 논문 부문, 한국정보과학회 |
| 2026.07 | **최우수상(1위)** — KHUDA 제1회 정기학술제 |
| 2025.12 | **최우수상(1위)** — KHUDA 9th 심화프로젝트 컨퍼런스 |

---

## Current Focus

- hidden state를 활용한 동적 RAG retrieval timing과 LLM inference 효율화
- AI 모델을 API·UI·배포 환경까지 연결하는 ML/AI system engineering
- OCR, document AI와 multi-frame low-resolution vision

---

## Let's Connect

> LLM/RAG, 컴퓨터 비전, OCR과 실제 사용자에게 전달되는 AI 시스템 개발에 관심이 있습니다.

<a href="https://github.com/JihunPyo" target="_blank"><img src="https://img.shields.io/badge/GitHub-JihunPyo-181717?style=flat-square&logo=github&logoColor=white"/></a>

---

## English Version

### About Me

I am an AI engineer who turns research ideas in LLM/RAG and computer vision into reliable, user-facing systems.

### Current Focus

- Dynamic RAG retrieval timing using hidden states and efficient LLM inference
- Computer vision pipelines with detection, tracking, and pose estimation
- OCR and document image analysis with skeleton-based stroke extraction
- End-to-end AI systems spanning model pipelines, APIs, user interfaces, and deployment

### Featured Work

- **RAMO**: branch-based LLM conversation management, graph visualization, and AI usage reports
- **Handwriting2Ink**: document image preprocessing, skeletonization, stroke extraction, and OCR layout experiments
- **DisabledParkingGuard**: CCTV-based gait analysis prototype for accessible parking misuse detection
- **ICPR LRLPR Competition**: experiments for multi-frame low-resolution license plate recognition

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:14B8A6,50:2563EB,100:1E3A8A&height=120&section=footer)
