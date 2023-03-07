# Portfolio

` 주니어 데이터 분석가 조재민입니다. 도메인 지식인 기계공학을 이용하여 여러 공학 문제의 데이터를 분석하고 이에 대한 인사이트를 도출하는
것을 목표로 하고 있습니다. image object detection을 이용한 불량 검출과 video object tracking을 이용한 차량 추적을 프로젝트로 진행하였습니다. `

## **📝 프로젝트 개요**

<img width="100%" alt="nextlab" src="https://github.com/novamp2016/portfolio/blob/main/images/nextlab.png"/>

> **프로젝트:** [Nextlab 프로젝트](https://github.com/novamp2016/Nextlab-project)
>
> **기획 및 제작:** 조재민
>
> **분류:** 기업협업 프로젝트
>
> **제작 기간:** 2023.01 - 2023.02
>
> **주요 기능:** object detection, ReID
>
> **사용 기술:** Python

<details>
<summary>Nextlab 프로젝트 요약</summary>
<div markdown="1">
<br/>
  
* YOLO 모델을 이용하여 차량 추적을 구현함.
* ReID 모델을 적용하기 위해 포착된 차량의 정보를 다른 영상의 차량 추적에서 이용할 수 있게 함.
* 실제 환경에 적용하기 전에 모델 간의 특성을 확인하기 위해서 차량 이미지 데이터셋을 이용하여 선행 성능 검증을 함.
* 가장 적합하다고 판단한 모델을 실제 환경에 적용하여 결과를 분석함.
* 결과 : 시내 도로 같은 차량의 행동 변수가 많고 차간 거리가 가까운 도로에서는 적용이 힘들다 판단됨. 행동 변수가 적은 주차장 출입구나 차간 거리가 먼 고속도로와 같은 상황에는 일부 적용 가능하다고 판단함.
<br>
</div>
</details>

<p align="center"><img width="44%" alt="nextlab" src="https://github.com/novamp2016/portfolio/blob/main/images/casting.png"/></p>

> **프로젝트:** [주조공정 불량품 검출 프로젝트](https://github.com/novamp2016/Defective-detection-of-casting-process)
>
> **기획 및 제작:** 조재민
>
> **분류:** 개인 프로젝트
>
> **제작 기간:** 2022.10 - 2022.11
>
> **주요 기능:** image classification, object detection
>
> **사용 기술:** Python 

<details>
<summary>주조공정 불량품 검출 프로젝트 요약</summary>
<div markdown="1">
  
  
* 데이터셋이 양품과 불량품으로 라벨링 되어 있음.
* image classification을 위해 CNN 모델을 구현함.
* CNN 모델로는 결함의 위치를 확인 불가능하여 기존의 데이터셋에서 추가로 라벨링 한 후 object detection을 YOLO 모델로 구현함.
* 결함이 주로 일어나는 위치를 시각화하고 결과를 분석함.
* 결과 : 테스트 데이터셋에서 accuracy가 0.978인 CNN 모델을 구현하였다. CNN 모델이 불량이라 판단한 이미지들에 대하여 결함의 위치
와 종류를 인식하는 object detection을 YOLO 모델로 구현함.
  
</div>
</details>

> **프로젝트:** [살균기 공정 예측 프로젝트](https://github.com/novamp2016/Pasteurizer-process-prediction)
>
> **기획 및 제작:** 조재민
>
> **분류:** 개인 프로젝트
>
> **제작 기간:** 2022.10 - 2022.11
> 
> **주요 기능:** classification
>
> **사용 기술:** Python, HTML

<details>
<summary>프로젝트 요약</summary>
<div markdown="1">
  
  
* 데이터셋이 온도와 작동 상태에 따른 불량 여부가 라벨링 되어 있음.
* Scikit-learn의 XGBClassifier을 이용하여 머신러닝 분류 모델을 구현하고 RandomizedSearchCV로 하이퍼파라미터 튜닝을 진행함.
* 입력되는 값에 따른 예측값을 확인할 수 있게 flask를 이용하여 웹 페이지로 구현함.
* 결과 : 테스트 데이터셋에서 weighted avg 기준 precision은 0.89, f1-score는 0.77인 머신러닝 모델을 구현함. 입력되는 온도와 작동 상태에 따른 불량 예측을 웹 페이지에서 확인할 수 있게 구현함
  
</div>
</details>

## **🛠 기술 및 도구**

### Python
* 기본적인 문제해결을 위한 Python 스킬 보유.
* Scikit-learn을 이용하여 분류, 회귀, 클러스터링 등의 머신러닝 문제해결 가능, 파이프라인 구현 가능.
* Tensorflow, keras를 이용하여 간단한 딥러닝 모델을 구현 가능.
* Pandas와 PySpark를 사용하여 데이터를 다룰 수 있으며, Matplotlib을 이용하여 시각화 가능.
* Flask를 통한 간단한 대시보드 구현 가능.
### SQL
* Join을 이용한 쿼리와 중첩 서브 쿼리를 사용하여 데이터를 추출 및 분석 가능.
* PySpark에 기본적인 SQL 구문을 적용 가능.
### Others
* Git을 통한 기본적인 협업 가능.
* HTML를 이용하여 간단한 Flask 웹 페이지 구현 가능.

