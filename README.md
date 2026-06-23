# 📊 Data Analysis & Machine Learning Portfolio

데이터 전처리(Preprocessing), 통계적 분석, 머신러닝 알고리즘 및 딥러닝 모델링 성능 비교를 위한 통합 데이터 분석 포트폴리오 저장소입니다. 각 주차별 핵심 분석 주제는 독립된 브랜치에서 상세 코드와 함께 확인할 수 있습니다.

---

## 📌 주요 프로젝트 및 분석 브랜치 요약

### 1. 당뇨병 예측 딥러닝 이진 분류 모델 
* **브랜치:** `feat/diabetes-classification`
* **주요 내용:** `Pima Indians Diabetes` 데이터셋 기반 당뇨병 예측 파이프라인 구축
* **핵심 역량:** `StandardScaler` 피처 스케일링, 과적합 방지를 위한 `Dropout` 아키텍처 설계, `ModelCheckpoint` 및 `EarlyStopping`을 활용한 최적의 딥러닝 하이퍼파라미터 튜닝 수행.

### 2. 결측치(Missing Value) 통계적 메커니즘 및 보간 분석
* **브랜치:** `feat/missing-data-analysis` (또는 `feat/missing-value-imputation`)
* **주요 내용:** 결측치 유형(MCAR, MAR, MNAR)별 통계적 특성 분류 및 `bike_sharing_daily.csv` 활용 실습
* **핵심 역량:** 기계적인 데이터 삭제를 지양하고, 무작위·비무작위 결측 메커니즘을 수학적으로 판별하여 데이터 왜곡을 최소화하는 최적의 보간법(Imputation) 전처리 설계 역량 확보.

### 3. 다중 유형 이상치 탐지(Anomaly Detection) 알고리즘 비교
* **브랜치:** `feat/anomaly-detection`
* **주요 내용:** 극단적·군집형·무작위 이상치 시뮬레이션 및 비지도 학습 알고리즘 비교 분석
* **핵심 역량:** 로컬 밀도를 반영하는 `LOF`와 글로벌 격리를 수행하는 `Isolation Forest` 모델 구축. AUC-ROC 및 AUC-PR 지표의 정량적 평가와 산점도 시각화를 결합하여 데이터 분포에 따른 알고리즘의 수학적·기하학적 적합성 도출.

---

## 🛠️ Tech Stacks
* **Languages & Libraries:** Python, TensorFlow, Keras, NumPy, Pandas, Scikit-learn
* **Tools:** Jupyter Notebook, Git/GitHub, VS Code
