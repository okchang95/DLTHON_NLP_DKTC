# [DKTC (Dataset of Korean Threatening Conversations)](https://github.com/tunib-ai/DKTC)
---
DLTON에서 활용한 데이터셋은 TUNiB에서 제공된 DKTC(Dataset of Korean Threatening Conversations)입니다.   
이 데이터셋은 멀티턴 대화 형식으로 구성되어 있으며, 총 4가지 클래스(협박 대화, 갈취 대화, 직장 내 괴롭힘 대화, 기타 괴롭힘 대화)로 세분화되어 있습니다.   
데이터셋은 크게 3가지 파일로 구성되어 있습니다.  


| 파일명         | 설명                   |
| -------------- | ---------------------- |
| train.csv      | 1. idx = 인덱스\n2. class = 0~3\n   - class 0: 협박 대화\n   - class 1: 갈취 대화\n   - class 2: 직장 내 괴롭힘 대화\n   - class 3: 기타 괴롭힘 대화\n3. conversation = \n으로 구분된 멀티턴 텍스트 대화 |
| test.json      | 1. t_### = 인덱스\n2. text = 대화 |
| submission.csv | 1. file_name = 인덱스\n2. class = 예측값 |


*원본 링크와 다르게, 해당 DLTON에서는 (원본)sample_answersheet.json이 submission.csv 파일로 제공되었습니다.  
