# Deep Learning 

딥러닝을 활용하여, DKTC 데이터셋을 기반으로 한 4가지 클래스(협박 대화, 갈취 대화, 직장 내 괴롭힘 대화, 기타 괴롭힘 대화) 분류 작업을 진행했습니다.   

사용된 딥러닝 모델은 다음과 같습니다.
- LSTM(Long Short-Term Memory)
- Bidirectional LSTM
- Simple RNN
- GRU
- (+ Augmentation)

### 과적합 문제로 augmentation(random swap, deletion) 적용:
  > RS : 문장 내 임의의 두 단어의 위치를 바꾸는 것<br>
  > RD : 임의의 단어 삭제
- blog : https://fish-tank.tistory.com/95
- github : [참고한 korEDA aug github](https://github.com/catSirup/KorEDA/blob/master/README.md)
  

- 결과 :
  
  <img width="760" alt="image" src="https://github.com/Eunssong/DLTHON_NLP_DKTC/assets/124979889/59639751-f26a-4f2b-8e16-44cb386a01ec">


<!--
<img width="300" alt="image" src="https://github.com/Eunssong/DLTHON_NLP_DKTC/assets/124979889/ffebb1ed-9d0c-4ecc-85d8-bffd84740f67">


### 리더보드 test accuracy : 

![image](https://github.com/Eunssong/DLTON_NLP_DKTC/assets/124979889/73e699bd-cc1b-4778-b88d-1897431647fa)

나중에 읽어볼만한 논문: https://journalofbigdata.springeropen.com/articles/10.1186/s40537-021-00492-0#Sec8
-->


