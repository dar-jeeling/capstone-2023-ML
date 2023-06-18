# capstone-2023-ML

## 구현

![](https://i.imgur.com/fKnBlx6.png)

## 사용 모델

### Xception

Xception에서는 depthwise separable convolution이라는 개념을 사용하여 일반적인 CNN보다 모델의 파라미터 수를 줄이고 계산 효율성을 높혀주어, 같은 수의 파라미터를 가지고 더 깊은 신경망 구조를 구현할 수 있음.​

Xception 모델을 통해 공간적인 상관 관계와 채널 간 상관관계를 분리하여 처리할 수 있으며, 이는 데이터의 복잡성을 더욱 잘 포착하고 채널 간 상관관계를 효과적으로 학습함​

로고 이미지의 경우 종종 복잡한 패턴과 독특한 기하적 구조를 가지고 있기 때문에 Xception은 이러한 복잡성을 잘 처리하면서도 효율적인 학습이 가능하므로 Logo Detection에 해당 모델이 적합하다고 판단 후 사용함​
