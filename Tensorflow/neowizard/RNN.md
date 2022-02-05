# RNN 개념 정리 해보기 

RNN이란? - Recurrent Neural Network, 순환 신경망

*I work at google*
이 문장을 해석할 때 주어가 앞이기에 당연히 동사가 오고, 전치사 뒤에는 명사!

Sequence Data 

= 시퀀스 데이터란 각각의 데이터가 순서가 있는 데이터를 말하며, 다양한 분야에서 찾을 수가 있다. 예를 들어, 음성신호, 텍스트, 주가 데이터 등이 있다.
시간의 경과에 따라서 데이터가 순차적으로 들어온다는 것. 

이런 식으로 자연스럽게 추론하게 되는데, 이를 수학적으로 모델링한것이 'RNN'이다. 

![image](https://user-images.githubusercontent.com/76649707/152628409-fc9295d6-a50d-4dc5-ad2f-69b967591130.png)
<img width="547" alt="스크린샷 2022-02-05 오후 1 22 05" src="https://user-images.githubusercontent.com/76649707/152628447-b08fb9cd-3dfe-43aa-bcfd-759173cded9a.png">

간략하게 위와 같은 구조로서 과거 자신의 정보(가중치)를 기억, 학습에 반영합니다. 

은닉층의 tanh 계산값이 출력값으로 계산되는 것과 동시에 다시 입력층으로 되돌아감.

DNN과 RNN의 차이점은 relu가 아닌 tanh사용, 은닉층의 tanh 계산값이 출력값으로 계산되는 것과 동시에 다시 입력층으로 되돌아감.

<img width="519" alt="스크린샷 2022-02-05 오후 1 23 56" src="https://user-images.githubusercontent.com/76649707/152628495-eb5b7f80-dcc1-405c-bd5a-9a59e98e337c.png">
**https://www.youtube.com/watch?v=h9T9HlVvsDo&list=PLS8gIc2q83OhM0RTktKDitgZGX5dHo7Vs&index=20**

I work at google. 정성적으로 분석
