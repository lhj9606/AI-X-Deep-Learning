YOLOv5를 이용한 Vehicle Detection & Validation with Video Game Graphics (AI-X:Deep-Learning)

Hanyang University 2021 / AI+X:Deep Learning / Final Project

## Member

|  이름  |    학과    |    학번    |        E-mail         | 역할 |
| :----: | :--------: | :--------: | :-------------------: | :----:|
| 이홍준 | 기계공학부 | 2015011203 | lhj9606@hanyang.ac.kr | Everything |

## 1. Proposal (Option A)

 4차 산업혁명 시대가 대두되면서, 여러 기술들이 발전하고 주목받고 있지만 그 중에서도 우리 생활에 밀접하게 관련있고, 접근성이 좋은 기술 중장 주목받는 기술 중 하나를 꼽자면 바로 '**자율주행**' 기술일 것이다. 이러한 자율주행 기술이 급격하게 발전하게 된 이유 중 하나는 Deep Learning(Deep Neural Network)의 발전, 그리고 CNN(Convolutional Neural Network) 등의 등장으로 인한 Computer Vision 분야의 많은 기술적 도약이 있었기에 가능해졌다.



<iframe title="vimeo-player" src="https://player.vimeo.com/video/192179726?h=849b6a5ec9" width="640" height="360" frameborder="0" allowfullscreen></iframe>



 ### Need

 >  자율주행 자동차는 '인지', '판단', '제어'의 3가지 Step으로 스스로 주행을 관장하는데, '인지' 단계에서 ***카메라(Camera), 레이더(Rader), 라이다(LiDAR)*** 등의 여러 센서로 부터 취합한 정보를 바탕으로 차량 주변의 환경을 인식하며, 이를 토대로 '판단'과 '제어'를 수행한다. 즉 **'인지'** 단계가 자율주행 알고리즘에 있어 가장 첫번째 단계이므로, 자율주행에서 가장 중요하면서도 차량의 주변 환경을 명확하게 인식해야만 안전한 주행이 가능하기 때문에 매우 중요한 단계라고 할 수 있다.
 >
 >  이러한 **'인지'** 수행 과정에서 카메라, 레이더, 라이다 등의 센서 정보들 모두 중요하며, 각각의 장단점으로 인해 상호보완적으로 사용되지만, 물체의 종류를 식별하는 데에 가장 중요한 정보는 바로 ***'카메라 데이터'*** 이다. 



### Objective

>  본 프로젝트는 YOLOv5를 기반으로 하여, 자율주행 환경에 필요한 이미지들을 모델에 학습하고, 자율주행 환경에 필요한 이미지 검출 속도에 맞게 모델을 튜닝할 예정이다. 
>
>  학습된 모델을 토대로 실제 차량에 탑재하여, 실제 차량과 그 이외의 주행 상황에 등장 가능한 물체에 대한 인식을 검출하는 시도를 하면 좋겠지만, 실제 차량에 컴퓨터와 카메라를 탑재하여 이를 검증해보는 것이 어렵다. 따라서, 본 프로젝트에서는 자율주행 환경을 모사 가능한 일부 게임 (ex. *GTA5, Euro Truck Simulator, Forza Horizon* 등)의 화면 데이터를 카메라 데이터로 대응시켜 모델의 객체 검출이 잘 이뤄지는지 확인해볼 예정이다.



## 2. Datasets



## 3. Methodology

####  3.1. Pre-Processing

####  3.2.  

#### 3.3. YOLOv5 (You Only Look Once)

#### 3.4. OpenCV






## 4. Evaluation & Analysis


## 5. Related Work


#### Autonomous Driving 

## 6. Conclusion & Discussion
