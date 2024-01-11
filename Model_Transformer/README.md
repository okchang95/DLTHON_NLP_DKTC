# Transformer

트랜스포머를 활용하여, DKTC 데이터셋을 기반으로 한 4가지 클래스(협박 대화, 갈취 대화, 직장 내 괴롭힘 대화, 기타 괴롭힘 대화) 분류 작업을 진행했습니다.   

### 사용한 트랜스포머 모델
- KLUE-BERT: 90% 달성
- kobigbird-bert-base: 91.5% 달성
- kykim/bert-kor-base: 92.25% 달성
- GPT-3.5 fine tuning(시간 및 비용 문제로 400문장): 86.5% 달성

### 선택 기준
허깅페이스의 검색결과 기준으로 한국어 bert 모델중에 많이 사용하는 순으로 정했습니다.

### 앙상블
klue bert, kobigbird bert, kykim bert를 앙상블하여 더 나은 점수를 기대하였으나 92% 달성으로 앙상블의 효과가 없음을 확인하였습니다.

### 참고문헌
- [Transformers와 Tensorflow를 활용한 BERT Fine-tuning](https://velog.io/@jaehyeong/Fine-tuning-Bert-using-Transformers-and-TensorFlow)
- [huggingface BERT 검색결과 filter with korean](https://huggingface.co/models?pipeline_tag=fill-mask&language=ko&sort=likes&search=bert)


