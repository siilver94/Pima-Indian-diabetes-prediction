# Pima Indians Diabetes Prediction

<br/>

<code><img height = '450'
src = https://github.com/siilver94/Pima-Indian-diabetes-prediction/assets/57824945/29020004-58a1-4d0d-a06c-51714c4c4aa1></code>


## 프로젝트 개요
이 프로젝트는 캐글의 [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) 데이터셋을 사용하여, 기계 학습 모델을 통해 당뇨병 여부를 예측하는 것을 목표로 합니다.

이 데이터셋은 아리조나주에 사는 피마 인디언 여성들의 의료 기록을 기반으로 하며, 연령, 임신 횟수, 인슐린 수치 등의 여러 특성을 포함합니다. 이 프로젝트에서는 데이터 전처리, 탐색적 데이터 분석(EDA), 모델 선택 및 튜닝, 그리고 결과 해석의 전체적인 데이터 분석을 진행하였습니다.

<br/>

## 데이터셋
이 데이터셋은 768명의 피마 인디언 여성들의 건강 및 의료 기록으로 구성되어 있으며, 다음과 같은 특성을 포함합니다:

- 임신 횟수
- 포도당 내성 실험 후 2시간의 혈장 포도당 농도
- 이완기 혈압 (mm Hg)
- 상완 삼두근 피부 두께 (mm)
- 2시간 혈청 인슐린 (mu U/ml)
- 체질량 지수 (체중 kg / (키 m)^2)
- 당뇨병 가족력
- 나이 (년)
- 당뇨병 여부 (0 또는 1)

<br/>

## 분석 방법 및 결과

1. **데이터 전처리**: 결측치 처리, 이상치 탐지 및 제거, 데이터 정규화 등
2. **탐색적 데이터 분석(EDA)**: 각 특성의 분포, 상관 관계 분석, 중요 변수 도출
3. **모델 선택 및 튜닝**: 로지스틱 회귀, 결정 트리, 랜덤 포레스트, 그라디언트 부스팅 등 여러 기계 학습 모델을 실험 및 평가
4. **결과 해석 및 평가**: 모델 성능 평가, 중요 변수 분석, 모델 해석

주요 발견사항에는 당뇨병 예측에 가장 영향력 있는 변수들과 모델의 예측 정확도 향상을 위한 인사이트가 포함됩니다.

<br/>

## 사용 기술
- `Python`
- `Pandas`, `NumPy`
- `Matplotlib`, `Seaborn`
- `Scikit-learn`

<br/>

## 리뷰 및 회고

이 프로젝트를 통해  단순히 데이터를 처리하고 모델을 구축하는 기술적인 부분보다 시각화를 통해 답을 찾아내는 과정에서 깊은 만족감과 성취감을 느꼈습니다. 특히, Pima Indians Diabetes 데이터셋을 분석하며 다음과 같은 중요한 인사이트를 얻었습니다:

- 데이터의 질과 전처리의 중요성: 결측치와 이상치의 적절한 처리가 모델의 성능에 큰 영향을 미칩니다.
- 모델의 복잡성과 해석 가능성 간의 균형: 복잡한 모델이 더 좋은 성능을 보일 수 있지만, 해석 가능성 또한 중요합니다.

### 겪었던 어려움과 극복 과정

- **데이터의 결측치와 이상치 처리**: 데이터 전처리 과정에서 결측치와 이상치를 어떻게 처리할지 결정하는 것이 어려웠습니다. 이를 극복하기 위해, 다양한 통계적 방법과 대체 전략을 실험하여 최적의 방법을 찾았습니다.
- **적절한 모델 선택**: 다양한 모델 중에서 프로젝트 목표에 가장 적합한 모델을 선택하는 것은 도전적이었습니다. 이를 위해 여러 모델을 비교 분석하고, 교차 검증을 통해 모델의 일반화 성능을 평가함으로써 최종 모델을 선정했습니다.

### 개인적인 성장

이 프로젝트를 통해, 데이터 분석 및 모델링과 특히 시각화의 중요성에 대해 알게 되었습니다. 뿐만 아니라, 문제 해결 과정에서의 끈기와 창의적인 사고 방식이 중요함을 깨달았습니다. 무엇보다, 실제 의료 데이터를 분석하며 데이터 분석이 실세계 문제를 해결하는 데 얼마나 강력한 도구가 될 수 있는지 실감했습니다.
