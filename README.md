# DLTHON_NLP_DKTC 다중분류 프로젝트: 한국어 위협 대화 데이터셋 활용

**DLTHON_NLP 기간: 2024년 1월 10일부터 1월 12일**   

**팀명: 바른말 고운말**

DKTC (Dataset of Korean Threatening Conversations)을 활용한 다중 분류 프로젝트를 진행하였습니다.   
이 프로젝트에서 저희 팀은 **머신러닝과 딥러닝 모델을 활용하여 주어진 DKTC dataset(한국어 위협 대화 데이터셋)의 4가지 클래스 분류**를 수행하였습니다.
| 클래스명         | 샘플 수 |
| ---------------- | ------- |
| 기타 괴롭힘 대화 | 1094    |
| 갈취 대화        | 981     |
| 직장 내 괴롭힘 대화 | 979    |
| 협박 대화        | 896     |

DKTC 데이터셋은 멀티턴 대화 형식으로 구성되어 있습니다.

![image](https://github.com/Eunssong/DLTON_NLP_DKTC/assets/134351442/c8220424-ad30-4e9e-a7d4-f62007aee8d0)

사용된 모델은 다음과 같습니다.  

| 분야        | 사용된 모델                   |
| ----------- | ----------------------------- |
| 머신러닝     | SGD Classifier, LinearSVC, VotingClassifier, MultinomialNB, LogisticRegression, ComplementNB, DecisionTreeClassifier, RandomForestClassifier, GradientBoostingClassifier, LGBMClassifier, XGBClassifier |
| 딥러닝       | LSTM,  Bidirectional LSTM, Simple RNN, GRU|
| 트랜스포머   | BERT, GPT-3.5 |

## 결과

| Team Name                  | Accuracy Score |
|----------------------------|----------------|
| 바른말 고운말 simpleRNN     | 0.3            |
| 바른말 고운말 aug_simpleRNN | 0.345          |
| 바른말 고운말 LSTM          | 0.54           |
| 바른말 고운말 GRU           | 0.56           |
| 바른말 고운말 bi_LSTM       | 0.5675         |
| 바른말 고운말 aug_GRU       | 0.6275         |
| 바른말 고운말 aug+LSTM      | 0.6825         |
| 바른말 고운말 aug_LSTM      | 0.7325         |
| 바른말 고운말 aug_bi_LSTM   | 0.755          |
| 바른말 고운말_ML2           | 0.81           |
| 바른말 고운말_MLensemble    | 0.81           |
| 바른말 고운말 ML            | 0.815          |
| 바른말 고운말 aug_ML2       | 0.815          |
| 바른말 고운말 aug_ensemble   | 0.8175         |
| 바른말 고운말 aug_ML        | 0.82           |
| 바른말 고운말 gpt3.5-ft     | 0.865          |
| 바른말 고운말 klue/bert-base | 0.9            |
| 바른말 고운말 bert augment   | 0.9125         |
| 바른말 고운말               | 0.915          |
| 바른말 고운말 kobigbird      | 0.915          |
| 바른말 고운말 bert ensemble  | 0.92           |
| 바른말 고운말 kykim/bert-kor-base | 0.9225    |



