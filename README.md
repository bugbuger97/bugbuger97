<h2>Hi, I'm Junho Paeng(팽준호) 👋</h2>
📄 **[Portfolio (PDF)](./Portfolio.pdf)**

---

### 🎓 Education & Experience
| 기간 | 내용 |
|---|---|
| 2026.08 | 인하대학교 인공지능공학과 졸업 (B.S. in AI Engineering) |
| 2026.01 ~ 2026.06 | 한국철도기술연구원 철도교통AX본부 철도AI융합연구실 현장실습 |
| 2024.12 ~ 2025.06 | 인하대학교 멀티모달 AI 연구실 학부연구생 |

### 🏆 Awards
- **2024.08** K-Software Showcase 신세계I&C 이사상
- **2024.12** 인하대학교 오픈소스SW 페스티벌 우수상
- **2025.03** 인하대학교 인공지능공학과 성적우수상

---

### 🚀 Projects

#### 01. Walk-Thru R&D · 비접촉식 개찰 시스템 `2026.01 – 2026.06`
스테레오 카메라와 무선측위를 정합해 부정승차자를 실시간 판별하는 시스템의 Vision 파트 담당
- RANSAC 기반 바닥면 추출로 카메라 Roll/Pitch/높이 **자동 Calibration**
- LUT Backward Mapping으로 6m×10m 영역 **실시간 Top-View(IPM)** 생성 (1cm/px)
- RT-DETR 머리 검출 + ByteTrack 추적 → 무선측위 좌표계 정합, Streamlit 대시보드 구현

`Python` `OpenCV` `RT-DETR` `ByteTrack` `FastAPI` `Streamlit`

#### 02. AI 도로 파손 감지 및 관리 시스템 `2024.07 – 2024.08` · 🏆 신세계I&C 이사상
스마트폰 On-Device AI로 도로 파손을 탐지하고, 서버에서 파손 유형을 분류하는 신고·관리 서비스 (팀장)
- YOLOv8s → TFLite 변환으로 CameraX 화면에서 실시간 탐지
- 서버에서 Real-ESRGAN 화질 복원 후 EfficientNet-B3로 **15개 파손 유형 분류**
- 모델별 EC2 분리 배치 + httpx 비동기 통신, 관리자 웹·카카오맵 연동까지 End-to-End 구현

`Python` `YOLOv8` `TFLite` `EfficientNet-B3` `Real-ESRGAN` `Android` `AWS`

#### 03. 피부 지킴이 App `2024.11 – 2024.12` · 🏆 오픈소스SW 페스티벌 우수상
사진 한 장으로 피부 질환 6종을 On-Device 분류하고, 응급처치와 인근 피부과를 안내하는 헬스케어 앱 (팀장)
- 크롤링 노이즈 제거를 위한 **9-Cell 피부색·분포 필터** 설계
- MobileNet V3 전이학습 및 TFLite 변환, GPT 기반 응급처치 안내

`Python` `OpenCV` `MobileNet V3` `TFLite` `Kotlin` `OpenAI API`

#### 04. Video Grounding 모델 성능 개선 `2024.12 – 2025.06`
자연어 질의에 맞는 영상 구간을 찾는 DETR 모델에서 Quality Head의 오답 고득점 문제 개선
- Attention Map 분석으로 Feature 편향·Encoder 정렬 오류·Quality Head 순위 역전 문제 발견
- IoU(80%)와 Ratio(20%)를 결합한 **Quality Loss** 설계
- QVHighlights val 기준 BAM-DETR 대비 **R1@0.7 +1.55%p**, mAP@0.75 +0.47%p

`Python` `PyTorch` `DETR` `CLIP` `SlowFast`

---

### 🛠️ Tech Stacks
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=PyTorch&logoColor=white">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=TensorFlow&logoColor=white">
  <img src="https://img.shields.io/badge/Keras-D00000?style=flat&logo=Keras&logoColor=white">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=NumPy&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=Pandas&logoColor=white">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=OpenCV&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=FastAPI&logoColor=white">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=Streamlit&logoColor=white">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=C%2B%2B&logoColor=white">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=Kotlin&logoColor=white">
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat&logo=Android&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=Linux&logoColor=black">
</p>

### 🧑‍💻 Contact
<a href="mailto:junopaeng@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat&logo=Gmail&logoColor=white"></a>
