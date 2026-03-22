# 👋 Kolmar-KAIST Research

콜마-KAIST 공동 연구 프로젝트 레포지토리입니다.  
본 조직은 **혼합물(Mixture) 기반 물성 예측 모델 연구 및 시스템 개발**을 목표로 합니다.

---

## 🧱 Core Repositories (기반 시스템)

> 연구의 핵심 구성 요소입니다. 모든 프로젝트는 아래 구조를 기반으로 합니다.

### 🔹 Learning
- **[Kolmar Learning](https://github.com/kolmar-korea/KolmarLearning)**  
  → 학습 전략 및 트레이닝 파이프라인 구현

### 🔹 Models
- **[Kolmar Models](https://github.com/kolmar-korea/KolmarModels)**  
  → 모델 아키텍처 정의 (Transformer, Mixing 기반 구조 등)

### 🔹 Data
- **[Kolmar Data](https://github.com/kolmar-korea/KolmarData)**  
  → 데이터셋 구조 및 전처리 정의

---

## 🚀 Projects (응용 및 연구 프로젝트)

> Core 레포를 기반으로 한 실제 연구 및 제품화 프로젝트입니다.

### 📱 Application
- **[KolmarApp-2025](https://github.com/kolmar-korea/KolmarApp-2025)**  
  → KAIST 2025 프로젝트용 애플리케이션

### 🧪 Research
- **[Mixing-Former](https://github.com/kolmar-korea/MixingFormer)**  
  → 혼합물 표현 학습을 위한 Transformer 기반 모델 연구

- **[Kolmar-Blend](https://github.com/kolmar-korea/KolmarBlend)**  
  → 물성 레이블 정보를 통합한 2차 모델 개선 연구

---

## 🧭 Repository Structure Overview

```text
Kolmar-KAIST
│
├── KolmarLearning   # Training / Optimization
├── KolmarModels     # Architecture
├── KolmarData       # Dataset
│
├── MixingFormer     # Core research model
├── KolmarBlend      # Extended model
└── KolmarApp-2025   # Application
