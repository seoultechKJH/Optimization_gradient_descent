# Optimization_gradient_descent
gradient descent 최적화 알고리즘의 성능과 관련하여, 여러 변수를 고려한 고차원 공간에서 learning rate와 momentum의 조절 여부가 선형회귀 최적화 결과에 미치는 영향 분석


# Dataset
- Python sklearn에서 제공하는 boston 집값 예측 dataset


# Model
- (case 1) learning rate 0.0001 / momentum X
- (case 2) learning rate 0.1 / momentum X
- (case 3) learning rate 0.0001 / momentum 50%
- (case 4) learning rate 0.1 / momentum 50%


# Result
learning rate와 momentum 적용여부 조건을 달리하여 총 4개의 모델을 실험한 결과, momentum이 적용되지 않은 경우에는 learning rate의 크기에 상관없이 오차가 줄어드는 것으로 보아, 데이터의 분포가 비교적 규칙적인 형태를 띠고 있을 것이라 추측했으나, momentum을 적용했을 때 learning rate가 크면 최적해에 수렴하지 않는 것으로 보아 다른 조건과의 혼합에 있어서 learning rate 값의 역할이 중요함을 알 수 있음
![image](https://github.com/user-attachments/assets/3cfaa0bf-6ace-4cef-9269-6a27d89dbd23)
