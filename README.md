# HearRate_Control_Car
심장박동 센서(핸들)를 이용하여 큰 사고를 방지하는 차를 아두이노를 통해 만들었습니다.
(심장박둉 센서를 핸들에 두어 제어하는 방식입니다 / 특정 범위( < bpm 70)인 경우 모터와 비상등을 제어)

1. 모터 제어
2. 비상등 제어

## USE
- Arduino, C



## 배경

![배경](https://user-images.githubusercontent.com/53526987/150732044-81887812-d594-4b25-ad9a-28940f7337e9.jpg)

< 출처: 도로교통공단 충북 지부 >

다음과 같이 졸음 운전으로 인해 생긴 사고가 많이 발생하는 것을 볼 수 있습니다.

해당 문제를 심장 박동수와 연결하여 문제를 해결하려고 했습니다.

그래서 논문을 통해 심박 변이도 측정을 통한 운전자 졸음 및 각성 상태 분석하였습니다.

![그림1](https://user-images.githubusercontent.com/53526987/150732424-7eacd1f4-6d8c-4efd-a273-194f65062264.png)

<출처: 한국자동차공학회 지회 학술대회 논문집, 2015.10, 4-5(2pages)>

즉,

각성상태은 깨어있는 상태이고 R-R interval은 심장박동 간격으로 값이 증가할 수록 심박수는 느려지는 것을 알 수 있습니다.

그래서 **Serial-Osciloscope-v1.5**를 이용해서 심장박동 수를 측정하였습니다.

![심전도 파악](https://user-images.githubusercontent.com/53526987/150732031-1f9ad341-f351-4947-b95a-16b52f0380f6.PNG)

평균 70BPM으로 잡고 프로그래밍을 하게 되었습니다.

다음과 같은 정보를 가지고 센서들을 심장박동수를 가지고 제어하기 위해 제어 장치 배경도를 제작하여 개발하였습니다.



## 제어 장치 배경도

![1](https://user-images.githubusercontent.com/53526987/150732021-45f36672-10a2-48b7-849b-468d44fe5c1e.PNG)





## IMAGE
![자동차 그림](https://user-images.githubusercontent.com/53526987/150733486-fb687a6f-893f-4790-bb81-337bf8b6fcfa.png)

