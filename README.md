# 수정필요

<div align="center">
  <img height="150" src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif"  />
</div>

###

<div align="center">
  <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo"  />
  <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="youtube logo"  />
  <img src="https://img.shields.io/static/v1?message=Twitter&logo=twitter&label=&color=1DA1F2&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="twitter logo"  />
</div>

###

<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=maurodesouza.maurodesouza&"  />
</div>

###

<h1 align="center">hey there 👋</h1>

###

<h3 align="left">👩‍💻  About Me</h3>

###

<p align="left">I'm ... from ....<br><br>- 🔭 I’m working as ...<br>- 📚 I'm currently learning ...<br>- ⚡ In my free time I ...</p>

###

<h3 align="left">🛠 Language and tools</h3>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" height="40" alt="go logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" height="40" alt="rust logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ruby/ruby-plain-wordmark.svg" height="40" alt="ruby logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dot-net/dot-net-plain-wordmark.svg" height="40" alt="dot-net logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain-wordmark.svg" height="40" alt="firebase logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-line-wordmark.svg" height="40" alt="amazonwebservices logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/circleci/circleci-plain.svg" height="40" alt="circleci logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" height="40" alt="kubernetes logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-plain-wordmark.svg" height="40" alt="docker logo"  />
</div>

###

<h3 align="left">🔥   My Stats :</h3>

###

<div align="center">
  <img src="https://streak-stats.demolab.com?user=maurodesouza&locale=en&mode=daily&theme=dark&hide_border=false&border_radius=5&order=3" height="220" alt="streak graph"  />
</div>

###


# 🌟 프로젝트 포트폴리오 - Miho Park

안녕하세요! 저는 **산업공학 + 컴퓨터 프로그래밍**을 전공한 개발자 박지영(Miho)입니다.  
데이터 분석과 웹/AI 프로젝트 경험을 바탕으로 **실용적인 서비스와 연구 개발**을 진행하고 있습니다.

---

## 🔹 기술 스택

| 분야 | 기술 |
|------|------|
| Backend | Spring Boot, Django, Flask, Node.js |
| Frontend | React, Flutter |
| Database | MySQL, Redis, MongoDB |
| AI/ML | PyTorch, TensorFlow, OpenCV, LLM, Grad-CAM |
| DevOps/Cloud | AWS (Lightsail, EC2, RDS), Docker, Jenkins, GitHub Actions |
| Tools | Git, Postman, VSCode, PyCharm |

---

## 🔹 프로젝트

### 1️⃣ DE-Fake it (DeepFake Detection & Explainable AI + LLM)
**기간:** 2025.02 ~ 진행중  
**기술 스택:** Python, PyTorch, CNN-LSTM, Grad-CAM, React, Django, JSONL, LLM fine-tuning  

**프로젝트 소개:**  
딥페이크 영상 여부를 판단하고, Grad-CAM 기반 ROI 분석 결과를 LLM으로 자연어 설명하는 웹 서비스.

**주요 기능:**
- 영상 업로드 후 첫 프레임 캡처 및 Grad-CAM 시각화
- 얼굴 특징별 활성도 분석 및 top-10 프레임 선택
- ROI 기반 점수 계산 후 LLM으로 설명 생성
- Confusion matrix, ROC, t-SNE 시각화 포함한 평가 파이프라인

**성과 및 학습:**  
- ResNeXt50, Xception, EfficientNet-B0 모델 활용 멀티태스크 학습
- CNN-LSTM 구조로 **이진 및 다중 분류** 동시 수행
- 논문 실험용 데이터셋(FaceForensics++, DFDC, Celeb-DF) 활용 cross-dataset 평가

**📌 시각화 예시:**
![Grad-CAM 예시](./assets/gradcam_example.png)

---

### 2️⃣ Vitacheck (건강 보조제 추천 플랫폼)
**기간:** 2025.01 ~ 진행중  
**기술 스택:** Spring Boot, MySQL, Redis, QueryDSL, AWS EC2/RDS, Docker  

**프로젝트 소개:**  
사용자 맞춤 건강 보조제 추천, 성분별 검색 및 복용량 관리 기능 제공.

**주요 기능:**
- 성분/브랜드 기반 추천 및 대체 식품 검색
- Redis 기반 인기 순위 및 사용자 검색 로그 관리
- DDD/Hexagonal 구조 적용, Ports/Adapters 활용
- 배치 스케줄러 및 CI/CD 자동화 (Jenkins/GitHub Actions)

**📌 데이터 구조 예시:**
```json
{
  "userId": 12345,
  "recommendedSupplements": [
    {"name": "Omega3", "dosage": "1000mg"},
    {"name": "Vitamin D", "dosage": "2000IU"}
  ]
}
```


----------


