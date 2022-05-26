# AI-Pose
### 1. PoseNet 오픈소스 사용
 - PoseNet 중에서도 경량모델인 MobileNet으로 학습된 모델을 사용 => 접근성 강화

### 2. 판단하는 자세 종류
 - O, X, 만세(HandsUp), 스트레칭, 팔벌려뛰기(Stretching2)
 - 판단하는 자세별로 파일을 나누어 둠

### 3. 파일 설명
  #### .html
  - PoseNet을 사용하기 위한 script파일 로드. (중요 코드는 js 파일에 들어있다.)
  #### .js
  - 판단하는 자세별로 코드를 나누어 두었다. (OX, XHandsUp, Stretching, Stretching2)
  - js 파일에서 하는 기능들
      1. 웹캠 켜는 코드
      2. PoseNet모델을 불러오는 코드
      3. 자세를 판단하고 화면에 그리는 코드
      4. timer 기능 코드

### 4. 예시
![O](https://user-images.githubusercontent.com/70802352/170471649-ca61c360-d21d-41de-9d14-d7a40ae89484.jpg)
![스트레칭](https://user-images.githubusercontent.com/70802352/170471533-c2475ae7-d677-4dde-a869-d9153e125e7e.jpg)


### 5. 접속 링크
#### OX
https://dongle06.github.io/AI-Pose/OX.html

#### XHandsUp
https://dongle06.github.io/AI-Pose/XHandsUp.html

#### Stretching
https://dongle06.github.io/AI-Pose/Stretching.html

#### Stretching2 (팔벌려뛰기)
https://dongle06.github.io/AI-Pose/Stretching2.html
