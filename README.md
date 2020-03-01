# 프로그라피 6기 딥러닝 사전과제

by. 장원범, 조성만



## 과제 설명
사전과제는 딥러닝 모델의 구조를 원하는 형태로 변경할 수 있는지, 백엔드와의 연동을 위한 코드를 작성할 수 있는지에 대한 부분을 파악하기 위하여 기획하게 되었습니다. 

사전과제를 완성하지 못하더라도, 선발에서 제외되는 것이 아니므로 **최선을 다해주세요!**

### 사전과제 주제
1. 데이터 및 네트워크 구조 변경  
2. 아래의 조건을 만족시키는 모델을 만드세요
     

### 필수사항
1. VGG-16으로 네트워크를 구성하고, MNIST 데이터를 RGB 채널로 변경해주세요.
2. (1)의 모델 구조에서 model initialization, inference 부분을  함수형태로 작성해주세요. 
   (객체 형태로 작성하여도 무관합니다)
3. (2)의 구조에서 Conv2_1의 입력을 첫번째 Dense 입력에 추가해주는 구조를 추가해주세요. (Skip connection 구조)
4. (3)에서 나온 모델을 RGB체널로 바꾼 MNIST로 학습해주세요.
5. ```python test.py```을 통해 테스트 코드를 실행시켜 정확도를 출력해주세요.
6. 정확도와 구현한 모델의 ADT를 README.md에 간단히 요약해주세요.

- 프레임워크(Tensorflow, Keras, Pytorch 등) 은 원하는 대로 선택해주시면 됩니다.
  

### 유의사항
- repository의 이름은 'prography-6th-deep-본인의이름'으로 설정해주시길 바랍니다.
  (ex: prography-6th-deep-chosungman / prography-6th-deep-sungmancho)  
- **마감기한은 3/5 23:59며 기간내 commit만 인정됩니다.**
- jupyter notebook이 아닌 python 파일로 작업하시길 바랍니다.
  

## 문의
문의는 카카오톡 오픈체팅방을 통해서 진행해주시면 되겠습니다.
[https://open.kakao.com/o/gr9KqaZb](https://open.kakao.com/o/gr9KqaZb)
