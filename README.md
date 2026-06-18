# Daily Study Log - Deep Learning

딥러닝 기초 개념과 모델 학습 흐름을 실습하며 정리한 Jupyter Notebook 저장소입니다.

교육 과정에서 진행한 실습 코드를 기반으로, 회귀 모델부터 이미지 분류, CNN, RNN, 전이학습, Hugging Face Transformers 기반 자연어 처리 모델까지 단계적으로 학습한 내용을 기록했습니다.

이 저장소는 완성형 프로젝트보다는 딥러닝 모델의 기본 구조와 데이터 처리 흐름을 익히기 위한 학습 기록입니다.

---

## 학습 목적

* 딥러닝 모델의 기본 학습 흐름 이해
* 데이터 전처리, 모델 구성, 학습, 평가 과정 실습
* 이미지 데이터와 텍스트 데이터를 활용한 분류 문제 경험
* CNN, RNN, Transformer 계열 모델의 기본 사용 흐름 학습
* Jupyter Notebook 기반 실습 코드 정리

---

## 사용 기술

| 구분                               | 사용 기술                                 |
| -------------------------------- | ------------------------------------- |
| Language                         | Python                                |
| Environment                      | Jupyter Notebook                      |
| Data Processing                  | pandas, NumPy                         |
| Machine Learning / Deep Learning | scikit-learn, TensorFlow/Keras        |
| NLP / Transformer                | Hugging Face Transformers, BERT 계열 모델 |

---

## 주요 학습 내용

### 1. 회귀 및 기본 모델 복습

의료비 예측 데이터를 활용해 선형회귀 모델의 기본 흐름을 복습했습니다.

* 데이터 불러오기
* 특성 확인
* 회귀 모델 학습
* 예측 결과 확인

### 2. 기본 분류 모델 실습

유방암 데이터셋과 손글씨 데이터셋을 활용해 분류 모델의 학습 흐름을 실습했습니다.

* 데이터셋 구성 확인
* 학습용/테스트용 데이터 분리
* 모델 학습 및 예측
* 정확도 등 평가 지표 확인

### 3. 이미지 데이터 전처리 및 CNN 실습

이미지 데이터를 모델에 입력하기 위한 전처리 과정과 CNN 기반 이미지 분류 흐름을 실습했습니다.

* 이미지 데이터 불러오기
* 이미지 크기 조정 및 배열 변환
* 개/고양이 이미지 분류 모델 실습
* 손글씨 데이터 CNN 분류 실습

### 4. 전이학습 실습

Brain Tumor 데이터셋을 활용해 사전학습 모델 기반 전이학습 흐름을 실습했습니다.

* 이미지 분류 문제 구성
* 사전학습 모델 활용
* 다중분류 모델 학습
* 모델 성능 확인

### 5. RNN 계열 모델 이해

시퀀스 데이터를 처리하는 RNN 계열 모델의 기본 구조와 사용 흐름을 학습했습니다.

* Simple RNN 기본 구조 실습
* 순차 데이터 입력 방식 이해
* RNN 계열 모델의 동작 흐름 정리

### 6. Transformer 기반 NLP 실습

Hugging Face Transformers를 활용해 Transformer 계열 모델의 사용 흐름을 실습했습니다.

* Hugging Face Transformers 기본 사용법
* BERT, KoBERT, KoELECTRA, KoBART 등 한국어 모델 실습
* 네이버 영화 리뷰 분석
* 뉴스 카테고리 분류 실습

---

## 파일 구성

```text
DeepLearning/
├── 00_선형회귀_복습(의료비예측).ipynb
├── ex01_딥러닝_맛보기.ipynb
├── ex02_유방암_데이터셋.ipynb
├── ex03_손글씨_데이터_분류.ipynb
├── ex04_1_이미지데이터전처리.ipynb
├── ex04_2_개,_고양이_분류_모델_실습.ipynb
├── ex05_손글씨_데이터_CNN.ipynb
├── ex06_BrainTumor_다중분류(전이학습).ipynb
├── ex07_Simple_RNN_실습.ipynb
├── ex08_RNN_계열_이해하기.ipynb
├── ex09_HuggingFace_Transformers_맛보기.ipynb
├── ex10_Transformer(Bert,_Kobert,_KoElctra,_KoBart)_네이버영화리뷰분석.ipynb
└── ex11_Transformers(뉴스카테고리_분류_실습).ipynb
```

---

## Notebook 설명

| 파일명                                                                | 내용                                    |
| ------------------------------------------------------------------ | ------------------------------------- |
| `00_선형회귀_복습(의료비예측).ipynb`                                          | 의료비 예측 데이터를 활용한 선형회귀 복습               |
| `ex01_딥러닝_맛보기.ipynb`                                               | 딥러닝 모델 학습 흐름 기초 실습                    |
| `ex02_유방암_데이터셋.ipynb`                                              | 유방암 데이터셋 기반 분류 실습                     |
| `ex03_손글씨_데이터_분류.ipynb`                                            | 손글씨 데이터 분류 모델 실습                      |
| `ex04_1_이미지데이터전처리.ipynb`                                           | 이미지 데이터 전처리 과정 실습                     |
| `ex04_2_개,_고양이_분류_모델_실습.ipynb`                                     | 개/고양이 이미지 분류 모델 실습                    |
| `ex05_손글씨_데이터_CNN.ipynb`                                           | CNN 기반 손글씨 이미지 분류 실습                  |
| `ex06_BrainTumor_다중분류(전이학습).ipynb`                                 | Brain Tumor 이미지 데이터 기반 전이학습 실습        |
| `ex07_Simple_RNN_실습.ipynb`                                         | Simple RNN 기본 구조 실습                   |
| `ex08_RNN_계열_이해하기.ipynb`                                           | RNN 계열 모델의 구조와 흐름 정리                  |
| `ex09_HuggingFace_Transformers_맛보기.ipynb`                          | Hugging Face Transformers 기본 사용법 실습   |
| `ex10_Transformer(Bert,_Kobert,_KoElctra,_KoBart)_네이버영화리뷰분석.ipynb` | 한국어 Transformer 모델 기반 네이버 영화 리뷰 분석 실습 |
| `ex11_Transformers(뉴스카테고리_분류_실습).ipynb`                            | Transformer 기반 뉴스 카테고리 분류 실습          |

---

## 정리

이 저장소를 통해 딥러닝 모델의 기본 학습 흐름과 이미지·텍스트 데이터 처리 과정을 실습했습니다.

특히 이후 텍스트 분류 프로젝트와 발화 분석 프로젝트를 진행하면서, 데이터 전처리, 모델 입력 구조, 학습 결과 평가 흐름을 이해하는 데 기반이 되었습니다.
