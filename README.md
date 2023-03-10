# PyTorch를 공부하기 전에..
> 인공지능, 머신러닝, 딥러닝이 무엇인지,,
> 파이토치가 무엇인지, 다른 프레임워크와 비교하여 어떠한 장단점이 있는지,,

> 지금부터 끄적이는 내용은 '파이토치 첫걸음'(최건호 지음)을 밑바탕으로 합니다.

# 1. 딥러닝(deep learning)에 관하여
## 1.1 딥러닝이란 무엇인가?
> 딥러닝에 대해 알아보려면 먼저 딥러닝이 속한 머신러닝에 대해 이해하고 또한 머신러닝을 포함하고 있는 [**인공지능**](https://cloud.google.com/learn/what-is-artificial-intelligence?hl=ko)이라는 더 포괄적 개념에 대해서 짚고 넘어가야 한다.  
직관적으로 인공지능 문제를 푸는 방법 중 하나로 머신러닝이라는 접근 방식이 있었고, 머신러닝적 접근 중 한 가지로 딥러닝이 있다고 이해하면 쉽다.
  - 인공지능 : 기계가 인간의 '인지 과정'을 모방하는 것.
    - 인지 과정의 예시) 학습, 문제 해결
  - 머신러닝 : 명시적으로 프로그래밍되지 않은 상태에서 기계에게 학습할 능력을 부여하는 것.
    - 머신러닝 알고리즘 종류) 서포트 벡터 머신, k-NN, 결정 트리, 인공 신경망 등등
  - 머신러닝의 주요 학습 세 분야
    1. 지도학습(Supervised Learning) : 데이터와 각각에 해당하는 정답 쌍이 존재할 때 데이터와 정답 간의 상관관계를 모델링하는 방식  
      - ex) 어떤 사진이 주어질 때 이 사진이 강아지 사진인지, 고양이 사진인지 구분하는 문제 -> 즉, 누군가 미리 구분해놓은 어떤 패턴을 기계가 배우는 방식  

    2. 비지도학습(Unsupervised Learning) : 데이터만 있고 정답이 존재하지 않는 상황에서 데이터에 숨겨진 특정 패턴을 찾는 과정  

    3. 강화학습(Reinforcement Learning) :  특정 환경에서 어떤 행동을 했을 때 결과로 얻어지는 보상을 통해 학습하는 알고리즘 -> 최종 보상을 극대화하도록 학습하는 방식  

## 1.2 딥러닝을 왜 배워야 하는가?
> 딥러닝이 어떠한 가능성이 있기 때문에 배워야하는 것일까? 사람과 컴퓨터의 차이를 생각해보자. 컴퓨터는 무수히 많은 연산을 사람과 다르게 쉽고 빠르게 처리할 수 있다. 반면 사람은 자연스럽게 물체를 보고  인지하고, 감각적으로 얻은 자극을 종합하여 사고할 수 있다는 점이 큰 차이다.  
> 기존의 컴퓨터 알고리즘은 이러한 면에서는 사람의 수준을 따라올 수 없었다. 이에 비해 딥러닝 모델들은 기존 알고리즘으로 풀기 어려웠던 문제들, 사람에겐 쉽지만 컴퓨터에게 어려웠던 문제들을 풀어나가고 있다. 

## 1.3 딥러닝으로 무엇을 할 수 있는가?
> 딥러닝 기술이 해결해나가고 있는 문제 중 대표적인 것은 '물체의 인식 문제'이다. 인간의 오차율이 5% 정도 된다는 실험 결과에 비해 이미 2017년에 오차율이 2.25% 에 도달하여 인간을 넘어섰다고 할 수 있다.
이러한 사물 인식을 시작으로 많은 것들을 할 수 있게 된다.  
> 하나의 예로 물체를 구분하는 것을 넘어서 위치와 경계선 또한 구할 수 있게 된다. 그렇게 되면 시야에 들어오는 물체들을 인식하고 어떠한 행동을 해야할지 결정을 내릴 수도 있고, 물체들의 이동 패턴을 배울 수도 있다. 즉, 모든 분야에 적용될 수 있다..


