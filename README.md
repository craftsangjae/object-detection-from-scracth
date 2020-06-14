Object Detection Model From Scratch
---

### Objective

Object Detection은 사물의 위치가 어디에 있는지를 찾는 모형입니다. 
대표적인 딥러닝 모델로는 YOLO / Faster RCNN / SSD가 있는데, 이 중 SSD를 중심으로 모형을 작성하였습니다. 
간단히 모델을 학습시키기 위해 아래과 같이 MNIST를 활용하여 문제를 접근합니다.

<img width="619" src="https://user-images.githubusercontent.com/66022630/84582794-91bb0100-ae2b-11ea-9a0d-990edf371ec7.png">

### 구성

실행 관련된 코드들은 `scripts/`에 수록되어 있습니다.

1. Problem Definition
2. Build Single Shot Detector
3. Build Prior Boxes
4. Train single Shot Model
5. Infer Model

