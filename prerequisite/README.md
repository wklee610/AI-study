# [용어 정리]

**인공지능 (Artifical Intelligence)**
- 학습하고 추론할 수 있는 지능을 가진 컴퓨터 시스템을 만드는 기술

**강인공지능 vs 약인공지능**
- 강인공지능: 인공일반지능, 사람의 지능과 유사 (혼자 모든 것을 다 하는 AI)
- 약인공지능: 특정 분야에서 사람을 돕는 보조 AI (음성 비서, 자율주행 etc.)

**머신러닝 (Machine Learning)**
- 데이터에서 규칙을 학습하는 알고리즘을 연구하는 분야 (scikit-learn)

**딥러닝 (Deep Learning)**
- 인공신경망(Artificial Neural Network, ANN)을 기반으로 한 머신러닝 분야 
- 라이브러리: [Tensorflow](https://www.tensorflow.org/?hl=ko)
- 라이브러리: [Pytorch](https://pytorch.org/)

**이진 분류 (Binary Classification)**
- 머신러닝에서 여러 개의 종류 (혹은 클래스) 중 하나를 구별해 내는 문제를 Classification
- 2개의 클래스 중 하나를 고르는 문제

**특성 (Feature)**
- 데이터를 표현하는 특징

**[Matplotlib](https://matplotlib.org/)**
- 파이썬 과학계산용 그래프 패키지

**k-최근접 이웃 알고리즘 (k-Nearest Neighbors Algorithm, KNN)**
- 머신러닝 알고리즘
- 인접한 샘플을 기반으로 예측을 수행

**훈련 (Training)**
- 머신러닝 알고리즘이 데이터에서 규칙을 찾는 과정 또는 모델에 데이터를 전달하여 규칙을 학습하는 과정

**지도학습 (Supervised Learning)**
- 입력(데이터)과 정답으로 이루어진 훈련 데이터가 필요하며, 새로운 데이터를 예측하는데 활용

**비지도학습 (Unsupervised Learning)**
- 타깃 데이터 없이 입력 데이터만 있을 때 사용
- 정답을 사용하지 않으므로, 맞힐 수 없지만 데이터를 잘 파악하거나 변형하는데 도움

**훈련 데이터 (Traning Data)**
- 필요한 입력(데이터)와 타깃을 합쳐 놓은 것

**훈련 세트 / 테스트 세트 (Train Set / Test Set)**
- 모델을 훈련할 때는 훈련 세트를 사용하고 평가는 테스트 세트로 진행
- 테스트 세트는 전체 데이터에서 20 ~ 30%

**샘플링 편향 (Sampling Bias)**
- 훈련 세트와 테스트 세트에 샘플링이 고르게 섞여 있지 않을 때, 샘플링 편향 나타냄
- 지도 학습 모델을 만들 수 없음

**[NumPy](https://numpy.org/)**
- 파이썬 배열 라이브러리
- 고차원의 배열을 손쉽게 만들고 조작

**데이터 전처리 (Data Preprocessing)**
- 머신러닝 모델에 훈련 데이터를 주입하기 전 가공하는 단계
- 특성값을 일정한 기준으로 맞추어 주는 작업
- 데이터를 표현하는 기준이 다르면 알고리즘을 올바르게 예측 불가능

**브로드캐스팅 (Broadcasting)**
- 조건을 만족하면 모양이 다른 배열 간의 연산을 가능하게 해주는 기능